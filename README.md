# be-java-chess-max
2023 마스터즈 맥스 보너스 프로젝트 체스

## 미션 첫째주(6/5 ~ 6/9) 구현계획
| 날짜    | 6/5(월)                | 6/6(화)                | 6/7(수)            |6/8(목)|6/9(금)|
|-------|-----------------------|-----------------------|-------------------|---|---|
| 구현 내용 | 체스 구현 시작하기<br>체스판 생성 | 체스판 초기화<br>모든 기물 배치하기 | 보드에 위치 부여 및 점수 계산 |기물 이동 구현|예외 처리|

## 구현 내용
### 체스 구현 시작하기
- 개발 환경 설정
  - [x] gradle project 생성하기
  - [x] build.gradle 수정하기
- Pawn Test 생성
  - [x] createWhitePawn() 메서드 작성: 컴파일도 되지 않는 메서드 생성
- Pawn Class 생성
  - [x] create() 메서드 작성: createWhitePawn() 메서드가 컴파일만 되고 실패하게 Pawn Class 생성
- PawnTest 수정하기
  - [x] createWhitePawn()을 createPawns 테스트로 변경: 검은색 Pawn을 생성하고 실패하는 테스트 작성
- Pawn Class 수정하기
  - [x] createPawns() 테스트가 통과하게 Pawn 클래스 수정하기
- 리팩토링
  - [x] createPawns() 테스트에 local variable을 추가해서 코드의 중복제거
  - [x] PawnTest Class에 verifyPawnColor메서드를 생성하여 메서드 분리하기