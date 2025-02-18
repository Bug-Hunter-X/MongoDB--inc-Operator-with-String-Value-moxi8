# MongoDB $inc Operator with String Value
This example demonstrates an incorrect usage of the MongoDB $inc operator, where a string value is used instead of a number. This results in an unexpected update operation behavior or error.

**Bug:** The script attempts to increment the age field by '1' which is a string.  The correct approach is to use a numeric value (e.g., 1).

**Solution:**  Correctly using the $inc operator with a numerical value will update the age field correctly.