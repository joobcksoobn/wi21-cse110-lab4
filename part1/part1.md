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

