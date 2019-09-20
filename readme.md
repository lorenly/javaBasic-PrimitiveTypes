BooleanOperatorsTest.
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
	* Official Document: https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html
	* Reading and answering the expected output of the code without running.
	* Performing the logical Boolean operators and bitwise. 
2. Why the test failed at first?
	* The expected values are null or incorrect
3. Why you corrected the test that way?
	* I initialized the expected Boolean result.
4. Do you have further questions on this knowledge point?
	* None
CharTypeTest
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
	* Official Document: https://docs.oracle.com/javase/tutorial/java/data/characters.html
	* Learning escape sequence
	* Escaped characters 
2. Why the test failed at first?
	* The initialize values are whitespaces
3. Why you corrected the test that way?
	* I initialized the variables to the expected escape character
4. Do you have further questions on this knowledge point?
	* None
FloatingTypeTest
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
	* Official Document: https://docs.oracle.com/javase/8/docs/api/java/lang/Math.html
	* Learning data type conversion
	* Rounding off numbers
	* Check if numbers are real numbers or not
2. Why the test failed at first?
	* The initialized variables are having the MAX Integer value
	* No throw exception for non-real numbers
3. Why you corrected the test that way?
	* I used Math.Floor() for not rounding off
	* Math.Round() for rounding off
	* Throw exception error for non-real numbers.
4. Do you have further questions on this knowledge point?
	* No.
IntegerTypeTest
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
	* Official Document: https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html
	* Learning Primitive data types.
	* Maximum and Minimum values for each data types
2. Why the test failed at first?
	* The expected values are incorrect
3. Why you corrected the test that way?
	* I initialized the expected values to Max and Min value for each data type.
	* Computed manually and initialized constant values
	* Throw exception for ArithmeticException and NotImplementedException
4. Do you have further questions on this knowledge point?
	* None

