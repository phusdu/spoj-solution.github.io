---
layout: post
title:  WOWSUBSTR - Counting WOW-Substrings
categories: ['uncategorized']
code: WOWSUBSTR
src: WOWSUBSTR.cpp
---

### **Statement**


    You are given a string. You have to count the total lengths of all WOW substrings.  
     WOW substrings are defined as a contiguous substring of a string  
     where there is no any character occurring more than one times.  
    That means, all the characters of substring are unique.  
    As answer could be very large, so print it modulo 100007. (NOTE THAT: 100007 is not a prime number!!)

###  Input

Input starts with an integer TC (<=50), denoting the number of test
cases.Each case starts with a string S.  
All characters in string will consists of only lowercase letters of English
alphabets.

### Output

For each case, print the case number and total lengths of all WOW substrings
of given string modulo 100007.

Constraints:

1 <=TC<=50.

1 <=|S|<=500000. (Length of string)

Example  
 Input:  
 2  
 aaa  
 ab  
 Output:  
 Case 1: 3  
 Case 2: 4



#### **Solution**



