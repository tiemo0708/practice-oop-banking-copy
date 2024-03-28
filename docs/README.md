## 기능 목록

- [ ]  **계좌를 생성한다.**
    - [ ]  계좌 종류(예금:N, 적금: S)를 선택한다
    - [ ]  이름을 입력한다.
    - [ ]  계좌번호를 입력한다(5자리)
    - [ ]  첫 입금액을 입력받는다.
    - [ ]  적금 계좌일 경우 ****목표 금액을 입력한다
- [ ]  **계좌 정보를 보여준다 -  getAccountInf()**
    - [ ]  계좌종류, 계좌번호, 소유자, 잔액, 활성화 여부를 보여준다
    - [ ]  적금 계좌일 경우 목표 금액을 추가로 보여준다.
- [ ]  **입금 기능**
    - [ ]  사용자가 입력한 입금액을 계좌잔액에 더한다.
    - [ ]  활성화 되지 않은 계좌에는 입금불가능
- [ ]  **출금 기능**
    - [ ]  사용자가 입력한 출금액만큼 계좌잔액에서 뺀다
    - [ ]  출금액이 잔액보다 크면 출금이 실패한다.
    - [ ]  적금 계좌일 경우 잔액이 목표액보다 많아야 출금이 가능하다
    - [ ]  계좌 잔액에 대한 이자금액을 보여준다
        - [ ]  일반계좌 이자금액을 보여준다
            - 1000만원 이상 50%
            - 500만원이상 7%
            - 100만원이상은 4%
            - 1만원이상은 2%
            - 나머지 1%
        - [ ]  적금계좌 이자금액을 보여준다.
            - 100만원 이상 50%
            - 나머지 1%
- [ ]  **송금 기능**
    - [ ]  사용자의 계좌의 잔액에서 송금 금액을 뺀다
    - [ ]  송금 받는 사람 계좌의 잔액에 송금금액을 거해준다.
- [ ]  **해당 계정을 비활성화 한다**

**예외처리**

- [ ]  입금 금액이 1이상의 숫자가 아닌 경우
- [ ]  출금 금액이 1이상의 숫자가 아닌 경우
- [ ]  출금 금액이 잔액보다 많은 경우
- [ ]  계좌번호가 숫자가 아닌 경우
- [ ]  계좌 형식이 알맞지 않은 경우
- [ ]  없는 계좌로 송금, 입금, 출금을 시도할 경우
- [ ]  활성화 되지 않은 계좌에 입금하는경우
- [ ]  활성화 되지 않은 계좌에 출금하는경우