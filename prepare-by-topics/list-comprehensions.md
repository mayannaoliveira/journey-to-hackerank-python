## List Comprehensions

Let's learn about list comprehensions! You are given three integers `x`, `y` and `z` representing the dimensions of a cuboid along with an integer `n`. Print a list of all possible coordinates given by `(i,j,k)` on a 3D grid where the sum of `i+j+k` is not equal to `n`. Here, . Please use list comprehensions rather than multiple loops, as a learning exercise.

Example
```
x=1
y=1
x=2
n=3
```

All permutations of `i,j,k` are:
`[[0,0,0],[0,0,1],[0,0,2],[0,1,0],[0,1,1],[0,1,2],[1,0,0],,[1,0,1][1,0,2],[1,1,2]]`

Print an array of the elements that do not sum to `n=3`.
`[[0,0,0],[0,0,1],[0,0,2],[0,1,0],[0,1,1],[1,0,0],[1,1,0],[1,1,2]]`

Input Format

Four integers `x`, `y` and `z`, each on a separate line.

Constraints

Print the list in lexicographic increasing order.

Sample Input 0
```
1
1
1
2
```

Sample Output 0

`[[0,0,0],[0,0,1],[0,1,0],[1,0,0],[1,1,1]]`

Explanation 0

Each variable  and  will have values of  or . All permutations of lists in the form .
Remove all arrays that sum to  to leave only the valid permutations.

Sample Input 1
```
2
2
2
2
```

Sample Output 1
```
[[0, 0, 0], [0, 0, 1], [0, 1, 0], [0, 1, 2], [0, 2, 1], [0, 2, 2], [1, 0, 0], [1, 0, 2], [1, 1, 1], [1, 1, 2], [1, 2, 0], [1, 2, 1], [1, 2, 2], [2, 0, 1], [2, 0, 2], [2, 1, 0], [2, 1, 1], [2, 1, 2], [2, 2, 0], [2, 2, 1], [2, 2, 2]]
```

Solving

```python
if __name__ == '__main__':
    x = int(input())
    y = int(input())
    z = int(input())
    n = int(input())
    
coordinates = [[i, j, k] for i in range(x + 1) for j in range(y + 1) for k in range(z + 1) if (i + j + k) != n]
print(coordinates)
```

Input (stdin)
```
1
1
1
2
```
Your Output (stdout)
`[[0, 0, 0], [0, 0, 1], [0, 1, 0], [1, 0, 0], [1, 1, 1]]`
Expected Output
`[[0, 0, 0], [0, 0, 1], [0, 1, 0], [1, 0, 0], [1, 1, 1]]`


:snake: Please check the code in [PythonAnywhere](https://www.pythonanywhere.com/user/mayannaoliveira/shares/53a00042326e4101be30fc738962097f/).

:rocket: Follow me in [HackerRank](https://www.hackerrank.com/profile/mayannait). 

:computer: _Click here to back to [README](/README.md)._

