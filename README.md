The lookup function in excel is used to find the approximate match of any one row or one column as per selection criteria, and it returns the value from the corresponding any one row or one column. This works like Vlookup, but the Lookup function’s major advantage is that it considers both row and column to find the lookup range value.

In simple terms, this function searches the lookup value in a row or a column and gives a matching value in the same location from another cell or column. This is a built-in worksheet function in Excel. So it can be used as a formula in a worksheet. It can be found in Lookup & References under the Formula tab on the ribbon. It is present on all the versions of MS Excel.
The LOOKUP function syntax has two types:

1. Vector

=LOOKUP(lookup-value, lookup-vector, result-vector)

Lookup Value: It is the value that we want to search in a range or array. It can be a text, number, reference, logical value or a name.
Lookup Vector: It is a single row or column containing data sorted in ascending order.
Result Vector: It is a single row or column having data and of the same size as the lookup vector.

2. Array

=LOOKUP(lookup_value, array)

Lookup _value: To search for a value in an array.
Array: It is the range of cells containing multiple rows and columns where you want to search the lookup value.
The Lookup function searches the lookup value in the Lookup vector and returns the value in the same position from the result vector. The function can return string, numeric, name depending upon the data type.

This function is used for finding prices of products from a data table, transactions from previous months/years, finding marks of students.
