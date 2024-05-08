# Impledge-Coding-Question-Solution
Solution to Impledge's coding question. Implements "Search the longest compounded word" as ESSENTIAL part.

Step-by-Step Approach:

1. Input Gathering:
The program prompts the user to input the number of strings (n).
It then reads n strings from the standard input.

2.Sorting:
The strings are sorted based on their lengths using the std::sort function.

3.Hashing:
A hash map (unordered_map) is used to store each string and its frequency.

4.Processing:
Starting from the longest string, the program checks if the reverse of any suffix of the string exists in the hash map.
If it doesn't exist, it is considered a compound word. The program prints it as one of the longest compound words and exits when it finds the second longest.

5.Output:
The program prints the two longest compound words found in the input strings.

Running the Program:

1.Compilation:
Compile the program using a C++ compiler.

Input:
Provide the number of strings (n) and the strings themselves as input.
Output:
The program will display the two longest compound words found in the input.

Input:
5
cat
cats
catsdogcats
catxdogcatsrat
dog

Output:
Longest Compound Word: catsdogcats
Second Longest Compound Word: catxdogcatsrat
