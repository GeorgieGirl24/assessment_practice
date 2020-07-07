class Cookies

---Attributes---

+ NAME_BRAND: (integer)
+ type (string)
+ total_package_amount(integer)
+ brand (string)
+ location (string)
+ current_available (integer)
+ expiration_date (datetime)

---Method---
+ change_type (takes `type` and changes it)
+ move_location (takes `location` and changes it)
+ is_name_brand? (evaluates `brand` with NAME_BRAND; returns a boolean)
+ is_expired? (evaluates `expiration_date` to `current_date`; returns boolean)
