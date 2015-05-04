Jnode Framework
======
Node 기반의 Front-end 개발 프레임워크이다. HTML element node와 JavaScript hierarchical object node 단위로 개발을 할 수 있다. 단순히 HTML 소스들을 쪼개서 Include하고, 실제 Client로부터의 요청시마다 전체 페이지가 합쳐져서 네트워크를 통해 매번 내려오는 비효율적인 방식이 아니라, 실제로 필요한 Node만 요청을 하고 해당 Node를 위한 Template 파일과 JavaScript 파일, CSS 파일들이 렌더링되어 진다.

![Alt Jnode Framework architecutre](images/jnode_architecture.png?raw=true "Jnode Framework architecutre")

> 비대해진 프레임워크(Heavy framework)로 인해 피로도가 높아진 개발자들을 위해 가벼운 프레임워크(Thin framework)을 제공한다.

> 무늬뿐인 HTML5을 따르는 개발 환경이 아니라, 진정한 HTML5 권고안에 충실한 개발 환경을 구축해 준다.

> 다양한 Template engine들을 플러그인처럼 add-on할 수 있다.

> Template 파일로부터 JavaScript 파일, CSS 파일들을 분리하기 위한 최적화된 방법을 제시해 준다.

> HTML Controller, JavaScript Module 등 편리 라이브러리들을 제공하여 보다 쉽게 개발을 할 수 있다.

> +back-end 추가 패키지를 통해 JEE Server 환경의 data를 binding하여 Front-end에서 사용할 수 있다.

### 사용 가이드
Jnode Framework의 자세한 사용법은 아래의 Jnode Framework 공식 사이트를 참조하기 바란다.

[http://jnode.jeasu.kim](http://jnode.jeasu.kim/)

### 사용 환경
Jnode Framework는 HTML5를 지원하는 Web Application을 개발하기 위한 Front-end 개발 프레임워크이다. Back-end 환경이 JEE Servlet 3.0 이상이라면 +back-end 추가 패키지를 통해 JEE Server 환경의 추가 기능들을 사용할 수 있다. JEE Servlet 3.0 이하의 환경이라면 제공되는 소스를 통해 직접 구축할 수도 있다.
