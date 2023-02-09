## 프로그램 실행 프로세스
1. 자동차 이름 입력 안내문구 출력
2. 자동차 이름 입력 받음
    - 이름은 5자 이내 여야 한다.
    - 이름은 쉼표(,)로 구분된다.
    - 자동차의 댓수는 1이상의 자연수이다.
3. 시도할 횟수 입력 안내문구 출력
4. 시도할 횟수 입력 받음
   - 자연수여야 한다
5. 자동차별 이동
6. 실행 결과 출력
7. 최종 우승자 확인
8. 최중 우승자 출력

## 기능 구분
### 도메인 로직
- [x] 자동차 객체를 생성한다
  - [x] 이름을 검증한다
- [x] 시도할 횟수를 저장한다
  - [x] Integer.MAX_VALUE 고려
  - [x] 음수, 0 고려
- [ ] 자동차 별 이동
  - [ ] 전진 조건의 random value를 생성한다
  - [x] 자동차의 이동 기록에 추가한다
  - [x] 자동차들에 이동 기록을 추가한다
  - [x] 자동차들의 진행 라운드, 턴 수를 확인한다
  - [x] 자동차의 위치를 계산한다
- [ ] 자동차 별 이동을 시도할 횟수만큼 각각 반복한다
- [ ] 우승자를 확인한다

### 어플리케이션 서비스 로직
- [x] 자동차 이름 입력 안내문구 출력
- [x] 자동차 이름 입력 받음
  - [x] 입력 형식을 검증한다
- [x] 시도할 횟수 입력 안내 문구를 출력
- [x] 시도할 횟수 입력 받음
  - [x] 입력 형식을 검증한다
- [ ] 각 시도의 결과를 출력한다
- [ ] 우승자를 출력한다

## 이번 미션에서 집중할 부분
1. 단위 테스트
2. 코드 품질