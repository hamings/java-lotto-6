# 기능 구현 정리

##  Model

### Lotto

- [x] `로또 발행` 기능
    - [x] 로또 번호 중복 체크 기능
    - [x] 당첨번호 개수 확인 기능
    - [x] 보너스 번호 맞았는지 확인 기능


### Lottos

- [x] `로또들 생성` 기능
    - [x] `중복된 이름` 있으면 예외 처리
    - [x] `구매금액` 유효성 확인
    - [x] '당첨등수' 체크 기능
    - [x] `이익률` 계산


### WinningNumber (로또 결과 )

- [x] `로또 당첨 번호` 저장 기능
- [x] `로또 보너스 번호` 저장 기능
- [x] `로또 번호` 유효성 확인


### RandomNumberGenerator

- [x] `1~45 사이의 6개의 중복되지 않은 랜덤 숫자` 생성 기능

##  View

### InputView

- [x] `로또 구매금액` 입력 기능 
    - [x] `구매금액 % 1000!=0`면 예외 처리
    - [x] 구매금액이 `0원`이면 예외 처리
- [x] `당첨번호` 입력 기능 
    - [x] `1~45` 아니면 예외 처리
    - [x] 당첨번호 `6개` 아니면 예외 처리
- [x] `보너스 번호` 입력 기능
    - [x] `1~45` 아니면 예외 처리

### OutputView
- [x] `로또 구매 수량 및 결과` 출력 기능
- [x] `로또 결과` 출력 기능
- [x] `수익률 출력` 출력 기능

## Controller

### LottoController

- [x] `로또 발행` 기능 (금액 입력받아 로또 발행)
- [x] `로또 당첨번호` 저장 기능
- [x] `로또 결과 및 수익률` 출력기능 (당첨결과 출력)


## 🔑 Exception

### ErrorMessage

- [x] `예외 메시지` 제공 기능
