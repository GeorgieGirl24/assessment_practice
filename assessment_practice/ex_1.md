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

- seat_guests (evaluates `guest_capacity` and `unoccupied` and returns a 'string')

- needs_cleaning (evaluates `unoccupied` and `is_dirty` and preforms an action to change `is_dirty` to `false`.)

- change_location (evaluates `current_location` and preforms an action to move it)

- needs_repair (evaluates `bad_condition` and takes action to return a boolean response to `false`)
