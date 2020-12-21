# Built-in function



### abs(x)

> 숫자의 절대값을 반환
>
> 인자가 복소수이면 크기를 반환



### all(iterable)

> iterable의 모든 요소가 참이면(또는 iterable이 비어있으면) `True`를 반환
>
> 숫자 0은 `False` 반환, 문자 '0'은 `True` 반환
>
> Dictionary의 경우 key값의 참, 거짓을 판단하여 반환



### any(iterable)

> iterable의 요소 중 어느 하나라도 참이면 `True`를 반환
>
> iterable이 비어 있으면 `False`를 반환



### bin(x)

> 정수를 `0b`가 앞에 붙은 이진 문자열로 반환

```python
# 접두어 0b 필요할 경우
bin(x)
format(x, "#b")
f"{x:#b}"

# 접두어 0b 필요없을 경우
format(x, 'b')
f"{x:b}"
```



### divmod(a, b)

> 두 개의 (복소수가 아닌)숫자를 인자로 취하고 정수 나누기를 사용할 때의 몫과 나머지로 구성된 한 쌍의 숫자를 반환
>
> 두 인자의 형이 다른 경우, 이 항 산술 연산자에 대한 규칙 적용



### int(x, base)

> 숫자나 문자열 x로 부터 만들어진 정수 객체 반환
>
> 인자가 주어지지 않으면 숫자 0 반환
>
> base 생략 가능(default=10)
>
> base는 0, 2 ~ 36 사이의 값

