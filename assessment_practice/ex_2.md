TableEight

+ material_type: "marble"
+ area_size: 92
+ current_location: "main dinning room"
+ guest_capacity: 8
+ unoccupied: true
+ is_dirty: true
+ bad_condition: true



---Method---
- can_seat_guests?: `true`

- needs_cleaning #=> `is_dirty`: `false`

- change_location: `current_location` = "back dinning room"

- repair: `bad_condition` = `false`
