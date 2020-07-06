TableEight

+ material_type: "marble"
+ area_size: 92
+ current_location: "main dinning room"
+ guest_capacity: 8
+ unoccupied: true
+ is_dirty: true
+ bad_condition: true



---Method---
- seat_guests #=> "Seat Sam (party of 8) at this table."

- needs_cleaning #=> `is_dirty`: `false`

- change_location #=> "back dinning room"

- needs_repair #=> `false`
