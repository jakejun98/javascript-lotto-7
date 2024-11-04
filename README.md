# javascript-lotto-precourse
## 기능 구현 목록
### 입력
- 로또 구입 금액 입력
  - 지정 단위 아닌 경우 예외처리
- 당첨 번호 입력
  - 쉼표 구분
  - 중복인 경우 예외처리
  - 1~45범위 아닌 경우 예외처리
- 보너스 번호 입력
  - 당첨번호와 중복인 경우 예외처리
  - 1~45범위 아닌경우 예외처리
### 출력
- 구입한 로또번호 출력
  - (구입금액 / 1000)개 만큼 배열로 생성 후 출력 , 배열 안 요소 오름차순 정렬
- 당첨통계 출력
  - 출력한 배열내부 요소와 당첨번호 비교
  - 수익률 계산 
