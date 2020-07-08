class Decor

---Attributes---

+ paint_color (string)
+ drapery_type (string)
+ number_of_can_lights (integer)
+ number_of_tables (integer)
+ type_of_sconces (string)
+ number_of_sconces (integer)
+ out_dated (boolean)
+ type_of_flooring (string)
+ number_of_broken_fixtures (integer)
+ most_recent_clean (datetime)
+ cushion_ripped (boolean)
+ expected_flooring (string)

---Method---
- change_paint (changes `paint_color`)

- change_flooring (evaluates the `type_of_flooring` and if that doesn't match  `expected_flooring`; change `type_of_flooring`)

- repair_cushion (takes `cushion_ripped` and returns `false`)

- calculate_total_bulbs_needed (evaluated `number_of_sconces` and `number_of_can_lights` returns integer)
