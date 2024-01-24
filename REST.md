REpresentational State Transfer
구체적으로 사용할 `리소스/자원`을 명시하는 웹 앱 구조의 설계 방식

[실제 REST 의 정의](https://en.wikipedia.org/wiki/REST)는 알려진 것보다 추상적이다.
통상적으로 알려진 RESTful 한 API, REST API 는 다음과 같은 조건에 맞춰 설계한다.

1. 균일화된 인터페이스
   기기, OS, 언어 등 플랫폼에 종속받지 않고 사용 가능
2. 스스로를 명시(Self-Descriptive)
   주고 받는 데이터 만으로도 행위에 대해 직관적으로 이해할 수 있도록
3. 상태를 저장하지 않음(Statelessness)
   맥락을 알지 못 해도 되므로 구현이 단순
4. `리소스/자원` 위주의 구조
   `리소스/자원` 자체가 중심이 되는 명사 위주의 정의를 권장

#설명/용어
