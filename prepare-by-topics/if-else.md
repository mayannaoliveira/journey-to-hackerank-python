## Python If-Else

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


:snake: Please check the code in [PythonAnywhere](https://www.pythonanywhere.com).

:rocket: Follow me in [HackerRank](https://www.hackerrank.com/profile/mayannait). 

:computer: _Click here to back to [README](/README.md)._