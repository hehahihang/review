## CS
### :arrow_forward: Statically Typed vs Dynamic Typed  
* **Statically Typed(정적 타입 언어)**
  - 컴파일 시 변수의 타입이 결정되는 언어
  - 컴파일 시에 자료형에 맞지 않는 값이 들어있으면 컴파일 에러ㅊ 발생
  - 프로그래머가 변수에 들어갈 값의 형태에 따라 직접 변수의 타입을 명시해줘야 함
  - Java, C, C++, C#, Scala  
  - 장점
    1.  타입 에러로 인한 문제점을 초기에 발견할 수 있어, **타입의 안정성이 높음**
    2.  컴파일 시에 미리 타입을 결정하기 때문에 **실행속도가 빠름**
  - 단점
    1. 매번 코드를 작성할 때 마다 변수형을 결정해 주어야하는 번거로움
  
* **Dynamically Typed(동적 타입 언어)**
  - 런타임(Runtime, 실행)시에 자료형을 결정하는 언어
  - Python, JavaScript, Ruby, PHP
  - 장점
    1. 런타임까지 타입에 대한 결정을 끌고갈 수 있어 **유연성이 높음**
    2. 컴파일시에 타입을 명시하지 않아도 돼 빠르게 코드 작성 가능
  - 단점
    1. 실행 도중에 변수에 예상치 못한 타입이 들어오면 Type Error 발생


## Java
### :arrow_forward: Java의 자료구조

### :arrow_forward: 반복문 vs 재귀 (팩토리얼 구현하기)
* 반복문
  '''Java
    public static int factorial(int n){
      int sum = 1;
      for(int i=2;i<=n;i++)
        sum *= i;
      return sum;
     }
  '''


## WEB
### :arrow_forward: 50억개의 URL을 중복 제거하고 크롤링하기
  - 확인 요망.... 메모리까지 신경써야해서 모르겠다 아직은
