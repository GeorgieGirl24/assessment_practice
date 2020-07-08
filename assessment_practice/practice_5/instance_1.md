class Anthropologie

---Attributes---
+ location: " 2234 1st Ave."
+ employees_on_duty: ["Jamie", "Lucas", "Stevie"]
+ occupancy_capacity: 26
+ current_occupancy: 0
+ is_open: false

---Method---
+ open: `is_open` = `true`
+ walk_in: `current_occupancy` = 1
+ calculate_open_capacity: 25
+ clock_in: `employees_on_duty` = ["Jamie", "Lucas", "Stevie", "Jo"]
+ re_locate: `location` = "423 Pearl St."
+ walk_out: `current_occupancy` = 0
