 Varenyam Singh
 
24070123126

Aim: To study and implement C++ decision making statements

Theory:Bitwise shift operators in C++ are powerful tools for manipulating data at the binary level. They allow you to shift the bits of an integer either to the left or right, which is often used for efficient arithmetic operations and low-level programming.

🔧 Bitwise Shift Operators in C++

1. Left Shift (<<)

- Syntax: a << b

- Effect: Shifts the bits of a to the left by b positions.

- Equivalent to: Multiplying a by 2^b

2. Right Shift (>>)

- Syntax: a >> b

- Effect: Shifts the bits of a to the right by b positions.

- Equivalent to: Dividing a by 2^b

-  Algorithm: Set a Specific Bit in an Integer

- Start

- Input the integer a (original number)

- Input the bit position set to be modified

- Calculate var1 = 1 << set → creates a mask with 1 at the desired position

- Compute final = a | var1 → sets the bit using bitwise OR

- Display final (modified number with the bit set)

- End

-  Algorithm: Reset (Clear) a Specific Bit in an Integer

- Start

- Input the integer a (original number)

- Input the bit position reset to be cleared

- Calculate var1 = 1 << reset → creates a mask with 1 at the desired position

- Compute final = a & ~(var1) → resets the bit using bitwise AND and NOT

- Display final (modified number with the bit cleared)

- End

 Conclusion: Bitwise Shift Operators in C++
 
   Bitwise shift operators—<< for left shift and >> for right shift—are essential tools for optimizing performance and performing arithmetic operations more efficiently in C++. By directly      
   manipulating binary data, these operators enable low-level control of values, which is particularly useful in areas like embedded systems, graphics processing, and cryptographic              
   algorithms.
   
   Understanding how these shifts affect the binary representation of numbers improves your ability to write fast, memory-efficient code. Mastery of bitwise shifting also lays the foundation    
   for advanced topics like bit masking, flags, and protocol handling.



 





