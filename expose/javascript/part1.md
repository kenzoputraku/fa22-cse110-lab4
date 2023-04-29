1. `values added:  20`
2. `final result:  20`
3. `values added:  20`
4. The code returns an error because the variable result is declared using the let operator which makes it only available inside the if function and since the console.log() statement on line 13 is out of the if statement, it can't access the result variable giving an error.
5. The code returns an error because the variable result is declared with a const keyword so we can't assign it a new value so when we try to assign the result into the sum of num1 and num2, it gives us a TypeError: Assignment to constant variable.
6. The code returns an error due to line number 9 so line 13 doesn't print as well. But if there was no previous error, the code will return an error because the const variable is only in the if scope so when we try to access it outside of the if block, it cannot find the variable result.

