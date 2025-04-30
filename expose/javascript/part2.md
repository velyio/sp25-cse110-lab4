# Part 2 Question Answers

1. Line 12 will print 3, because at the last iteration of the loop i is incremented to 3 and the loop ends. This can happen because var variables still exist when the loop ends.
2. Line 13 will print 150. This is because discountedPrice is defined with var, so it still exists outside the scope of the loop. So discountedPrice will be set to the value of the last iteration where i=2 and discountedPrice = 300 * 0.5
3. Line 14 will also print 150. This is because finalPrice will be set to the value of discountedPrice on the last iteration of the loop. 
4. This function will not print anything because there are no print statements, but it does not cause an error, so the function will return the values of discounted as [50, 100, 150].
5. This will cause an error because i is a let, therefore it cannot be accessed outside the for loop block. So i will be undefined when you call console.log(i).
6. This will cause an error because discountedPrice is defined inside the for loop block. Because it is a let, it cannot be accessed outside so it is not defined when calling console.log(discountedPrice)
7. Line 14 returns 150 because finalPrice is defined in the same function block that its called from, so the variable is correctly defined in the scope of the function.
8. The function does not print anything but it will return discounted with the values [50, 100, 150] after running the functions.
9. The code causes an error because i is not defined outside the scope of the for loop.
10. Line 12 prints 3 because length is never reaassigned, so it doesn't cause an error.
11. This code does not print anything but it will return discounted with the value [50, 100, 150] because all variables are correctly assigned for the for loop to calculate the discounted prices correctly.
12. Question 12:
    -  (a) student.name
    -  (b) student['Grad Year']
    -  (c) student.greeting()
    -  (d) student['Favorite Teacher'].name
    -  (e) student.courseload[0]
13. Question 13:
    - (a) '32'
    - (b) 1
    - (c) 3
    - (d) '3null'
    - (e) 4
    - (f) 0
    - (g) '3undefined'
    - (h) NaN
14. Question 14:
    - (a) true
    - (b) false
    - (c) true
    - (d) false
    - (e) false
    - (f) true
15. the == operator compares values of the variables, even if they have to be converted to another type; and === operator compares the type and value of the variables, since it is a strict equality.
16. part2-question16.js
17. The result will be [2,4,6]. This is because modifyArray loops through and calls back iteratively. When the input is [1,2,3] the callback function returns num*2, so callback(1) returns 2, then callback(2) returns 4 and callback(3) returns 6. So newArr will store [2,4,6].
18. part2-question18.js
19. Output:
1  
4  
3  
2  
