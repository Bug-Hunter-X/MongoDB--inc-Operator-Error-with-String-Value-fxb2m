# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB, leading to an error. The `$inc` operator is used to increment a numerical field.  Using a string instead of a number will result in an error.

## Bug
The original code attempts to increment the `age` field by '1' (a string), which is not valid. 

## Solution
The solution corrects the query by using a number (1) instead of a string to increment the `age` field.