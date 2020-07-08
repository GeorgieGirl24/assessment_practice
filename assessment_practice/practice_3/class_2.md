class Instrument

---Attributes---
+ categorgy (string)
+ materials (array)
+ color (string)
+ length (float)
+ size (string)
+ is_hand_held (boolean)
+ fingers_needed_for_note (hash)
+ is_tuned (boolean)

---Method---
+ add_embellishment (takes `materials` and adds to the array)
+ paint (takes `color` and changes it)
+ tune (assign the value of `is_tuned` to `true`)
+ change_category (takes `categorgy` and changes it)
+ calculate_case_length (takes the `length` and adds a 2.3)
