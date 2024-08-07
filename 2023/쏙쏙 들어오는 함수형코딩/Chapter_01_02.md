# TIL (2023.08.08)

## DAY 1

오늘 읽은 범위: 시작 - 1장) 쏙쏙 들어노는 함수형 코딩에 오신 것을 환영합니다. / 2장) 현실에서의 함수형 사고

---

```text
😉 책에서 기억하고 싶은 내용을 써보세요.
```

## 실용적인 측면에서 함수형 프로그래밍 정의의 문제점은?

- 부수 효과는 필요하다. -> 부수 효과는 소프트웨어를 실행하는 이유
- 부수 효과를 잘 다룰 수 있다. -> 순수 함수만 쓰라는 것처럼 되어 있지만, 순수하지 않은 함수도 사용합니다.
- 실용적이다.

## 액션, 계산, 데이터는 무엇일까?

일반적으로 액션보다는 계산이 쓰기 쉽고 계산 보다는 데이터가 쓰기 쉬워요.
각각을 살펴보면:

- 액션(Actions) : 실행 시점이나 횟수 또는 둘다에 의존
- 계산(calculations) : 입력값으로 출력값을 만드는 것
- 데이터(Data) : 이벤트에 대해 기록한 사실

## 액션, 계산 데이터를 구분하면 어떤 장점이?

분산 시스템에 잘어울려요:

- 데이터와 계산은 실행 시점이나 횟수에 의존하지 않아요
- 액션은 실행 시점과 횟수에 의존하기 때문에 문제가 되지만, 코드 전체에 영향을 주지 않도록 격리시키면 되요.
- 결론적으로 코드의 많은 부분을 액션에서 계산으로 옮기면 결과적으로 액션도 다루기 쉬워져요.

## 함수형 사고가 무엇인가요?

함수형 프로그래머가 소프트웨어 문제를 해결하기 위해 사용하는 기술과 생각을 말해요.
여기에 2가지 개념이 있어요:

- 액션과 계산, 데이터를 구분
- 일급 추상

### 그럼 액션과 계산, 데이터를 구분하려면 어떻게 해야할까?

계층형 설계 원칙을 사용하면 되요:

- 계층형 설계: 일반적으로 비즈니스 규칙, 도메인 규칙, 기술 스택 계층으로 나뉘어요. 그리고 위쪽으로 갈수록(비즈니스 계층) 자주 바뀌는 코드가 있고
  아래쪽으로 갈수록(기술 스택) 자주 바뀌지 않는 코드가 있어요

### 일급 추상은?

타임라인 다이어그램을 활용해요:
타임라인 다이어그램: 시간에 따라 변하는 액션을 시각화하는 방법을 말해요.

```text
🤔 오늘 익은 소감은? 떠오르는 생각을 가볍게 적어보세요
```

- 계층형 설계로 액션과 계산, 데이터를 구분하고 그중에 액션을 타임라인 다이어그램을 통해 시각화 한다.

```text
궁금한 내용이 있거나, 잘 이해되지 않는 내용이 있다면 적어보세요.
```
