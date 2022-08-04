# C 언어
> 저장공간 확보 -> 데이터입력 -> 처리 -> 출력 

## C 언어의 역사
> 1972년, 벨연구소, 데니스 리치와 켐톰슨
> 어떠한 유닉스 환경에서도 개발할 수 있게끔 만듦

- ANSI C (American National Standard Institute)
- C 99 (ISO - International Standard Organization)에서 정한 표준 

## 하드웨어 제어, 호환성, 이식성 함수사용

- 소스코드는 ASCII(American Standard Cord for Infomation Interchange) 코드값 형태로 저장됨
- 컴퓨터에 bit(0, 1)로 저장된다.
- 키보드로 타이핑하는 모든 것은 코드화 된 문자다.
> A라는 문자를 컴퓨터에 입력 -> ASCII 규칙을 기반으로 코드화 되어 입력되어 호출
>> 1바이트(byte)는 8비트(bit)
>>> A = 01000001 => 65 (10진수로 변환 한것이 ASCII 코드)

## 컴파일 : 코드화된 문자 -> 명령들의 집합