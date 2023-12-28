Conditional Statements.
1. Conditional expressions allow your programs to make decisions and take different forks in the road, depending on the values of variables or user input.
2. C provides a few different ways to implement conditional expressions (also known as branches) in your programs, some of which likely look familiar from Scratch.
3. if (boolean expression)
 
   {
   
   }
   1. If the boolean-expression evaluates to true, all lines of code between the curly braces will execute in order from top-to-bottom.
   2. If the boolean-expression evaluates to false, those lines of code will not execute.
4. if (boolean expression)

   {

   }
   
   else
   
   {
   
   }
   1. If the boolean-expression evaluates to true, all lines of code between the first set of curly braces will execute in order from top-to-bottom.
   2. If the boolean-expression evaluates to false, all lines of code between the second set of curly braces will execute in order from top-to-bottom.
5. if (boolean expression 1)

   {
   
                //first branch

   }
   
   else if (boolean expression 2)
   
   {

                //second branch 

   }

    else if (boolean expression 3)
   
   {
   
                //third branch 

   }

   else

   {

                //fourth branch

   }

   1. In C, it is possible to creat an if-else, if-else chain.
   2. In scratch, this required nesting blocks.
   3. As you would expect each branch is mutually exclusive.
6. 5. if (boolean expression 1)

   {
   
                //first branch

   }
   
   if (boolean expression 2)
   
   {

                //second branch 

   }

   if (boolean expression 3)
   
   {
   
                //third branch 

   }

   else

   {

                //fourth branch

   }

   1. Its is possible to create a chain of non mutually exclusive branches.
   2. In this example, only the third and fourth branches are mutually exclusive. The else binds to the nest if only.
   

   

   
   
