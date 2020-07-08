class Steakhouse

---Attributes---
+ ideal_employee_number (integer)
+ current_emmployee_number (integer)
+ managers_on_duty (array)
+ website (string)
+ is_dirty (boolean)

---Methods---
+ clean (takes `is_dirty` and sets it to `false`)
+ update_website (takes `website` and changes it)
+ calculate_hiring_needs (subtracts `current_emmployee_number` from `ideal_employee_number` and returns value)
+ change_shift (updates `managers_on_duty`)
