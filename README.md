#Pytimer

**The Python package to measure how long it took your python function to run**

Sample:

```
import pytimer

@pytimer
def multiple_by_2(x):
    print(2*x)
```

Output:

```
multiple_by_2 : 0.00005603 seconds
```

It indicates that it took `multiple_by_2` function 0.00005603 seconds to complete
