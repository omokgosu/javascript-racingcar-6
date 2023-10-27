#자동차 경주

## 기능 목록

- [ ] 자동차에 이름을 부여할 수 있어야 한다.
    - [ ] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
    - [ ] 자동차 이름은 5글자 이하여야 한다.

- [ ] 사용자는 몇 번의 이동을 할 것인지 입력할 수 있어야 한다.

- [ ] 사용자는 입력 횟수에 따른 자동차 이동 실행결과를 확인할 수 있다.
    - [ ] 주어진 횟수 n 동안 자동차는 전진 또는 멈출 수 있다.
    - [ ] 전진하는 조건은 0에서 9사이의 무작위 값 중 무작위 값이 4 이상일 경우이다.
    - [ ] 출력 시 자동차 이름을 같이 출력한다.

- [ ] 사용자는 최종 우승자를 확인할 수 있어야 한다.
    - [ ] 최종 우승자는 1명 또는 여러명일 수 있다.
    - [ ] 우승자가 여러명일 경우 쉼표(,)를 사용하여 구분한다.

- [ ] 사용자가 잘못된 값을 입력한 경우 예외 처리를 할 수 있어야 한다.
    - [ ] 예외는 thorw 문을 사용해 처리한다.
    - [ ] '[ERROR]' 로 시작하는 메시지를 가져야 한다.

## 기능 요구 사항

초간단 자동차 경주 게임을 구현한다.

각 자동차에 이름을 부여할 수 있다. 
자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.

e.g. pobi,woni,jun

사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.   

e.g 5

주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.

e.g.
pobi : --
woni : ----
jun : ---


자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.

e.g.
최종 우승자 : pobi
최종 우승자 : pobi,jun

사용자가 잘못된 값을 입력한 경우 throw문을 사용해 "[ERROR]"로 시작하는 메시지를 가지는 예외를 발생시킨 후, 애플리케이션은 종료되어야 한다.
e.g.
숫자가 잘못되었을 때 : [ERROR] 숫자가 잘못된 형식입니다.