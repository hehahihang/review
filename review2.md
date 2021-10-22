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
- 무 많아서 잠시 보류..
* Map
* List

### :arrow_forward: 반복문 vs 재귀함수 (팩토리얼 구현하기)
* 반복문
- 메모리 : Heap 메모리 사용
- 속도 : 빠름
```Java
 public static int factorial(int n){
    int sum = 1;
    for(int i=2;i<=n;i++)
        sum *= i;
    return sum;
 }
```

* 재귀함수
- 메모리 : Stack 메모리 사용, 함수가 호출될 때 마다 새 로컬변수와 매개변수 집합을 저장
- 속도 : 느림, n 값이 커질 수록 호출하는 함수가 많아져 비효율적이다.
```Java
  public static int factorial(int n){
      if(n==1) return 1;
      else return n * factorial(n-1);
  }
```

⭐ **재귀호출이 중요한 이유**
* 변수 사용을 줄일 수 있다
  - 변수 사용을 줄인다는 것은 변수가 사용하는 메모리를 줄인다는 것이 아니라, mutable state(변경 가능한 상태)를  
    제거하여 프로그램 오류 발생 가능성을 줄인다는 것이다. mutable state를 최대한 피하는 것은  
    변수의 수를 줄이는 것과 변수가 가질 수 있는 값의 종류 or 범위를 정확하게 제한하는 것이다.  
    ex) f(n)을 구하기 위해서 f(n-2), f(n-1)이라는 자기자신의 함수를 재귀적으로 매개변수만 바꾸어 호출한다  
    

## WEB
### :arrow_forward: 50억개의 URL을 중복 제거하고 크롤링하기
  - 확인 요망.... 메모리까지 신경써야해서 모르겠다 아직은

