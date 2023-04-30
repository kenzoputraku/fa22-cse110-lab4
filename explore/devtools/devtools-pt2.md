1. The bug is the data type of num1 and num2 are both string data type so when we try to add num1 and num2, it does a string concatenationg instead of arithmetic addition.
2. When we try to add num1 and num2, we can convert the data type of num1 and num2 into number first before adding them. So the fix would be
`let result = Number(num1) + Number(num2);`