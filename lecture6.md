Loops
1. Loops allow your programs to execute lines of code repeatedly, saving you from needing to copy and paste or otherwise repeat lines of code.
2. C provides a few different ways to implement loops in your programs, some of which likely look familiar from Scratch.
   1. While (true)
      1. This is what we call an infinite loop. The lines of code between the curly braces will execute repeatedly from top to bottom, until and unless we break out of it (as with a break; statement) or otherwise kill our program.
   2. While (boolean-exp)
      1. If the boolean-expr evaluates to true, all lines of code between the curly braces will execute repeatedly, in order from top-to-bottom, until boolean-expr evaluates to false.
      2. Somewhat confusingly, the behavior of the Scratch block is reversed, but it is the closest analog.
   3. Do while loop (boolean-exp)
      1. This loop will execute all lines of code between the curly braces once, and then, if the boolean-expr evaluates to true, will go back and repeat that process until boolean-expr evaluates to false.
   4. For loop
      1. for (int i = o; i < 10; i++)
      2. Syntactically unattractive, but for loops are used to repeat the body of a loop a specified number of times, in this example 10.
      3. The process undertaken in a for loop is:
         1. The counter variable(s) (here,i) is set.
         2. The Boolean expression is checked.
            1. If it evaluates to true, the body of the loop executes.
            2. If it evaluates to false, the body of the loop does not execute.
         3. The counter variable is incremented, and then the Boolean expression is checked again, etc.
    5. for (start; exp; increment)
       1. Syntactically unattractive, but for loops are used to repeat the body of a loop a specified number of times, in this example 10.
       2. The process undertaken in a for loop is:
          1. The statements) in start are executed
          2. The expr is checked.
             1. If it evaluates to true, the body of the loop executes.
             2. If it evaluates to false, the body of the loop does not execute.
          3. The statements) in increment are executed, and then the expr is checked again, etc.
3. while:
   1. Use when you want a loop to repeat an unknown number of times, and possibly not at all.
4. do-while:
   1. Use when you want a loop to repeat an unknown number of times, but at least once.
5. for:
   1. Use when you want a loop to repeat a discrete number of times, though you may not know the number
