# 프리코스 1주차 미션: 문자열 덧셈 계산기
## 기능 목록 정리
- [ ]  문자열 입력 처리: 사용자에게 콘솔에서 문자열을 입력받는다.
- [ ]  구분자 처리: 입력받은 문자열에서 구분자를 판별한다.
   - 기본 구분자: 쉼표, 콜론을 기본 구분자로 설정한다.
   - 커스텀 구분자: 커스텀 구분자인지 판별하기 위해 "`//`"와 "`\n`" 사이에 위치하는 “문자”를 찾고, 해당 문자를 커스텀 구분자로 사용한다.
- [ ]  입력 받은 숫자 누적: 문자열에서 구분자를 기준으로 덧셈할 숫자를 추출하고 누적한다.
- [x]  덧셈 연산 처리: 누적된 숫자 덧셈 연산한다.
- [ ]  최종 결과 반환: 모든 숫자를 더한 결과를 반환한다.
- [ ]  오류 처리: 비정상적인 사용자 입력에 대한 오류 처리 및 애플리케이션 종료한다.
   - [ ]  커스텀 구분자 선언 오류
   - [ ]  연산할 숫자가 아닌 잘못된 사용자 입력
   - [x]  구분자, 양수가 아닌 사용자 입력