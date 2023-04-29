1. The code will print `3` because the variable i is declared using the var keyword making it available even after the for loop block and at the end of the for loop, the variable i is incremented into the prices.length and the length of the prices list is 3 so it prints out 3. 
2. The code will print `150`. At the end of the for loop, the last discountedPrice that was calcualted was the discounted price of the price at index 2 (third price), so when we try to print out the value of the discountedPrice variable it still store the last calculated discounted price and it is possible because the var declaration allow the variable to be accessed outside of the for loop block.
3. The code will print `150`. at the end of the for loop, the finalPrice is updated by the discountedPrice that is calculated at that iteration which is the 150. And since the variable declaration is var, we are still able to access it in the function scope and it returns the last value it was assigned.
4. The function return a list, `[ 50, 100 , 150 ]` which are the discounted prices of each of the element in the prices list, because at every iteration of the for loop, each of the element in the prices list is multiplied by the discount rate and it is being pushed into the discounted list so at the end of the function, the discounted list has all the discounted prices.
5. The code causes an error because the variable i is declared using the let keyword so it only exist in the scope of the for loop so when we try to print the value of i after the for loop, it gives us `ReferenceError: i is not defined`.
6. The code causes an error because the discountedPrice variable is declared using the let keyword inside the for loop so when we try to print the variable outside of the for loop, the variable doesn't exist anymore because it is only available in the scope of the for loop block.
7. The code will print 150 at line 14 because the finalPrice variable is defined inside the function discountPrices() using the let keyword so when we try to access the finalPrice variable, the variable exist in the function scope. the value that is printed is 150 becuause at the end of the for loop, the last iteration calculated the finalPrice of the element 300 so 300 * 0.5 = 150.
8. The function returns the list [ 50, 100, 150] because it successfully calculated each of the discounted prices inside the prices list and push it to the discounted list. The given prices list is [100, 200, 300] and the discount rate is 0.5 so by the end of the function, each of the prices is discounted by 50% and the list of the discounted prices is returned.
9. The code causes an error because the variable i is defined using the let keyword inside the for loop scope so when we try to print i outside or after the for loop ends, the variable i is not defined anymore.
10. line 12 print `3` because length is assigned a value of the length of the prices list which has 3 elements so when length is printed, 3 is being outputted. It is still in the function scope so it is accessible by the console.log() function.
11. The function returns the list [ 50, 100, 150 ] because the discount rate is 0.5 and the input prices is [100, 200, 300] so at each iteration of the for loop, each of the discountedPrice is being calculated and pushed into the discounted list which is returned at the end.
12. 

a. student.name

b. student['Grad Year']

c. student.greeting()

d. student['Favorite Teacher'].name

e. student.courseLoad[0]

13. 

a. the output is the string `32` because when a string is added with an integer, the integer is converted into a string and then it is concatenated with the string.

b. The output is integer 1 because the string '3' is converted into an integer then an arithmetic subtraction is performed with the integer 2.

c. The output is the integer 3 because null is converted into 0 in the number type so 3 + 0 = 3

d. The output is the string `3null` because the null is converted into a string "null" and then concatenated with the string '3'.

e. The output is the integer 4 because true is converted into the integer 1 in the number type and 1 + 3 = 4.

f. The output is the integer 0 because when false is converted into a number type it becomes a 0 and null is also converted into 0 in the number type so 0 + 0 = 0.

g. The output is the string `3undefined` because when undefined is added with a string, it is first converted into a string 'undefined' and then concatenated with the string '3'

h. The output is `NaN` because the string '3' is converted into a number type and the undefined is converted into a NaN. And when the integer 3 is subtracted with a NaN, it produces a NaN.

14. 

a. The output is true because the string '2' is converted into the integer 2 so 2 > 1 is true.

b. The output is false because the comparison is done character-by-character from left to right so when the first character is being compared the unicode value is 50 for the string 2 and the unicode value is 49 for the string 1 so the string '2' is bigger than the string '1' which outputs false for the expression.

c. The output is true because the string '2' is converted into the integer 2 so 2 == 2 which produce true.

d. The output is false because === is a strict equality so when the operands are of different types, the result is false and no type conversion is being done.

e. The output is false because when true is converted into a number it is converted into 1 so 1==2 produce a false.

f. The output is true because Boolean(2) returns true because the number 2 is a non-zero number so true === true produce a true result.

15. The `===` operator is a strict equality which checks the equality without type conversion while the `==` operator performs a comparison that involves converting the type of the operands if it is necessary to make them the same type. So when the type of the operands are different the operator `===` will give a false result directly.

17. The result will be the list [ 2, 4, 6 ]. First the doSomething(num) function is passed as a argument into the function modifyArray so it is stored in the callback variable. Then a newArr list is created to store all the result. At each iteration of the for loop, each element of the array list is input as the argument into the callback function which is the doSomething function. So at each iteration, the doSomething function returns the value of the input times 2 and it is pushed into the newArr. At the end of the for loop, the newArr is returned and it has each of the element of the array list but doubled.

19. the output is `1 4 3 2`. because the 1 and 4 is executed directly and the 3 has a 0 ms delay and the 2 has the 1000 ms delay.

