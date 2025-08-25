# Call by Reference Using Pointers in C++

---

### Aim
To study and implement the concept of call by reference using pointers in C++ for direct manipulation of variable values.

---

### Theory
- Call by reference allows functions to modify the actual values of arguments by passing their memory addresses.
- In C++, this is achieved using pointers (`*`) which store the address of variables.
- When a pointer is passed to a function, any changes made through dereferencing (`*ptr`) affect the original variable.
- This method is efficient for large data structures and enables in-place updates without returning values.
- It is commonly used in operations like swapping, sorting, and dynamic memory manipulation.

---

### Tool Used
- C++ programming language  
- Standard I/O library (`iostream`)  
- Compiler supporting C++11 or later

---

### Functions Used
- Pointer declaration and initialization  
- Address referencing using `&` operator  
- Dereferencing using `*` operator  
- Function calls with pointer parameters  
- In-place data manipulation via pointers

---

## Algorithms

---

### Algorithm: Arithmetic Operations Using Pointers

1. Start  
2. Declare two integer variables `a` and `b`  
3. Declare two integer pointers `*p1` and `*p2`  
4. Assign addresses of `a` and `b` to `p1` and `p2` respectively  
5. Perform addition, subtraction, multiplication, and division using dereferenced pointers  
6. Display the results  
7. End

---

### Algorithm: Array Reversal Using Pointer

1. Start  
2. Declare an array of fixed size  
3. Declare a pointer and assign it to the base address of the array  
4. Use two pointers: one at the start and one at the end of the array  
5. Swap elements pointed by the two pointers  
6. Increment start pointer and decrement end pointer until they meet  
7. Display the reversed array  
8. End

---

### Algorithm: Swap Two Numbers Using Pointers

1. Start  
2. Declare two integer variables `a` and `b`  
3. Input values for `a` and `b` from the user  
4. Call the function `swap()` and pass the addresses of `a` and `b`  
5. Inside the `swap()` function:  
   - Declare a temporary variable `k`  
   - Assign `k = *a`  
   - Assign `*a = *b`  
   - Assign `*b = k`  
6. Return to `main()`  
7. Display the swapped values of `a` and `b`  
8. End

---

### Conclusion
Call by reference using pointers is a foundational concept in C++ that enables direct manipulation of variables within functions. It eliminates the need for return values when multiple variables must be updated and ensures efficient memory usage by avoiding unnecessary data copying. This technique is especially valuable in performance-critical applications, recursive algorithms, and dynamic data structures. By mastering pointer-based reference passing, programmers gain precise control over program behavior, improve modularity, and build scalable, maintainable systems. Understanding this concept is essential for advancing into more complex topics such as dynamic memory allocation, pointer arithmetic, and low-level system programming.
