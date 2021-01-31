Debugging 
- Take a screenshot of breakpoints
- Take a screenshot of watch expressions list
- The bug was the type of result. Both num1 and num2 are strings. When we add the two varibles, it turned into string concatenation. Then result becamse the string concatenation of the two numbers instead of addition. 
- I fixed it by including the function Number() to convert both variables num1 and num2 to numbers. 

Network tab
1. citylots.json
2. part2.js:2
3. 11.7 mb
4. 1.78s
5. Mozilla/5.0 (Macintosh; Intel Mac OS X 11_1_0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. Inside the function fetchData(), we called fetch() to make the request 