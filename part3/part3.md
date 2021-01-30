The bug is on line 9 of part1.js, where result is assigned the value of num1 + num2. The bug is that the lets num1 and num2 are being interpreted as strings so num2 is simply appended onto num1 rather than their values being added. 
To fix this one can simply type cast num1 and num2 to be numbers so javascript will know to treat them properly.

1. citylots.json
2. part2.js
3. 3.1 kb
4. 162.95 ms
5. Chrome/87.0.4280.141
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData in part2.js