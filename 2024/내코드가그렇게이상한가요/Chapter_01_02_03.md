# TIL (2024.07.04)

## DAY 1

오늘 읽은 범위:

1장) 잘못된 구조의 문제 깨닫기

2장) 설계 첫걸음

3장) 클래스 설계: 모든 것과 연결되는 설계 기반

---

```text
😉 책에서 기억하고 싶은 내용을 써보세요.
```

일단 나쁜 구조의 폐해를 인지해야 합니다. 나쁜 폐해를 인지하면, '어떻게든 대처해야겠다' 라고 생각하게 되죠. (p.30)

의도를 갖고 적절하게 설계하면, 유지 보수와 변경이 쉬워집니다. (p.39)

시스템 사양에 필요한 메서드만 정의합시다 (p53)

클래스 설계란 인스턴스 변수가 잘못된 상태에 빠지지 않게 하기 위한 구조를 만드는 것 (p.55)

데이터와 그 데이터를 조작하는 로직을 한곳에 모아 응집도를 높이는 것, 그리고 필요한 조작만 외부에 공개해서캡슐화 하는 것이 중요하다.

좋은 구조란?

- 불필요한 중복 코드 제거
- 높은 가독성
- 불필요한 쓰레기 객체 생성 방지
- 잘못된 값이 들어오는걸 방지
- 생각하지 못한 부수 효과 차단
- 값 전달 실수 방지(타입)
