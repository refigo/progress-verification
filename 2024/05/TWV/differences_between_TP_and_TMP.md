
Template programming과 template metaprogramming은 C++에서 중요한 개념이지만, 그 목적과 사용 방식에서 차이가 있습니다. 두 가지 개념을 명확히 이해하기 위해 각각의 정의와 차이를 살펴보겠습니다.

Template Programming
	C++의 제네릭 프로그래밍을 지원하는 기능으로, 함수와 클래스를 다양한 데이터 타입으로 재사용할 수 있게 합니다.
	템플릿은 코드 중복을 줄이고, 타입에 독립적인 코드를 작성할 수 있게 해줍니다.

Template Metaprogramming (TMP)
	템플릿을 이용해 컴파일 시간에 코드 실행을 수행하는 기법입니다.
	TMP를 사용하면 복잡한 컴파일 시간 계산과 조건부 로직을 구현할 수 있습니다. TMP는 주로 컴파일 시간 최적화, 타입 특성 분석, 그리고 코드 생성 등에 사용됩니다.

## 차이점 요약

1. 목적
	- Template Programming: **코드 재사용성과 일반화를 목표**로 하여, 다양한 데이터 타입에 대해 동일한 코드를 작성할 수 있게 합니다.
	- Template Metaprogramming: **컴파일 시간에 복잡한 계산과 논리를 수행하여, 런타임 오버헤드를 줄이고**, 컴파일 타임 최적화를 도모합니다.

2. 사용 시기
	- Template Programming: 주로 런타임에 동작하며, 함수와 클래스 템플릿을 통해 일반화된 코드를 작성합니다.
	- Template Metaprogramming: 컴파일 타임에 동작하여, 조건부 로직과 계산을 통해 최적화된 코드를 생성합니다.

3. 복잡도
	- Template Programming: 비교적 이해하기 쉽고, 일반적인 프로그래밍 패턴에 가깝습니다.
	- Template Metaprogramming: 복잡하고 추상적인 개념을 포함하며, 컴파일러에 의해 수행되는 프로그래밍이라는 점에서 더 난해할 수 있습니다.


4. 컴파일 타임 vs 런타임
	- Template Programming: 주로 런타임에 동작하는 코드를 생성합니다.
	- Template Metaprogramming: 컴파일 타임에 코드를 실행하여 최적화된 코드를 생성합니다.

## 결론

Template Programming과 Template Metaprogramming은 C++의 템플릿 기능을 활용하는 두 가지 다른 접근 방식입니다. Template Programming은 다양한 타입에 대해 동일한 코드를 재사용할 수 있도록 하는 반면, Template Metaprogramming은 컴파일 시간에 복잡한 계산과 최적화를 수행합니다. 각각의 기술은 특정 상황에서 매우 유용하며, C++의 강력한 기능을 활용하는 데 중요한 역할을 합니다.


## References

- [Wikibooks on Template Metaprogramming](https://en.wikibooks.org/wiki/C%2B%2B_Programming/Templates/Template_Meta-Programming)
- https://en.wikipedia.org/wiki/Template_metaprogramming

