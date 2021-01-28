1. Line 11 will output the size of the prices array because i is a var meaning it can be accesses outside the for loop
2. Line 12 will output the discounted price of the last value in prices because discountedPrice is a var and will have scope outside the for loop.
3. Line 13 will output the final price after discount of the last item in the prices array becuase even though finalPrice is assigned within the for loop it is defined outside so its scope is greater than just the for loop
4. The function will return an array containing the values [50,100,150] because the function iterates through the prices input array and for each value it applies the discount and pushes the result into the discounted array, this array is returned producing the output of discounted values
5. Line 11 will throw an error because i is a let and therefor only defined in the scope of the for loop and not outside it.
6. Line 12 will throw an error because let discountedPrice is only defined in the scope of the for loop and is undefined when invoked outside
7. Line 13 will output the final price after discount of the last item in the prices array becuase even though finalPrice is a let and is assigned within the for loop it is defined outside so its scope is greater than just the for loop
8. The function will return [50,100,150] because it will properly iterate throgh prices and apply the discount, add the finalPrice to the discounted array, and return the array.
9. Line 11 will throw an error because i is a let and therefor only defined in the scope of the for loop and not outside it.
10. Line 12 will throw an error because const discountedPrice is only defined in the scope of the for loop and is undefined when invoked outside.
11. Line 13 will output 0 because finalPrice is defined as a const in the beginning and assigned 0 so it cannot be reassigned
12. The function will throw an error because of line 7 where it attempts to assign a new value to const finalPrice, as const variable must be assigned at decleration and cannot be reassigned
13. 
    A. alert( student.name );
    B. alert( student['Grad Year'] );
    C. student.greeting();
    D. alert( student['Favorite Teacher'].name );
    E. alert( student.courseLoad[0] );
14. 
    A. '3' + 2
        '32' because the 3 is a string so the 2 is simply appended on
    B. '3' - 2
        1 because javascript treats - different than + and will convert '3' into a number and subtracts 2
    C. 3 + null
        3 because no value is being added to the 3
    D. '3' + null
        '3null' because the 3 is a string first, null will be treated as a string and appended onto '3'
    E. true + 3
        4 because true and false are equivalent to 1 and 0 respectively, adding 3 to true equals 4
    F. false + null
        0 because both false and null are equivalent to value 0
    G. "3" + undefined
        '3undefined' because the "3" is a string first, undefined will be treated as a string and appended onto "3"
    H. "3" - undefined
        NaN because "3" is interpreted as a string which cannot be subtracted from so the program throws Not a Number
15. 
    A. '2' > 1
        true 
    B. '2' < '12'
        false
    C. 2 == '2'
        true
    D. 2 === '2'
        false
    E. true == 2
        false
    F. true === Boolean(2)
        true
16. == compares the value of two variables and returns true if they are equal, whereas === also checks if the variable types match and only returns true if type and value are equal
17. The code snippet will print 'How are you?' because the only if statement that evaluates to true because writing if(2) javascript will automatically change the type of 2 to bool, and since javascript considers true equivalent to 2 it will evauate to true. The first if statement evaluates to false because even though changing 2 to bool makes it equal to true, comparing true to an int will only evaluate to true when the int is 1.
18. part1-question18.js
19. The output will be [6,8,10] because for each element in the array it calls doSomething which adds 2 to the number, then the function inside modifyArray multiplies the result by 2.
20. part1-question20.js
21. The code will output 1 4 3 2 because the first line simply outputs 1, then the next two lines will output 2 and 3 but they both have delays so the next output is 4 on the following line. Then 3 is output before 2 because it has less delay.