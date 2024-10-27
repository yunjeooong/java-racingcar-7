# java-racingcar-precourse
## 📌 2주차 목표
###  - 단일 책임의 원칙을 지키기
하나의 클래스 안에 하나의 책임만 갖을 수 있도록 구현할 예정이에요
### -  조금 더 확장성을 고려해보기
오버 엔지니어링까지는 아니더라도 확장성을 고려서 좀 더 유지보수 하기 쉬운 코드를 작성하고 싶어요!
### - 테스트 코드 작성하기 
조듬 더 단단한 테스트 코드를 작성하고 싶어요

----------------------------------------------------------------------------------------------------
### 💬 입력 처리
- [ ] 자동차 이름 입력: 자동차 이름은 쉼표(,)를 기준으로 구분 
    - [ ] 자동차 이름 입력은 5자 이하
- [ ] 시도할 횟수 입력: 몇 번의 이동을 할 것인지를 입력
### 💬 게임 처리 
- [ ] 자동차 전진 조건 확인: 무작위로 생성된 값(0-9)이 4 이상일 경우 자동차는 전진한다.
    - [ ] 랜덤값 생성 (0~9)
    - [ ] 랜덤값 4이상 인 경우 전진
- [ ] 자동차 이동 출력: 입력 받은 횟수만큼 자동차가 전진할 때, 해당 자동차의 이름과 함께 이동 상태를 출력한다.
### 💬 우승자 선정 처리  
- [ ] 우승자 출력
    - [ ] 가장 멀리 이동한 자동차가 우승
    - [ ] 우승자가 다수 일 경우에는 ,로 구분하여 출력
------------------
### 🛎️ 입력 
- [x] 자동차 이름 입력 (,)로 구분
    - [x] 메세지: 경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
- [ ] 이동 횟수 입력
    - [x] 메세지: 시도할 횟수는 몇 회인가요?
### 🛎️ 출력  
- [ ] 각 차수 별 실행 결과
- [ ] 우승자 안내 문구 (단독 or 공동)
- [ ] 에러 상황 시 에러 문구

### 예외 처리
- [x] 자동차 이름 5자 이상
- [x] 자동차의 개수 2대 미만일 경우
- [ ] 잘못된 입력 처리: 입력이 잘못되었을 경우 IllegalArgumentException을 발생시키고 애플리케이션을 종료한다.
- [ ] 시도할 횟수
    - [x] 시도 횟수가 문자일경우
    - [x] 시도 횟수가 범위에 벗어날 경우 (int 범위에 벗어날 경우)


-----
### 요구 사항 
- [x] branch 아이디에서 미션 진행
- [ ] indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
- [ ] 3항 연산자를 쓰지 않는다.
- [ ] 함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 만들어라.
- [ ] JUnit 5와 AssertJ를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인한다.




