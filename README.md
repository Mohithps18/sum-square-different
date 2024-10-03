# sum-square-different
The sum of the squares of the first ten natural numbers is, . The square of the sum of the first ten natural numbers is, . Hence the absolute difference between the sum of the squares of the first ten natural numbers and the square of the sum is .

Find the absolute difference between the sum of the squares of the first  natural numbers and the square of the sum.

Input Format

First line contains  that denotes the number of test cases. This is followed by  lines, each containing an integer, .

Constraints

Output Format

Print the required answer for each test case.

Sample Input 0

2
3
10
Sample Output 0

22
2640
Explanation 0

For  , 
For , 
Language
Python 3
More
12345678910111213

    

Line: 13 Col: 1

Test against custom input

----------------------------------------------------------------------------------------------
for _ in range(int(input())):
    n = int(input())

   

    sq_sum = n ** 2 * (n + 1) ** 2 // 4
    sum_sq = n * (n + 1) * (2 * n + 1) // 6

    print(sq_sum - sum_sq)


    
