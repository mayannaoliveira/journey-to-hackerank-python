## Loops

Task
The provided code stub reads an integer, $n$, from STDIN. For all non-negative integers , print $i<n,printi^2$.

Example

$n=3$

The list of non-negative integers that are less than  is . Print the square of each number on a separate line.

```
0
1
4
```

Input Format

The first and only line contains the integer, $n$.

Constraints
$1<=n<=20$

Output Format

Print $n$ lines, one corresponding to each $i$.

Sample Input 0

`5`

Sample Output 0
```
0
1
4
9
16
```

Solving

```python
if __name__ == '__main__':
    n = int(input())
for i in range(n):
    print(i ** 2)
```

Input (stdin)
```
5
```
Your Output (stdout)
```
0
1
4
9
16
```
Expected Output
```
0
1
4
9
16
```

:snake: Please check the code in [PythonAnywhere](https://www.pythonanywhere.com/user/mayannaoliveira/shares/1a3e4bd12ef746a982b620c82c64bb9b/).

:rocket: Follow me in [HackerRank](https://www.hackerrank.com/profile/mayannait). 

:computer: _Click here to back to [README](/README.md)._
