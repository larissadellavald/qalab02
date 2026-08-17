Title: Behavior when the minute field is set to "60"
Do this: Set the hour field to "3", set the minute field to "60", set the period to "AM", then press the "Save/Activate" button. 
Expect: Either the field rejects the value or the configuration of the alarm fails.

Question for product owner: What happens when the minute field receives
a value outside the valid 0–59 range — is it blocked at input, or does
it fail on save?