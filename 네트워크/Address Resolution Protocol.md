---
aliases:
  - ARP
---
네트워크 상에서 [[IP Address|논리적 네트워크 주소]]를 [[MAC Address|물리적 네트워크 주소]]로 대응(bind)시키기 위해 사용되는 [[Protocol|프로토콜]].
RARP(Reverse ARP): 역으로 물리적 네트워크 주소를 논리적 네트워크 주소로 바꾸는 프로토콜

1. 송신 호스트가 알고 싶은 논리적 주소를 담은 ARP Request를 [[Broadcast|브로드캐스트]]
2. 수신 호스트의 논리적 주소가 ARP Request 속 주소와 일치하면 자신의 물리적 주소를 담아 ARP Request 송신 호스트에게 ARP Reply를 [[Unicast|유니캐스트]]

#설명/용어 #네트워크/프로토콜 