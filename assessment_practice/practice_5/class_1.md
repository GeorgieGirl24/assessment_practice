class Store

---Attributes---
+ location (string)
+ employees_on_duty (array)
+ occupancy_capacity (integer)
+ current_capacity (integer)
+ is_open (boolean)

---Method---
+ open (assigns `is_open` to `true`)
+ calculate_open_capacity (subtract `current_capacity` from `occupancy_capacity`; return results)
+ clock_in (adds to `employees_on_duty`)
+ re_locate ( changes the `location`)
