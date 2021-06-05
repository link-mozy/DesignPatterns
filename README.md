# DesignPatterns
저의 첫 디자인 패턴 개인 공부 공간입니다.

교재 : Head First Design Patterns (에릭 프리먼, 엘리자베스 프리먼, 케이시 시에라, 버트 베이처 / 서환수 역)

언어 : JAVA

## 공부를 시작하며...
학창 시절 프로그래밍 수업에서 디자인 패턴은 꼭 알아둬야 한다고 들었으나, 당시 "중요한 거구나"라고만 생각을 하고 넘어갔었다.

하지만, 계속 개발 공부를 하다 보니 필요성을 느꼈고 "SSAFY" 교육을 들으면서 나중에 프로젝트에서 필요할 것 같아 미리 공부하기로 했다.

책을 보며 공부하기로 했으며, 선택한 책은 'Head First Design Patterns'이다. 선택한 이유는 자바 언어를 사용하며, 여러 사람이 초심자가 공부하기에 좋은 책으로 추천해서이다. (그리고, Python을 'Head First Python'으로 공부하였는데, 개인적으로 매우 훌륭하다고 생각해서 더 신뢰가 간다)

끝까지 완독하여 디자인 패턴이 어떤 거구나 감을 익히는 것을 목표로 하겠다.

## Strategy Pattern (스트래티지 패턴)
알고리즘군을 정의하고 **각각을 캡슐화하여 교환해서 사용**할 수 있도록 만든다. 스트리태지을 활용하면 알고리즘을 사용하는 **클라이언트와는 독립적**으로 알고리즘을 변경할 수 있다.

- 애플리케이션에 달라지는 부분을 찾아 내고, 달라지지 않는 부분으로부터 분리 시킨다. (캡슐화)
- 구현이 아닌 인터페이스에 맞춰서 프로그래밍한다.
- 상속보다는 **구성**을 활용한다.

