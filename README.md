# Patters in Python

Some fun patters using loops in Python.

## XmasTree

def xmasTree(n):<br />
   * k = 2 * n -2<br />
    for i in range(0,n):<br />
        * for j in range(0,k):<br />
            print(end=" ")
        k = k-1
        for j in range(0, i+1):<br />
            print("*", end=" ")
        print("\r")
        
![XmasTree](/Images/XmasTree.png)


### Cone

![Cone](/Images/Cone.png)

def cone(n):
    k = 2 * n -2
    for i in range(n, -1, -1):
        for j in range(k, 0, -1):
            print(end=" ")
        k = k+1
        for j in range(0, i+1):
            print("*", end=" ")
        print("\r")

### Future

![Future](/Images/Future.png)

def future(n):
    for i in range(0,n):
        for j in range(0,i+1):
            print("* ", end="")
        print("\r")
    for i in range(n, 0, -1):
        for j in range(0, i+1):
            print("* ", end="")
        print("\r")
 ### Past
 ![Past](/Images/Past.png)      
def past(n):
    k = 2 * n - 2
    for i in range(0, n-1):
        for j in range(0, k):
            print(end=" ")
        k = k - 2
        for j in range(0, i+1):
            print("* ", end="")
        print("\r")
    k = -1
    for i in range(n-1, -1, -1):
        for j in range(k, -1, -1):
            print(end=" ")
        k = k + 2
        for j in range(0, i+1):
            print("* ", end="")
        print("\r")
