# Iterable



## Dictionary

> 연관배열 구조를 이용하여 키(key)에 결과 값(value)을 저장하는 해쉬 테이블로 구현된 자료구조
>
> 키(key)는 중복이 없는 유일한 값
>
> 키(key)는 리스트타입 사용 불가, 튜플 타입 사용 가능



#### 정렬

```python
import operator
# 0은 key 값을 뜻함
sorted(dict.items(), key=operator.itemgetter(0))
# 1은 value 값을 뜻함
sorted(dict.items(), key=operator.itemgetter(1))
# reverse를 이용하여 내림차순으로 정렬
sorted(dict.items(), key=operator.itemgetter(1), reverse=True)
# 두 개의 인자 입력 시 첫 번째 인자를 기준으로 정렬 한 후, 같은 값이 있다면 두 번째 인자를 기준으로 정렬
sorted(dict.items(), key=operator.itemgetter(1, 0))
```



### Set

> 순서가 정해지지 않고, 중복을 허용하지 않는 집합을 의미

* &

  > 교집합

* |

  > 합집합

* -

  > 차집합

* add(x)

  > `x`를 `set`에 추가

* clear()

  > 모든 항목 제거

* update(iterable)

  > 여러가지 값을 추가

* remove(x)

  > `x`를 `set`에서 삭제, `x`가 없을 시 `KeyError` 발생

* discard(x)

  > `x`를 `set`에서 삭제, `x`가 없을 시 `KeyError` 발생 x

* pop()

  > 한 항목을 무작위로 제거하고 그 항목을 반환
  >
  > `set`이 비어있을 경우 `KeyError` 발생



### String

* upper()

  > 문자열 내부에 모든 알파벳을 대문자로 반환

* lower()

  > 문자열 내부에 모든 알파벳을 소문자로 반환