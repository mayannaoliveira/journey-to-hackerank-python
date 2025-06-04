## Arithmetic Operators

**Task**  
The provided code stub reads two integers from STDIN,  and . Add code to print three lines where:
1. The first line contains the sum of the two numbers.
2. The second line contains the difference of the two numbers (first - second).
 
3. The third line contains the product of the two numbers.

**Example: **  
$a=3$
$b=5$
Print the following:

$8$
$-2$
$15$

**Input Format:**

The first line contains the first integer, $a$.  
The second line contains the second integer, $b$.

**Constraints: **
$$
1 <= a <= 10^10
$$
$$
1 <= b <= 10^10
$$
  

**Output Format: **
Print the three lines as explained above.

**Sample Input 0: **
`3`
`2`

**Sample Output 0**
`5`
`1`
`6`

**Explanation 0: **
$3+2 ==> 5$
$3-2 ==> 1$
$3*2 ==> 6$

:snake: **Solve: **

```python
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    
    print(a + b)
    print(a - b)
    print(a * b)
```

<details close>
  <summary> <b> Output: </b> </summary>
<p align="left">

**Input (stdin)**
```python
3
2
```
**Your Output (stdout)**
```python
5
1
6
```
**Expected Output**
```python
5
1
6
```
</p>
</details>

:snake: Please check the code in [PythonAnywhere](https://www.pythonanywhere.com).

:rocket: Follow me in [HackerRank](https://www.hackerrank.com/profile/mayannait). 

:computer: _Click here to back to [README](/README.md)._
