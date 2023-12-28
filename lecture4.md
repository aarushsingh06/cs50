Operators
1. Arithmetic Operators
   1.In order to manipulate and work with variables and values in C, we are have a number of operators at our disposal.
   2. In C we can add (+), subtract (-), multiply (*) and divide (/) numbers, as expected.
      1. int x = y + 1;
      2. x=x * 5;
   3. We also have the modulus operator, (%) which gives us the remainder when the number on the left of the operator is divided by the number on the right.
      1. int m = 13% 4; // m is now 1
   4. C also provides a shorthand way to apply an arithmetic operator to a single variable.
      1. x = x * 5;
      2. × *= 5;
   5. This trick works with all five basic arithmetic operators. C provides a further shorthand for incrementing or decrementing a variable by 1:
      1. X++;
      2. X--;
2. Boolean Expression.
   1. Boolean expressions are used in C for comparing values.
   2. All Boolean expressions in C evaluate to one of two possible values - true or false.
   3. We can use the result of evaluating a Boolean expression in other programming constructs such as deciding which branch in a conditional to take, or determining whether a loop should continue to run.
   4. Sometimes when working with Boolean expressions we will use variables of type bool, but we don't have to.
   5. In C, every nonzero value is equivalent to true, and zero is false.
   6. Two main types of Boolean expressions: logical operators and relational operators.
      1. Logical Operators.
         1. Logical AND (&&) is true if and only if both operand are true, otherwise false.
         2. Logical OR (||) is true if and only if at least one operand is true, otherwise false.
         3. Logical NOT (!) inverts the value of its operand.
      2. Relational operators.
         1. These behave as you would expect them to, and appear syntactically similar to how you may recall them from elementary arithmetic.
         2.  Less than (x < y)
         3.  Less than or equal to (x <= y)
         4.  Greater than (x > y)
         5.  Greater than or equal to (x >= y)
