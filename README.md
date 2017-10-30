# [LearningInternalRepresentationsByErrorPropagation](http://www.cs.toronto.edu/~fritz/absps/pdp8.pdf)
Let's code up backprop!

### [Map & Reduce](https://youtu.be/BihhRsWeKAo?t=2m25s)

```python
from math import sqrt
#Map a function to dfs or tensors
sq_numbers = [1*1, 2*2, 3*3, 4*4, 5*5, 6*6, 7*7, 8*8, 9*9]
numbers = list(map(sqrt, sq_numbers)
list(numbers)

from functions import reduce
#create a tuple in string form from x and y
def combine(x, y):
  return '(' + string(x) + ', '+ str(y) + ')'

print(numbers)
reduce(combine, numbers)
