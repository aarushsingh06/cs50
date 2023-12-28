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
       1. The bool data type is used for variables that will store a Boolean value. More precisely, they are capable only of storing one of two values: true and false.
       2. Be sure to #include ‹cs50.h> atop your programs if you wish to use the bool type.
    2. string
       1. The string data type is used for variables that will store a series of characters, which programmers typically call a string.
       2. Strings include things such as words, sentences, paragraphs, and the like.
       3. Be sure to #include ‹cs50.h› atop your programs if you wish to use the string type.
  8. Creating a variable.
     1. To bring a variable into existence, you need simply specify the data type of the variable and give it a name.
        1. int number;
        2. char letter;
     2. If you wish to create multiple variables of the same type, you specify the type name once, and then list as many variables of that type as you want.
        1. int height, width;
        2. float sortz, sarts, pi;
     3. In general, it's good practice to only declare variables when you need them.       
   9. Using a variable.
      1. After a variable has been declared, it's no longer necessary to specify that variable's type. (In fact, doing so has some unintended consequences!)
         1. int number;           //declaration
         2. number = 17;          //assignment
         3. cahr letter;          //declaration
         4. letter = 'H';         //assaignment
      2. If you are simultaneously declaring and setting the value of a variable (sometimes called initializing), you can consolidate this to one step.
         1. int number = 17;      //initialization
         2. char letter = 'H';    //initialization










