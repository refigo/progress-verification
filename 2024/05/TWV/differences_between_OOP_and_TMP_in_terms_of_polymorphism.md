
다형성은 객체지향 프로그래밍(OOP)과 템플릿 메타프로그래밍(TMP) 모두에서 중요한 개념이지만, 두 접근 방식에서의 다형성 구현과 역할은 다릅니다. 아래에서는 이 두 가지의 역할과 차이점을 다형성의 관점에서 설명하겠습니다.


- 객체지향 프로그래밍(OOP)에서의 다형성
	- OOP 다형성 정의
		- 다형성(Polymorphism)은 객체지향 프로그래밍에서 **동일한 인터페이스나 부모 클래스를 통해 다양한 형태의 객체를 사용할 수 있게 하는 기능**입니다.
		- **주로 상속과 인터페이스를 통해 구현**됩니다.
	- 종류
		1. 컴파일 타임 다형성 (Compile-time Polymorphism):
			- 오버로딩 (Overloading): 같은 이름의 메서드가 매개변수의 유형이나 개수에 따라 다르게 동작합니다.
			- 템플릿 (Templates): C++에서 제공하는 제네릭 프로그래밍 기능으로, 다양한 데이터 타입을 처리할 수 있는 코드를 작성할 수 있습니다.
		2. 런타임 다형성 (Runtime Polymorphism):
			- 오버라이딩 (Overriding): 자식 클래스가 부모 클래스의 메서드를 재정의하여 런타임에 해당 메서드를 호출할 때 다르게 동작하도록 합니다.
			- 추상 클래스와 인터페이스: 인터페이스나 추상 클래스를 통해 다양한 구현체를 사용할 수 있습니다.

- 템플릿 메타프로그래밍(TMP)에서의 다형성
	- TMP 다형성 정의
		- 템플릿 메타프로그래밍에서는 다형성이 템플릿 인스턴스화와 컴파일 타임 계산을 통해 달성됩니다.
		- TMP는 코드의 재사용성과 컴파일 타임 최적화를 위해 사용됩니다.
	- TMP에서의 다형성 구현
		1. 템플릿 특수화 (Template Specialization):
			- 일반 템플릿과 특수화된 템플릿을 통해 다형성을 구현할 수 있습니다.
		2. 템플릿 인스턴스화 (Template Instantiation):
			- 템플릿이 인스턴스화될 때 다양한 타입을 처리하도록 다형성을 제공합니다.


### 역할과 차이점
1. 다형성 구현 방법:
	- OOP: 주로 상속과 가상 함수(virtual function)를 통해 런타임 다형성을 구현합니다. 객체의 타입에 따라 동작이 다를 수 있습니다.
	- TMP: 템플릿 특수화와 인스턴스화를 통해 컴파일 타임에 다양한 타입을 처리합니다. 이는 컴파일 타임 다형성에 해당합니다.

2. 성능 및 컴파일 시간:
	- OOP: 런타임에 다형성을 지원하므로 약간의 오버헤드가 발생할 수 있습니다.
	- TMP: 컴파일 타임에 모든 결정이 이루어지므로 런타임 오버헤드가 없지만, 컴파일 시간이 길어질 수 있습니다.

3. 유연성:
	- OOP: 런타임에 객체의 타입을 변경하거나 확장하기 용이합니다.
	- TMP: 컴파일 타임에 타입을 결정하므로 유연성이 제한되지만, 특정 타입에 최적화된 코드를 생성할 수 있습니다.

4. 적용 분야: ⭐️
	- OOP: 대규모 소프트웨어 시스템, 게임 개발, GUI 애플리케이션 등 런타임에 객체의 다양한 동작이 필요한 경우에 적합합니다.
	- TMP: 컴파일 타임 최적화, 고성능 라이브러리(STL, Boost) 등에서 사용되며, 특히 성능이 중요한 경우에 유용합니다.


## References

- [wikibooks - C++ Programming/Templates/Template Meta-Programming](https://en.wikibooks.org/wiki/C%2B%2B_Programming/Templates/Template_Meta-Programming)
- [caiorss - CPP / C++ - Template Metaprogramming - Generic Programming](https://caiorss.github.io/C-Cpp-Notes/CPP-template-metaprogramming.html)
