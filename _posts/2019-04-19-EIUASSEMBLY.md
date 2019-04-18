---
layout: post
title:  EIUASSEMBLY - Assembly line
categories: ['greedy', 'binary-search']
code: EIUASSEMBLY
src: EIUASSEMBLY.cpp
---

### **Statement**

The Alternate Control Machine (ACM) Factory has a large assembly line to make
a type of product. The assembly has N robots (R<sub>1</sub>,
R<sub>2</sub>...R<sub>N</sub>) working sequentially. That means a
semi-finished product moves from robot R<sub>1</sub>, to
R<sub>2</sub>, then to R<sub>3</sub>... to R<sub>N</sub>. Each
robot adds a component to the product. Each robot can complete its own job in
P<sub>i</sub> products per one hour.

The company has a budget of M VNĐ to improve productivity for the entire
assembly. As a product director, you know that robot R<sub>i</sub> needs
to invest M<sub>i</sub> VNĐ to contribute to the production of one more
product per hour. You have to optimize the amount of money to invest to each
robot to produce maximum number of products per hour.

### Input

The first line of input contains one integer T (1≤T≤10) - the number of test
cases.

Then T test cases are given as follows:

• The first line of each test case contains an integer N (1≤n≤105) and an
integer M (0≤M≤1012) – the number of robots and the budget

• Line i-th of the next N lines contains two integers Pi (1≤P≤109) and Mi
(1≤Mi≤109) – information of the robot i-th

Then T test cases are given as follows:

  * The first line of each test case contains an integer N (1≤n≤10<sup>5</sup>) and an integer M (0≤M≤10<sup>12</sup>) – the number of robots and the budget
  * Line i-th of the next N lines contains two integers P<sub>i </sub>(1≤P<sub>i</sub>≤10<sup>9</sup>) and M<sub>i</sub> (1≤M<sub>i</sub>≤10<sup>9</sup>) – information of the robot i-th

### Output

For each test case, output in one line the maximum number of products the
assembly can make after investing at most M VNĐ.

### Example

    
    
    Input:
    1
    3 7
    1 2
    2 3
    3 1
    Output:
    3



#### **Solution**



