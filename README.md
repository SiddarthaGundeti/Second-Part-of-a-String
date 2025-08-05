# Second-Part-of-a-String

Write a program that reads a string and prints the second part of the string that has digits.

The given string contains 2 parts:
* The first part contains only two characters.
* The second part contains only digits.

Example: OF63, ab395

Input: OF63

Output: 63

Approach
To solve this problem, we will follow these steps:
1. Read the input string.
2. Extract the second part of the string that contains digits.
3. Convert the second part to an integer.
4. Print the result.

Step-by-Step Explanation

Step 1: Read the input string

First, we need to read the input string from the user. We can use the input() function to read the input and store it in a variable called string.
 
Step 2: Extract the second part of the string

Now, we know that the first part of the string contains only two characters. So, the second part starts from the third character. We can use slicing to extract the second part of the string.
 
Step 3: Convert the second part to an integer

The second part of the string contains digits. We need to convert it to an integer. We can use the int() function to do this.
 
Step 4: Print the result

Finally, we can print the result, which is the second part of the string as an integer.
