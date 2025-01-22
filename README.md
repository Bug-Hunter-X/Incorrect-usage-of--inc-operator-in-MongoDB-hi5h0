# Incorrect Usage of $inc Operator in MongoDB
This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string is provided as the increment value, the operation will not work as expected. 

## Bug
The original code uses the `$inc` operator with a string value, causing an unexpected result. 

## Solution
The corrected code uses a numeric value with the `$inc` operator, ensuring the field is incremented correctly.
