01_Introduction of Javascript...
================================
# 1. Core Concepts of Javascript 자바스트립트의 핵심 개념
## 1.1 Object 객체
+ 거의 모든 것은 **'객체'** 이다.
+ pimitive type : boolean, number, string, null, undefined
    + **boolean, number, string** -> primitive type 이지만 객체처럼 다룰 수 있다.
    + **null, undefined** 는 특수한 값
    
## 1.2 Function 함수
+ 함수도 **'객체'** 로 취급
+ 일반적인 객체보다 조금 더 많은 기능이 있는 객체
+ 자바스크립트에서는 함수가 **'일급객체'** 로 다뤄지는 점이 중요하다.

## 1.3 Prototype 프로토타입
+ 모든 객체는 숨겨진 링크(link)인 프로토타입(prototype)을 가진다.
    + 이 링크는 해당 객체를 생성한 생성자의 프로토타입 객체를 가리킨다.
    + ECMAScript에서는 [[Prototype]]이라고 표현한다.
    
## 1.4 Execution Context And Closure 실행 컨텍스트와 클로저
+ Javascript 는 자신만의 독특한 과정으로 실행 컨텍스트롤 만들고 그 안에서 실행이 이루어진다.
    + 이 실행 컨텍스트는 자신만의 유효 범위(scope)를 갖는다.
    + 이 과정에서 클로저(Closure)를 구현할 수 있다.

# 2. OOP Programing with Javascript 자바스크립트와 객체지향 프로그래밍
+ Javascript는 클래스를 지원하지 않는다.
+ 그러나, **객체지향 프로그래밍** 이 가능하다.
    + 프로토타입prototype), 클로저closure) -> 상속(inheritance), 캡슐화(encapsulation), 정보은닉 등을 소화
    
# 3. Functional Programming with Javascript 자바스크립트와 함수형 프로그래밍
+ 함수형 프로그래밍은 높은 수준의 모듈화를 가능케 하는 프로그래밍 방법이다.
    + **일급객체** 라는 특성과 **클로저** 를 활용하여 이를 가능케 한다.
+ 가독성을 떨어뜨리게 하는 단점이 있다.
    + 과도한 클로저 사용, 함수형 프로그래밍 기법 -> 제3자가 해석하기 난해하다.
    
# 4. Weakness of Javascript
+ 굉장히 유연하고 뛰어난 표현력을 가지고 있다.
+ 위와 같은 특성 때문에 종종 **디버깅** 에 어려움을 겪기도 한다.
    + 특히, 느슨한 타입 체크는... 
        + 개발자에게 타입 체크에 대한 자유를 주지만 
        + 컴파일 타임에서 잡지 못하는 오류는 고스란히 런타임오류로 발견된다.
+ 전역 객체의 존재...
    + 이름의 충돌 위험성이 존재

    








Reference_INSIDE JAVASCRIPT(인사이드 자바스크립트) 
--------------------------------------------