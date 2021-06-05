# DesignPatterns
저의 첫 디자인 패턴 개인 공부 공간입니다.

교재 : Head First Design Patterns (에릭 프리먼, 엘리자베스 프리먼, 케이시 시에라, 버트 베이처 / 서환수 역)

언어 : JAVA

## 공부를 시작하며...
프로그래밍 수업을 들을 때 교수님들께서 디자인 패턴의 중요성을 언급하셨었다. 당시에는 그냥 중요하구나 라고만 생각을 하는 정도였다.
그러다 다른 언어로 프로젝트를 했었을 때 필요성을 느꼈다. 그리고 현재 교육과정에서 자바를 배우고 있으며 나중에 프로젝트를 할 때 필요할 것 같아 미리 공부하기로 했다.
내가 선택한 'Head First Design Patterns'는 자바 언어를 사용하며, 많은 사람이 초심자들이 공부하기에 좋은 책으로 추천하여 선택하였다. (나도 Head First Python을 읽었는데 아주 좋았던 기억 때문에 의심치 않는다)

끝까지 완독하여 디자인 패턴이 어떤 거구나 감을 익히는 것을 목표로 하겠다.

## Strategy Pattern (스트래티지 패턴)
알고리즘군을 정의하고 **각각을 캡슐화하여 교환해서 사용**할 수 있도록 만든다. 스트리태지을 활용하면 알고리즘을 사용하는 **클라이언트와는 독립적**으로 알고리즘을 변경할 수 있다.

- 애플리케이션에 달라지는 부분을 찾아 내고, 달라지지 않는 부분으로부터 분리 시킨다. (캡슐화)
- 구현이 아닌 인터페이스에 맞춰서 프로그래밍한다.
- 상속보다는 **구성**을 활용한다.

