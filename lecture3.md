Data Types and Variables:
1. Int
   1. The int data type is used for variables that will store integers.
   2. Integers always take up 4 bytes of memory (32 bits).
   3. This means the range of values they can store is necessarily limited to 32 bits worth of information.
2. Unsigned int
   1. unsigned is a qualifier that can be applied to certain types (including int), which effectively doubles the positive range of variables of that type, at the cost of disallowing any negative values.
   3. You'll occasionally have use for unsigned variables in CS50.
3. Char
   1. The chhar data type is used for variables that will store single characters
   2. Characters will always take upto 1 byte of memory (8 bits). This mean the range of values they can store is necessarily limited to 8 bits worth of information.
   3. Thnaks to ASCII, we've developed a mapping of charcters like A,B,C, etc... to numeric values in the positive side of range.
4. Float
   1. The float data type is used for variables that will store floating-point values, also known as real numbers.
   2. Floating points values always take up 4 bytes of memory (32 bits).
   3. It's a little complicated to describe the range of a float, but suffice it to say with 32 bits of precision, some of which might be used for an integer part, we are limited in how precise we can be.
 5. Double
    1. The double data type is used for variables that will store floating-point values, also known as real numbers.
    2. The diffrence is that double are double precision. They always take up 8 bytes of memory (64 bits).
    3. With an additional 32 bits of precision relative to a float, doubles allow us to be specify much more precise real numbers.
 6. Void
    1. Its a type not a data type tho.
    2. Functions can have a void return type, which just mean the don't return a value.
    3. The parameter list of a functions can also be a void. It simply mran the functions take no parameters values.
    4. For now, think of void more as a placeholder for "nothing". It's more complex than that, but this should suffice for the better part of the course.
 7. CS50
    1. Bool
       • The bool data type is used for variables that will store a Boolean value. More precisely, they are capable only of storing one of two values: true and false.
       • Be sure to #include ‹cs50.h> atop your programs if you wish to use the bool type.
