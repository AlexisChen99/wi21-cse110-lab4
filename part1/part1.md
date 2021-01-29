q1: the console would print i, which should be the prices.length - 1. Since we declared i using var and var has no block scope, the varible i would still exist even after the for loop

q2: the console would print discountedPrice calculated when i = prices.legnth - 1. We could print it without an error because we declared it via var, which makes it visible through blocks. 

q3: the console would still print out finalPrice calculated when i = prices.length - 1 because finalPrice was previousy declared before the for loop via 'var', which makes finalPrice exist within the function. 

q4: the function would return the 50% discount of each prices passed into the function. More specifically, it returns 50, 100, 150. In the console, it would only print the length of prices and the discounted price for the last element in the price array. 

q5: it would cause an error since i is declared only in the block. It doesn't exist outside the for loop.

q6: it would also cause an error since discountedPrice was only declared inside the block via for loop. It doesn't exist outside the block.

q7: It wouldn't caused an error since finalPrice was declared within the same scope where it's passed into console.log(). 

q8: Regardless of all error, the function would still return the same answers as question 4, 50 100 150. The errors occur outside of the for loop, which doesn't affect discounted.

q9:it would still show an error since i doesn't exist outside of for loop.

q10: it would show an error since const is also block-scope. discountedPrice doesn't exist outside of the for loop.

q11: it would print out the finalPrice. the varible finalPrice was declared as a const and the code attempts to change it inside the for loop, which would cause an error. 

q12: regardless of all error, the function should return 0 0 0 since finalPrice was declared as const 0 and it wouldn't change within for loop. 

q13: 
a. student.name;
b. student["Grad Year"];
c. student.greeting();
d. student["Favorite Teacher"].name;
e. student.courseLoad[0]

q14:
a. 32. concatenation of strings
b. 1. it turns into both varibles into number
c. 3. since 3 is not a string, it turn null into 0 and do math arithmetic
d. 3null. since 3 is a string, it does string concatenation.
e. 4. since 3 is a number, it turns tru into 1 and do math arithmetic.
f. 0. since either of the two is a string, it does math arithmetic
g. 3undefined. Since 3 is a string, it does string concatenation
h. Nan. Since it has a minus sign, it turns the operation into math arithmetic. Since undefined becomes NaN, the result would be Nan. 

q15:
a. true. When comparing values of different types, it converts the value to numbers. Since we are comparing 2 > 1, which is true
b. false. Since both sides are string, it uses a diction ary order to compare the two. It first compare the first index of both, which is '2' and '1'. Since '2' is greater than '1', '2' is greater than '12'. 
c. true. Since both values have different types, it converts both values into number and compare them. 
d. false. Since both values have different types, it returns false.
e. false. It converts both values into numbers. true would return into 1, which is not equal to 2.
f. true. Since this comparison is a strick equality check. Both values are the same type and both are true. Boolean(2) returns true since 2 is not 0. 

q16: === works like ==. However, === would first check the types of both inputs. If the two inputs have different types, === would return false, whereas == would convert inputs' types. 

q17: How are you? At first, 2 == true would return false since 2 doesn't equal to 1. Then in else if (2), it would convert 2 into true. Thus, the code would enter the else if and return How are you?

q18: in part1-question18.js

q19: The result would be [6, 8, 10]. When we pass in the array [1,2,3] it enters a for loop, which runs from index 0 to 2. Inside the for loop, it passes 1 into the callback function doSomething with another callback function time 2. When it first enters the callback function, it increments 1 by 2. Then call the second callback function, which takes (1+2) and time it by 2, which results in 6. Then the second callback function returns it to the first function modifyArray, which pushs the result to the new array. Then, it continues the process, (2 + 2) * 2 and (3+2) *2. At the end, modifyArray returns the new array.

q20: in part1-question20.js

q21: 1 4 3 2. It first prints out 1 4 and 3. Then one minute later, it prints out 2. 