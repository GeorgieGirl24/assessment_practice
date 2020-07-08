class Store

---Attributes---
+ location (string)
+ employees_on_duty (array)
+ occupancy_capacity (integer)
+ current_occupancy (integer)
+ is_open (boolean)

---Method---
+ open (assigns `is_open` to `true`)
+ walk_in (takes `current_capacity` adds 1)
+ calculate_open_capacity (subtract `current_occupancy` from `occupancy_capacity`; return results)
+ clock_in (adds to `employees_on_duty`)
+ re_locate ( changes the `location`)
+ walk_out (takes `current_occupancy` subtracts 1)
