# Bug reports for exercise1.py

Line: 3  
Problem: is_even returns True for odd numbers because it checks if n % 2 == 1, but the docstring states it should return True for even numbers.  
Example: is_even(2) returns False, expected True; is_even(3) returns True, expected False.  
Fix: return n % 2 == 0  

bug 2

Line: 8  
Problem: rectangle_area returns the sum of width and height, but the docstring describes it as the area of a rectangle, which should be the product of width and height.  
Example: rectangle_area(4, 5) returns 9, expected 20.  
Fix: return width * height  

bug 3

Line: 13  
Problem: double adds 2 to the input number, but the docstring states it should return "twice the number n", which means multiplication by 2.  
Example: double(4) returns 6, expected 8.  
Fix: return n * 2
