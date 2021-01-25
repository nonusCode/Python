# collections

```python
import collections
from collections import
```



### .Counter()

> 요소가 key로 저장되고 요소의 개수가 value로 저장
>
> Dictionary로 반환



### .defaultdict()

> 내장 dict 클래스의 서브 클래스
>
> 첫 번째 인자인 default_factory는 어트리뷰트의 초기값을 제공, 기본값은 `None`

```python
from collections import defaultdict

new_dict = defaultdict(lambda: 0)
print(new_dict['key']) # 0
```

