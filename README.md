# 42-getnextline
Reading from descriptor line by line

Grade: 125/100

This is the code as it was upon closing the project and correcting it. There are a few minor issues that I have decided to leave as-is.

# Unsupported features:  
-Does not handle "binary" inputs (assuming \0 instead of storing byte counts)

# Bonus:  
-Handles multiple descriptors at once  
-A single static variable, used to store a self cleaning linked list

# Improvements I would like to make:  
-String copy and reallocation is very naive and inefficient, it can be significantly improved
