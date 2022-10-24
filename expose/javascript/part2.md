# Part 2
1. The console will log ``2``, which is one less than the number of prices in prices[]. The program still sees this variable because it was declared within the same function using the ``var`` keyword.
2. The console will log ``150``, which is the most recent value ``discountedPrice`` is set to. The program still sees this variable because it was declared within the same function using the ``var`` keyword.
3. The console will log ``150``, which is the most recent value ``finalPrice`` is set to. The program still sees this variable because it was declared within the same function using the ``var`` keyword.
4. This function returns an array with the following contents: ``[50, 100, 150]``
5. The console will log undefined, because ``i`` was declared using the ``let`` keyword, and has fallen out of scope since the for loop has ended. 
6. There will be an error, because ``discountedPrice`` was declared using the ``let`` keyword, and has fallen out of scope since the for loop has ended. 
7. The console will log ``50``, which is the most recent value ``finalPrice`` is set to. The program still sees this variable because even though it was declared with the ``let`` keyword, it has been declared in the same block as the log function is called. 
8. This function returns  an array with the following contents: ``[50, 100, 150]``
9. The console will log undefined, because ``i`` was declared using the ``let`` keyword, and has fallen out of scope since the for loop has ended. 
10. The console will log 3, which is the length of prices
11. This function returns  an array with the following contents: ``[50, 100, 150]``. - This does not create an error because the declaration of the variable happens in a separate scope each time, as each iteration of the for loop is it's own scope. 
12. 
    1. ``student.name``
    2. ``student["Grad Year"]``
    3. ``student.greeting();``
    4. ``student["Favorite Teacher"].name``
    5. ``student.courseload[0]``
13. Arithmetic
    1. ``'32'`` because 2 is being converted to a string and being appended to ``'3'``.
    2. ``1`` because ``'3'`` is being converted to an int, and ``2`` is being subtracted from it. 
    3. ``3`` because ``null`` is converted to ``0``, then added to ``3``.
    4. ``3null`` because ``null`` is being converted to a string and appended to ``'3'``.
    5. ``4`` because ``true`` is being converted to the integer ``1``, and then added to ``3``
    6. ``0`` because both ``false`` and ``null`` are both converted to ``0`` and then added to each other. 
    7. ``3undefined`` because ``undefined`` is being converted to a string and appended to ``'3'``. 
    8. ``NaN`` because there is no way to convert ``undefined`` to a number, and there is no ``undefined`` in ``'3'`` which is being converted to an int, so the operation cannot be completed. 
14. Comparison
    1.  ``true`` because ``'2'`` is being converted to an integer and tested to see if it is greater than ``1``, which it is. 
    2.  ``false`` because ``'2'`` and ``'12'`` are both strings, and alphabetically ``'12'`` is 'less' than ``'2'``. 
    3.  ``true`` because ``'2'`` is converted to an integer and compared with ``2``, which it is equal to. 
    4.  ``false`` because ``true`` is converted to ``1``, and then compared to ``2``, which it isn't equal to. 
    5.  ``true`` because ``Boolean(2)`` generates ``true`` if it is supplied with a value that isn't 0, or an empty value, sot the expression evaulates to ``true===true`` which is true.
15. ``==`` will attempt to compare values of differing types, while ``===`` considers operands with different types to be different. 
16. 
```javascript
Object.getOwnPropertyNames(statistics).forEach((val, idx, array) => {
    if (`${val}`[0] == 'r' || `${statistics[val]}` % 2)){
        console.log(`${obj[val]}`);
    }
});
```  
17. The result will be an array with the contents ``[2, 4, 6]`` because ``modifyArray`` takes the contents of the input ``array``, and adds the results of the callback function ``doSomething`` in the new array which it returns. ``doSomething`` simply returns the double of whatever number is input, so the new array will contain the double of the contents of the original array, which held ``[1, 2, 3]``. 
18. See part2-question18.js
19.  1  
4  
3  
2  