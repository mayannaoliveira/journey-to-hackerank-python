## Python: Division

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
</details>

:snake: Please check the code in [PythonAnywhere](https://www.pythonanywhere.com).

:rocket: Follow me in [HackerRank](https://www.hackerrank.com/profile/mayannait).  

:computer: _Click here to back to [README](/README.md)._