1) This will print out the number that is equal to prices.length, because i is declared as a var, which means it is global scope, so it can always be printed, regardless of what function it is in.
2) This prints out the last value in prices, multiplied by 1 - discount, and it print because it is declared as a var, which does not have an issue with redeclaration, and it will be printed due to its global scope.
3) This will print out the rounded value of (discountedPrice * 100) / 100, which works because it was declared as a var, so the scope is global, and it will work.
4) The function will return the array of [50, 100, 150]. This is because the discount is 0.5, or half of the original amount, and the for loop will run through the amount of prices there are, or for all three values. The array discounted will hold the values of the discounted original prices, which are half of their value.
5) Line 11 will cause an error, because it will not be able to find a variable with the name of "i". This is because the variable only exists within the scope of the for loop, and line 11 remains outside the loop, so the variable does not exist in that scope.
6) Line 12 will cause an error, because the variable was declared within the scope of the for loop, and only exists within that frame. Therefore, because line 12 is outside the loop, the variable it is referencing does not exist in that scope, so the program will crash.
7) Line 13 will print out the finalPrice contents of the last loop. This is because the variable finalPrice was declared on the same scope as line 13, and it will be the contents of the last loop, because that will be the last time the variable was changed during the loop.
8) The function will return the array of [50, 100, 150]. This is because the function will run normally, so each position in the discounted array will correspond to half of each value in their respective position in the prices array. This is because of the discount value, being 0.5
9) Line 11 will cause an error, because the variable i is declared only within the scope of the for loop. Because of this, it is unable to find the variable on the proper scope, so the program will crash.
10) This will cause an error, because const behaves the same was as the keyword "let", meaning that it can only exist within the scope of that block of code. This means that the variable of discountedPrice does not exist at line 12, meaning the program will crash.
11) This will print out the value of 0. This is because the finalPrice variable was assigned a value of 0 at line 3, and const variables cannot be reassigned a value after they have been assigned their first value. Therefore, any new assignment in the for loop is disregarded, and the finalPrice variable will always remain as 0. 
12) This function will return the array of [0, 0, 0]. Because finalPrice is being pushed into the array, and finalPrice is a const variable, the contents of finalPrice will never change, and will always be 0. Because the variable discounted is a const, it will always remain an array, but the array itself can be mutated through the push commands, therefore the array will grow due to the function.
13) student.name;
    
    student['Grad Year'];
    
    student.greeting();
    
    student['Favorite Teacher'].name;
    
    student.courseLoad[0];

14a) The output is a string that is equal to '32'. This is because the first part of the equation, the '3' is a string, so it assumes that the equation is a string concatenation.

14b) The output is equal to 1. This is because there is no available equal term for strings for the subtraction "-". Therefore, it cannot do anything for a string, so it converts the 3 into a number. 

14c) The output is 3. This is because the null value, when compared with a number, becomes equivalent to 0. 

14d) The output is '3null'. This is because the null value becomes a string with the equivalent value, so it becomes 'null'.

14e) The output is 4. This is because when true is compared with a numeric value, it becomes equivalent to 1, so it adds the two values together.

14f) The output is 0. This is because, there is no way to add these two values together unless they are being compared as numeric values. Therefore, both of these values are equal to 0, so it equals to 0 + 0.

14g) The output is '3undefined'. This is because it is still referred to as a string, and the undefined is being treated as a string.

14h) The output is NaN, which is defined as not a number, and this is because there is no subtraction for strings, so they are being treated as numeric values. Therefore, undefined is determined as NaN, so that will be the output.

15a) The output is true. This is because comparisons of different types are treated as a comparisons of numbers. Therefore, it compares if 2 is greater than 1, which is true.

15b) The output is false. This is because they are being compared to as strings, because they share the same type. Strings are compared character by character, so the comparison boils down to if '2' < '1', which is false, so the output is false. 

15c) The output is true. This is because they are different types, so it is comparing it as two numeric values. 2 is equal to 2, so the output is true.

15d) The output is false. This is because the triple = checks the equality without type conversion. Because the two values are different types, it is automatically false.

15e) The output is false. They are different types, so it compares them as numbers, and true is equal to 1, so it is false.

15f) The output is true. This is because the boolean function converts the value into a boolean value, and because 2 converts into true, the output is true.

16) The difference between the == and === operators is whether there is type conversion. == will convert the types of the values if they are different, thus checking if they are equal after a possible conversion. However, === checks if they are equal without converting the type of the values. Therefore, if the two values differ in type, the === will automatically output to false.
17) The string of 'How are you?' will be printed. This is because the first statement of 2 == true will output to false, because true is converted to 1, so the overall statement will be false. Then it will move onto the 2nd conditional, where 2 will be converted to a boolean, so it will be true, which means that the 2nd line will be printed, and the conditional will be finished. 
18) (code)
19) The result will be an array that contains [6, 8, 10]. This is because the newArr will push a value at i. The push will first callback the first function from the modifyArray arguments, which is doSomething. doSomething will return a value, where it calls the function function, with the initial number + 2. From there, the number is multiplied by 2, and then it will be pushed to the array.
20) (code)
21) The output of this code will be 1 4 3 2. This is because of the setTimeout function, which will delay the code for printing out the 2. Therefore, the function will delay the 2, allowing the 3 to print out first. However, because there is no timeout on the 4, this will print out before the 3, and will be able to print out after the 1.