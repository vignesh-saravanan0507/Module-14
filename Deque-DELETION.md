# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```python
import collections
  
n1=input()
n2=input()
n3=input()
# initializing deque
de = collections.deque([n1,n2,n3])

# inserts 14,15 at the end of deque


de.append('h')
de.append('o')
de.append('n')
# printing modified deque
print ("The deque after appending at right is : ")
print (de)
```
---
### OUTPUT
![image](https://github.com/user-attachments/assets/f49994c6-f4a4-4920-b3d9-3140800fe5e1)

---
### RESULT
Thus,a Python program to delete elements at FRONT END of deque using a collection built-in function was successfully implemented and verified.
