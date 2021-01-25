# itertools

```python
import itertools
from itertools import
```



### .combinations(iterable, r)

> 입력 iterable에서 요소의 길이 r 서브 시퀀스들을 반환 

 ```python
from itertools import combinations

arr = [1, 2, 3, 4, 5]
res = []
# 모든 부분집합
for i in range(len(arr)+1):
    sol = combinations(arr, i)
	res.extend(sol)

print(res) # [(), (1,), (2,), (3,), (4,), (5,), (1, 2), (1, 3), (1, 4), (1, 5), (2, 3), (2, 4), (2, 5), (3, 4), (3, 5), (4, 5), (1, 2, 3), (1, 2, 4), (1, 2, 5), (1, 3, 4), (1, 3, 5), (1, 4, 5), (2, 3, 4), (2, 3, 5), (2, 4, 5), (3, 4, 5), (1, 2, 3, 4), (1, 2, 3, 5), (1, 2, 4, 5), (1, 3, 4, 5), (2, 3, 4, 5), (1, 2, 3, 4, 5)]

# r길이의 부분집합 
sol = combinations(arr, 3)
res.extend(sol)

print(res) # [(1, 2, 3), (1, 2, 4), (1, 2, 5), (1, 3, 4), (1, 3, 5), (1, 4, 5), (2, 3, 4), (2, 3, 5), (2, 4, 5), (3, 4, 5)]
 ```

