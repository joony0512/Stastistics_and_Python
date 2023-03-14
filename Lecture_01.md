# 변수형과 자료형

## 리스트(LIst) Method

- Append()

Append() is a method in programming that adds an element or object to the end of an existing list or array.

This method is particularly useful when we want to add new data to an existing list without altering the existing data. For example, we can use the Append() method to add a new score to a list of test scores, or to add a new item to a shopping list.

In Python, the Append() method is used to add an element to the end of a list. Here's an example of how to use the Append() method:

```
my_list = [1, 2, 3]
my_list.append(4)
print(my_list)

```

The output of this code would be:

```
[1, 2, 3, 4]

```

As you can see, the Append() method has added the number 4 to the end of the list.

- Insert()

Insert() is a function or method used in computer programming to add an element or item into a data structure, such as an array, list, or string.

In Python, the Insert() method is used to add an element at a specific index position in a list. Here's an example of how to use the Insert() method:

```
my_list = [1, 2, 3]
my_list.insert(1, 4)
print(my_list)

```

The output of this code would be:

```
[1, 4, 2, 3]

```

As you can see, the Insert() method has added the number 4 at index position 1 of the list.

Other methods that can be used with lists in Python include Append(), Extend(), Remove(), Pop(), Index(), Count(), Sort() and Reverse().

- Extend()
- Remove()
- Pop()
- Index()
- Count()
- Sort()
- Reverse()

## 튜플(Tuple)

- 리스트와 유사하나 한번 입력되면 이후 항목을 변경할 수 없음
- ()사용

## 세트(Set)

- {}사용, 순서 없음, 중복불가
- 세트 메소드
    - 교집합 : A.intersection(B)
    - 합집합 : A.union(B)
    - 차집합 : A.difference(B)

## 딕셔너리(dictionary)

딕셔너리는 컴퓨터 과학에서 사용되는 자료 구조 중 하나로, 키와 값으로 이루어진 쌍들의 집합을 나타냅니다.

딕셔너리는 리스트나 튜플처럼 순서가 있지 않으며, 각 요소의 위치를 나타내는 인덱스 대신 고유한 키를 사용하여 각 값을 구분합니다. 이러한 구조는 특정 키에 대한 값을 빠르게 찾을 수 있도록 도와줍니다.

예를 들어, 다음과 같이 딕셔너리를 정의할 수 있습니다.

```
my_dict = {'apple': 1, 'banana': 2, 'orange': 3}

```

이 딕셔너리에서 'apple', 'banana', 'orange'는 각각 고유한 키이며, 1, 2, 3은 각각 해당 키에 대한 값입니다. 딕셔너리는 중괄호({})를 사용하여 정의하며, 각 키와 값은 콜론(:)으로 구분됩니다.

딕셔너리에는 여러 가지 유용한 메소드가 있으며, 이를 사용하여 딕셔너리의 요소를 추가, 삭제, 수정 및 검색할 수 있습니다.

다음은 딕셔너리에서 사용할 수 있는 일부 메소드입니다.

- keys() : 딕셔너리의 모든 키를 반환합니다.
- values() : 딕셔너리의 모든 값을 반환합니다.
- items() : 딕셔너리의 모든 키-값 쌍을 반환합니다.
- get() : 지정된 키에 대한 값을 반환합니다. 키가 없으면 None을 반환합니다.
- pop() : 지정된 키에 대한 값을 반환하고 해당 키-값 쌍을 딕셔너리에서 제거합니다.
