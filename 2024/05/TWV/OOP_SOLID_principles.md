
객체지향 프로그래밍(OOP)의 SOLID 원칙은 소프트웨어 개발에서 유지 보수성과 확장성을 높이기 위해 사용하는 다섯 가지 디자인 원칙을 의미합니다. 이 원칙들은 Robert C. Martin에 의해 정의되었으며, 각 원칙의 첫 글자를 따서 SOLID라고 부릅니다.


- SOLID 원칙
	1. Single Responsibility Principle (SRP)
	2. Open/Closed Principle (OCP)
	3. Liskov Substitution Principle (LSP)
	4. Interface Segregation Principle (ISP)
	5. Dependency Inversion Principle (DIP)


1. Single Responsibility Principle (SRP)
	- 단일 책임 원칙
	- 하나의 클래스는 하나의 책임만 가져야 하며, 클래스는 그 책임을 완전히 캡슐화해야 합니다.
	- 즉, 하나의 클래스는 하나의 기능만을 담당해야 하고, 그 기능을 변경하는 이유는 오직 하나뿐이어야 합니다.

2. Open/Closed Principle (OCP)
	- 개방/폐쇄 원칙
	- 소프트웨어 개체는 확장에는 열려 있어야 하고, 변경에는 닫혀 있어야 합니다.
	- 즉, 기존 코드를 변경하지 않고도 기능을 확장할 수 있어야 합니다.

3. Liskov Substitution Principle (LSP)
	- 리스코프 치환 원칙
	- 자식 클래스는 언제나 자신의 부모 클래스를 대체할 수 있어야 합니다.
	- 즉, 자식 클래스는 부모 클래스와 호환되어야 하며, 부모 클래스 타입의 객체를 자식 클래스 타입의 객체로 대체해도 프로그램의 작동이 멈추지 않아야 합니다.

4. Interface Segregation Principle (ISP)
	- 인터페이스 분리 원칙
	- 클라이언트는 자신이 사용하지 않는 메서드에 의존하지 않아야 합니다.
	- 즉, 특정 클라이언트를 위한 인터페이스를 분리하여, 불필요한 메서드에 의존하지 않도록 합니다.

5. Dependency Inversion Principle (DIP)
	- 의존성 역전 원칙
	- 고수준 모듈은 저수준 모듈에 의존해서는 안 되며, 둘 다 추상화에 의존해야 합니다.
	- 즉, 구체적인 클래스에 의존하지 않고, 추상화된 인터페이스에 의존해야 합니다.


SOLID 원칙은 객체지향 프로그래밍에서 코드의 유지 보수성과 확장성을 높이기 위해 설계된 중요한 디자인 원칙입니다. 이 원칙들을 잘 이해하고 적용하면, 코드의 품질을 높이고, 변화에 더 유연하게 대처할 수 있는 시스템을 만들 수 있습니다.

