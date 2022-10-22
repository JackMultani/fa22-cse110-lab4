1. 2 will be printed since 'i' was declared as a var in the for loop and thus and exists outside of the scope of the for loop.
2. 150 will be printed since 'discountedPrice' was declared as a var in the for loop and thus exists outside of the scope of the for loop.
3. 150 will be printed since finalPRice was declared as a var in the scope of the function 'discountPrices' and thus exists throughout the rest of the function. 
4. The function 'discountPrices' will return [50, 100, 150]. In addition, the function returns an array that contains the discounted prices of each item in 'prices' as each item in 'prices' is multiplied by (1 - discount) to obtain the discounted price and is pushed to the discounted array after being rounded.
5. There will be an error at line 12 since the variable 'i' was declared using 'let' in the for loop declaration. Therefore, 'i' is not accessible outside of the for loop and only exists in the scope of the for loop.
6. There will be an error at line 13 since the variable 'discountedPrice' was declared using 'let' in the body of the for loop. Therefore, 'discountedPrice' is not accessible outside of the for loop and only exists in the scope of the for loop.
7. 150 will be printed at line 14 since 'finalPrice' was declared using a 'let' in the body of the function. Therefore, the scope of 'finalPrice' exists within the whole function and is thus accessible throughout the function. Also, as 'finalPrice' was calculating the discounted price of the last entry in prices during the last iteration of the for loop, line 14 will ultimately print the last calculated price which is 150.
8. The function 'discountPrices' will return [50, 100, 150] as the array 'discounted' was declaring using a 'let' in the body of the function and is thus accessible throughout the whole function. In addition, the function returns an array that contains the discounted prices of each item in 'prices' as each item in 'prices' is multiplied by (1 - discount) to obtain the discounted price and is pushed to the discounted array after being rounded.
9. There will be an error at line 11 since the variable 'i' was declared using 'let' in the for loop declaration. Therefore, 'i' is not accessible outside of the for loop and only exists in the scope of the for loop.
10. At line 12, the value 3 will be printed as the variable 'length' was declared in the body of the function using the 'const' variable and is thus accessible throughout the function.
11. The function 'discountPrices' will return [50, 100, 150] as the array 'discounted' was declaring using a 'const' in the body of the function and is thus accessible throughout the whole function. In addition, a 'const' array is still able to be modified by the 'push' function. Also, the function returns an array that contains the discounted prices of each item in 'prices' as each item in 'prices' is multiplied by (1 - discount) to obtain the discounted price and is pushed to the discounted array after being rounded.
12. 
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13.  
    A. The output was '32' since integers map to their exact string representation and 2 is thus treated as a string.
    B. The output is 1 because '3' is casted to an int and the operation (3 - 2) is performed, resulting in 1.
    C. The output is 3 because null is treated as 0 and the operation (3 + 0) is performed, resulting in 3.
    D. The output is '3null' because null is casted to a string and the operation ('3' + 'null') is performed, resulting in '3null'
    E. The output is 4 because true maps to 1, resulting in the operation (1 + 3) being performed.
    F. The output is 0 because false maps to 0 and null is treated as 0, resulting in the operation (0 + 0) being performed.
    G. The output is '3undefined' because undefined is casted to a string, resulting in the operation ('3' + 'undefined') being performed.
    H. The output is NaN because a number, in this case 3, cannot be subtracted by an undefined number, resutling in NaN.
14. 
    A. The output is true because '2' is casted to an int and the comparison (2 > 1) is performed, resutling in true.
    B. The output is false because the numbers '2' and '12' are compared in numerical order. Since '2' is greater than '1', any string that contains a '2' as its first character will be greater than any string that contains a '1' as its first character. Therefore, the output is false.
    C. The output is true because '2' is casted to an int and the comparison (2 == 2) is performed, resulting in true.
    D. The output is false because the int 2 is not the same datatype as the string '2', resulting in false.
    E. The output is false because true maps to 1 and '2' is casted to an int, resulting in the operation (1 == 2) which is false.
    F. The output is true because true and Boolean(2) are of the same data types and 
15. The == operator only compares the value stored by two operands and the === operator comapres both the value stored by two operands and the data types of the two operands. 
16. 
    for(const property in statistics) {
        if(property == 'r' || (statistics[property] % 2 != 0) {
            console.log(statistics[property]);
        }
    }
17. The result will be [2, 4, 6]. First the function modifyArray() runs a for loop that iterates through the [1, 2, 3] array. Then, for each element in [1, 2, 3], the for loop calls the doSomething() function and sends each element in [1, 2, 3] as the function's parameter. The doSomething() function then mulitplies each element by 2 and returns the resulting number. Finally, the for loop pushes each resulting number from doSomething() into newArr and the function modifyArray returns newArr after the for loop is finished.
18. 
    setTimeout(function () { 
        let d = new Date();
        let time = d.toLocaleTimeString();
        console.log(time);
        }, 1000);
19. 1 3 4 2
