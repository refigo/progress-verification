
**포인터 변수는 메모리 주소를 저장하며 동적 메모리 할당과 같은 다양한 방식으로 유연하게 사용할 수 있습니다.**
**배열 변수는 정적으로 크기가 할당된 메모리 블록으로, 선언 시 크기가 고정되고 배열 이름은 배열의 첫 번째 요소의 주소를 가리킵니다.**

포인터와 배열은 많은 경우에 서로 교환 가능하게 사용할 수 있지만, 그 특성과 사용법에는 중요한 차이점이 있습니다.

1. 정의와 선언
	1. 포인터 변수는 메모리 주소를 저장하는 변수입니다. 어떤 타입의 포인터 변수는 그 타입의 데이터를 가리키는 메모리 주소를 저장할 수 있습니다.
	2. 배열 변수는 동일한 타입의 데이터가 연속적으로 저장된 메모리 공간을 나타냅니다. 배열 변수는 해당 배열의 첫 번째 요소의 메모리 주소를 가리킵니다.
2. 메모리 할당
	1. 포인터 변수 자체는 메모리 주소를 저장하는 공간만 할당됩니다. 데이터에 대한 메모리는 별도로 할당해야 합니다.
	2. 배열 변수는 선언 시에 배열의 크기만큼 메모리가 할당됩니다.
3. 메모리 접근 🤔
	1. 포인터 변수는 가리키는 메모리 주소를 통해 데이터를 접근합니다.
	2. 배열 변수는 배열의 인덱스를 통해 데이터를 접근합니다. 🤔
4. 배열과 포인터의 관계
	1. 배열 변수는 배열의 첫 번째 요소의 주소로 평가될 수 있습니다. 따라서 포인터와 배열은 많은 경우에 서로 교환 가능하게 사용할 수 있습니다.
	2. 포인터와 배열 이름을 사용하여 동일한 방식으로 배열 요소에 접근할 수 있습니다. 👍
5. 크기 정보
	1. 포인터 변수는 가리키는 데이터의 크기 정보를 가지고 있지 않습니다. 즉, 포인터가 몇 개의 요소를 가리키는지 알 수 없습니다.
	2. 배열 변수는 배열의 크기 정보를 가지고 있습니다. 배열 전체의 크기를 계산할 수 있습니다.
6. 재할당 가능 여부
	1. 포인터 변수는 다른 메모리 주소를 가리키도록 할당할 수 있습니다.
	2. 배열 변수는 다른 메모리로 재할당 할 수 없습니다. 고정된 포인터 변수와 같습니다.

