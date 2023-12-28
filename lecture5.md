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
6. if (boolean expression 1)

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
7. int x = GetInt();
   
   switch (x)

   {

   case 1:
   
      printf("One! \n");
   
      break;
   
   case 2:
   
      printf("Two! \n") ;
   
      break;
   
   case 3:
   
      printf ("Three! \n"); break; default:
   
      break;
   
   case 4:
   
      printf("Sorry! \n");
   
      break;
   
   default:
   
      printf("Sorry\n");
   
   }

   1. C's switch() statement is a conditional statement that permits enumeration of discrete cases, instead of relying on Boolean expressions.
   2. It's important to break; between each case, or you will "fall through" each case (unless that is desired behaviour).
8.
   1. int x;

   if (exprssion)

   {

     x = 5;

   }

   else

   {

     x = 6;

   }
   
   2. int x = (expression) ? 5 : 6;
      1. These two snippets of codes act identically.
      2. The ternaray operator (?:)is mostly a cute trick, but is useful for writing trivally shot conditionally branches. Be familiar with it, but know that you won't need to write it if you don't want to.




   

   

   
   
