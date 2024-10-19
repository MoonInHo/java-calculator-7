# java-calculator-precourse

### 개발 방식
- 테스트 주도 개발 (TDD)

### 구현할 기능 목록
- 입력 값 변환기
  - 빈 문자열은 "0"을 반환
  - 양수로만 구성된 문자열은 입력 값 그대로 반환
- 문자열 검증
  - 커스텀 구분자 선언부에 구분 기호 누락 시 예외 발생
  - 커스텀 구분자 자릿 수 초과 시 예외 발생
  - 커스텀 구분자에 숫자 포함 시 예외 발생
  - 이미 존재하는 구분자 선언 시 예외 발생
  - 구분자 외의 문자 포함 시 예외 발생
- 구분자 패턴을 이용한 문자열 파싱
  - 커스텀 구분자가 존재하지 않을 경우 기본 구분자로 파싱
  - 커스텀 구분자가 존재할 경우 기본 구분자와 커스텀 구분자를 혼합하여 파싱
  - 파싱된 문자열 배열에 담아서 반환
- 문자열 덧셈
  - 전달받은 숫자의 합을 애플리케이션에 반환