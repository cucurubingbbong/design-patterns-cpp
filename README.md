# 디자인 패턴 공부

같은 예제를 C#과 C++로 각각 구현합니다. 패턴을 적용한 이유와 두 언어에서 달라지는 부분도 같이 정리합니다.

| 폴더 | 내용 |
| --- | --- |
| [csharp](csharp/) | C# 구현 |
| [cpp](cpp/) | C++ 구현 |

## 공부할 패턴

| 순서 | 패턴 |
| --- | --- |
| 1 | Strategy, State, Observer, Command, Factory Method |
| 2 | Singleton, Facade, Decorator, Composite, Adapter |
| 3 | Template Method, Chain of Responsibility, Builder, Memento |

Object Pool도 별도로 구현합니다. Object Pool은 GoF 23개에 포함되는 패턴은 아닙니다.

## 정리할 내용

- 어떤 문제 때문에 사용했는지
- 적용 전후 코드
- 게임에서 쓸 수 있는 예
- 장단점과 비슷한 패턴과의 차이
- C#과 C++ 구현에서 달라진 점

각 언어 폴더 아래에 `strategy/`, `state/`처럼 패턴별로 코드를 추가합니다. 두 구현에서 같은 동작이 나오는지 확인합니다.
