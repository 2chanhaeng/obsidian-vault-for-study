---
aliases:
  - QUIC
---
[[TCP]]를 대체하기 위해 [[UDP]]를 기반으로 만들어진 [[전송 계층]] [[Protocol|프로토콜]].

[[Transport Layer Security|TLS]] 지원.

첫 연결 설정에 1-[[Round-Trip Time|RTT]]만 소요.

[[Forward Error Correction|FEC]] 적용.
전송 중 패킷 손실 되어도 수신 측에서 검출 및 수정 가능.

구글이 개발을 시작해서 현재는 IEEE 표준 RFC9000으로 등록됨.
QUIC라는 이름은 처음에 *Quick UDP Internet Connections*의 약어로 제시됐지만 그냥 QUIC 라는 고유명사로 지정됨.