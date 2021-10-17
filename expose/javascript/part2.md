# Part 2

### 1. Line 12 will print out 3.
### 2. Line 13 will print out 150.
### 3. Line 14 will print out 150.
### 4. The function returns an array, [50,100,150], because discounted is declared as var, and it is a global variable.
### 5. Line 12 will return an error because let is not visible outside of for loop.
### 6. Line 13 will return an error because discountedPrice is declared inside the for loop and it is a let varible, it could not be accessed outside of the block.
### 7. Line 14 will print out 150.
### 8. The function will return an array, [50,100,150], because discounted will be contained in the return value. 
### 9. Line 11 will return an error because i is a let varible and it is not accessable outside of for loop. 
### 10. Line 12 will return 3 because it is a const and it has not been reassigned after it is defined. 
### 11. This would return an array, [50,100,150] because const defines a constant reference to an array, the element of the array could be changed.
### 12.  
    A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];
### 13. 
    A. '32', because 2 maps to '2'. 
    B. 1, because '3' maps to integer, 3.
    C. 3, because null maps to 0.
    D. '3null', because null maps to the string representation of it, 'null'.
    E. '4', because true maps to 1.
    F. 0, because false and null both map to 0. 
    G. '3undefined', becasue undefined maps to the string representation of it, 'underfined'.
    H. NaN, because underfined maps to NaN and '3' maps to 3.
### 14. 
    A. true, because '3' maps to 3. 
    B. false, because they are both string, and for string comparision, the first character of the 2 string is compared. 
    C. true, '2' maps to 2.
    D. false, === checks the equality without type conversion, and 2 is an integer while '2' is a string. 
    E. false, true maps to 1. 
    F. true, because Boolean(2) maps to true. 
### 15. Equals, '==', means the equality test, and it checks the equality with type conversion while the strict euqality operator '===' checks the equality without type conversion. 

### 16. See **part2-question16.js**
### 17. The function returns an array, [2,4,6]. The function loop throught the input array and for each element in the array, it calls the function doSomething and passes the element into doSomething function. All the element in the array is multiplied by 2 then pushed into the newArr which is returned at the end of the function.

### 18. see **part2-question18.js**.
### 19. The code would output 1, 4, 3, 2. 