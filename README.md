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
    return 0; // 함수의 기능을 끝내고 함수를 호출한 곳으로 제어를 돌려줌
}

// 한줄 주석문
/*
여러줄 주석
*/

#include <stdio.h> // 전처리 지시자, stdio.h 에서 printf를 호출
int main(void) {
    printf("Be Happy \n"); // 문자열 출력 \n 줄바꿈
    printf("Dont Worry");
    printf("%d", 10); // 정수 10
    printf("%lf", 3.4); // 실수 3.400000
    printf("%.1lf", 3.4); // 실수 3.4
    return 0;
}
/n : 줄바꿈
/r : 커서를 해당줄에 맨 앞으로
/b : 커서를 한칸 왼쪽으로 (백스페이스)
/t : 운영채제에서 다음 탭(8비트)으로 이동
/a : 비프음 사운드 제어

```
