# C 언어 1장
> 저장공간 확보 -> 데이터입력 -> 처리 -> 출력 

<br />

## C 언어의 역사
> 1972년, 벨연구소, 데니스 리치와 켐톰슨
> 어떠한 유닉스 환경에서도 개발할 수 있게끔 만듦

- ANSI C (American National Standard Institute)
- C 99 (ISO - International Standard Organization)에서 정한 표준 

<br />

## 하드웨어 제어, 호환성, 이식성 함수사용

- 소스코드는 ASCII(American Standard Cord for Infomation Interchange) 코드값 형태로 저장됨
- 컴퓨터에 bit(0, 1)로 저장된다.
- 키보드로 타이핑하는 모든 것은 코드화 된 문자다.
> A라는 문자를 컴퓨터에 입력 -> ASCII 규칙을 기반으로 코드화 되어 입력되어 호출
>> 1바이트(byte)는 8비트(bit)
>>> A = 01000001 => 65 (10진수로 변환 한것이 ASCII 코드)

<br />

## 컴파일 : 코드화된 문자 -> 명령들의 집합
- ASCII 코드로 작성된 소스코드를 CPU가 이해할 수 있는 명령어로 바꾸어 주는것이 컴파일
> 소스코드 작성 -> 컴파일 ->  운영체제에서 실행

<br /><br />

# C 언어 2장

- 함수로 구성되어 있다.
- 하나의 함수로 구성된다면 main

```C
int main(void) {
    10 + 20;
    10
    +
    20
    ;
    return 0;
}
```