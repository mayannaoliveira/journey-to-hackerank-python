###  Say "Hello, World!" With Python

Here is a sample line of code that can be executed in Python:
`print("Hello, World!")`
You can just as easily store a string as a variable and then print it to stdout:

```markdown
my_string = "Hello, World!"
print(my_string)
```

The above code will print `Hello, World!` on your screen. Try it yourself in the editor below!

**Input Format: **
You do not need to read any input in this challenge.
**Output Format: **
Print `Hello, World!` to stdout.
**Sample Output: **
`Hello, World!`

:snake: **Solve: **

```python
if __name__ == '__main__':
    print("")
```

### Python If-Else

**Task**  
Given an integer, , perform the following conditional actions:

- If  is odd, print `Weird`
- If  is even and in the inclusive range of  to , print `Not Weird`
- If  is even and in the inclusive range of  to , print `Weird`
- If  is even and greater than , print `Not Weird`

**Input Format: **

A single line containing a positive integer, $n$.

**Constraints: **
$1 <= n <= 100$

**Output Format**
Print `Weird` if the number is weird. Otherwise, print `Not Weird`.

**Sample Input:**
`3`

**Sample Output:**
`Weird`

**Explanation:**  
 $n=3$ 
 $n$ is odd and odd numbers are weird, so print `Weird`.

**Sample Input 1:**
`24`

**Sample Output 1:**
`Not Weird`

**Explanation 1:**
  $n=24$
  $n>20$ and $n$ is even, so it is not weird.

:snake: **Solve:**

```python
#!/bin/python3

import math
import os
import random
import re
import sys

if __name__ == '__main__':
    n = int(input().strip())

if n % 2 != 0:
    print("Weird")
else:
    if 2 <= n <= 5:
        print("Not Weird")
    elif 6 <= n <= 20:
        print("Weird")
    else:
        print("Not Weird")
```

<details close>
<summary> <b> :woman_technologist: Output: </b> </summary>
<p>Input (stdin): 3.</p>
<p>Output (stdout): Weird.</p>
<p>Expected Output: Weird.</p>
</details>

### Arithmetic Operators
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

### Python: Division
**Task**  
The provided code stub reads two integers,  and , from STDIN.

Add logic to print two lines. The first line should contain the result of integer division,  // . The second line should contain the result of float division,  / .

No rounding or formatting is necessary.

**Example**  
$a$=3$
$b=5$ 
- The result of the integer division $3//5=0$ .
- The result of the float division is $3/5=0.6$.

**Print:**

```python
0
0.6
```

**Input Format**

The first line contains the first integer, .  
The second line contains the second integer, .

**Output Format**

Print the two lines as described above.

**Sample Input 0**

```python
4
3
```

**Sample Output 0**

```python
1
1.33333333333
```

:snake: **Solve:**
```python
 if __name__ == '__main__':
    a = int(input())
    b = int(input())
    
    print(a // b)
    print(a / b)
```

<details close>
<summary> <b> :woman_technologist: Output: </b> </summary>

 **Input (stdin)**

```python
4
3
```

**Your Output (stdout)**

```python
1
1.3333333333333333
```

**Expected Output**

```python
1
1.33333333333
```
 
