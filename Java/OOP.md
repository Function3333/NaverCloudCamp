## 


### 1. OOP(Object Orinted Programming)
- 현실세계를 구현하기 위한 프로그래밍 방식이다.

### 2. Objcet(객체)
- 우리가 일상생활에서 마주치는 모든 것들이 객체이다

### 3. abstraction(추상화)
- 객체의 attribute와 behavior를 정의하는 과정이며 객체의 attribute와 behavior는 domain, 즉 구현하는 영역에 따라 다르게 정의될 수 있다..

### 4. Encapuslation(캡슐화)
- 우리가 낯선 사람을 보고 바로 그 사람의 이름과 주민등록번호를 알 수 없듯이 oop에서도 객체를 구현한 class의 필드에 바로 접근하면 안 된다. 따라서 객체를 class로 만들기 전에
어떤 정보를 공개하고 어떤 정보를 숨길지를 결정하는 캡슐화 작업이 필요하다. 

### 5. class(클래스)
- 추상화, 캡슐화 단계를 거쳐 객체의 attribute와 behavior를 field, behavior로 변환하여 정의한 것이 class이다.

### 6. instantiate(인스턴스화)
-  class를 메모리에 올려 실제로 만들어내는 과정이다.

### 7. Relationship(관계)
- 위 과정을 거쳐 만들어진 클래스들은 서로 관계를 맺을 수 있다.

### 8. Generalization(일반화)
- 여러 클래스에서 공통된 필드와 메스들을 추출하여 새로운 클래스를 만들 수 있다 이렇게 클래스를 만드는 과정을 Generalization이라 하며 Generalization을 통해 만들어진 클래스는
하위 클래스에서 필드와 메서드를 공유하며 ~ is a ~라는 관계가 성립하고 계층이라는 관계가 생긴다.

### 9. Specialization(구체화)
- 상위 클래스에서 공유 받는 필드와 메서드를 포함하여 더 세부적인 필드와 메서드를 만드는 것이 구체화이다. 

### 10. Hierarchy(계층화)
- 일반화와 구체화를 통해 계층이라는 구조가 생성된다. 이렇게 생성된 계층에 따라 받을 수 있는 크기가 달라진다. 동물과 사람이라는 클래스가 있을 때 동물이 더 일반화된 클래스이고 사람은 동물의 
속성과 행동을 가지는 구체화한 클래스이다. 계층화된 클래스도 primitive 데이터타입처럼 크기를 가지며 일반화 된 클래스가 더 큰 크기를 가진다. 따라서 일반화 된 클래스는 구체화 된 클래스를 묵시적 형 변환을 통해
데이터를 담을 수 있지만, 구체화 된 클래스가 일반화 된 클래스를 담으려면 명시적 형 변환을 통해 데이터를 담아야 한다.

### 11. Polymorphism(다형성)
- 앞의 계층구조에서 언급한 것처럼 일반적인, 즉 상위의 클래스는 다양한 하위 클래스를 받아서 그들이 구체화한 기능들을 사용할 수 있으며, java method의 overLoadding 기능도
하나의 같은 이름을 가지는 메서드를 호출을 통해 다양한 값을 넣어 원하는 결과 값을 받을 수 있다 이러한 기능이 다형성을 지원하는 방식이고 다형성을 통해 클래스들을 쉽게 관리 가능하다

### 12. Realization(실체화)
- 상속받은 공통의 속성을 구현하는것 

### 13. Association(연관성)
- 하나의 객체가 다른 객체를 필드로 소유하는 형태이며 has a 관계가 성립한다

### 14. dependency(의존성)
- 객체가 다른 객체를 사용하는 형태이다.
