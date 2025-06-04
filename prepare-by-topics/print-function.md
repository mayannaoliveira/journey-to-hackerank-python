## Print Function

The included code stub will read an integer, $n$, from STDIN.
Without using any string methods, try to print the following:

$123...n$

Note that "" represents the consecutive values in between.

Example
$n=5$
Print the string `12345`.

Input Format

The first line contains an integer .

Constraints

$1<=n<=150$

Output Format

Print the list of integers from  through  as a string, without spaces.

Sample Input 0

`3`

Sample Output 0

`123`

```python
if __name__ == '__main__':
    n = int(input())
```

Solving

```python
 if __name__ == '__main__':
    n = int(input())
    result = ""
    for i in range(1, n + 1):
        result += str(i)
    print(result)
```

:snake: Please check the code in [PythonAnywhere](https://www.pythonanywhere.com/user/mayannaoliveira/shares/e708905cd660496481e5068f65f77401/).

:rocket: Follow me in [HackerRank](https://www.hackerrank.com/profile/mayannait). 

:computer: _Click here to back to [README](/README.md)._