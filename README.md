# Counting shirts
An online shop sells T-shirts of three sizes: S(small), M(medium) and L(large).
Write a function:
```class Solution { public String solution(String s); }```
that, given a string s of length N containing letters S, M and L returns a sorted string T by T-shirt sizes from the smallest to the largest.

Examples:
- Given S = "MSSLS", the function should return "SSSML".
- Given S = "LLMS", your function should return "SMLL"
- Given S = "SMS", your function should return "SSM".

Assumptions:
- N is an integer within the range [1...200000];
- string S consists only of the characters "S","M" and/or "L".
