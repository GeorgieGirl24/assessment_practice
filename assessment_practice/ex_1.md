class Table

---Attributes---

+ material_type (string)
+ area_size (integer)
+ current_location (string)
+ guest_capacity (integer)
+ unoccupied (boolean)
+ is_dirty (boolean)
+ bad_condition (boolean)


---Method---

- can_seat_guests? (evaluates `guest_capacity` and `unoccupied` and returns boolean)

- clean (evaluates `unoccupied` and `is_dirty` and preforms an action to change `is_dirty` to `false`.)

- change_location (evaluates `current_location` and preforms an action to move it)

- repair (evaluates `bad_condition` and takes action to return a boolean response to `false`)
