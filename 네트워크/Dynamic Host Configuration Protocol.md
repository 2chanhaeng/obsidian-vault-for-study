---
aliases:
  - DHCP
  - 동적 호스트 구성 프로토콜
---
[[IP Address|IP 주소]] 및 기타 통신 매개변수 자동 할당 네트워크 관리 [[Protocol|프로토콜]]

```mermaid
```

## 과정
여기서 서버란 DHCP를 통해 망 내부 IP 주소를 할당하는 DHCP 서버를 뜻함
1. Discover
	- 단말 → 서버, [[Broadcast|브로드캐스트]]
	- IP 주소 할당 요청
2. Offer
	- DHCP 서버 → 단말, 브로드캐스트 혹은 [[Unicast|유니캐스트]]
	- 단말의 요청에 대한 DHCP 서버의 응답
	- 제안할 IP 주소를 예약해두고 단말에게 해당 주소를 사용할 것인지를 제안
	- 단말 식별자(주로 [[MAC Address|MAC 주소]]), 제안할 IP 주소, [[Subnet Mask|서브넷 마스크]], 임대 기간, 응답을 보내는 서버의 IP 주소
3. Request
	- 단말 → DHCP 서버, [[Broadcast|브로드캐스트]]
	- 제안받은 IP 주소를 사용하겠다고 수락
	- 망 내에 여러 서버가 존재해 여러 제안을 받았을 경우 하나의 IP만 사용하기 위한 과정
4. Acknowledgement (Ack)
	- DHCP 서버 → 단말, 브로드캐스트 혹은 [[Unicast|유니캐스트]]
	- 단말의 MAC 주소에 제안했던 IP 주소와 게이트웨이 주소를 확정
	- 만약 다른 단말에서 이미 해당 IP를 사용하는 경우 Decline 을 보내야함
- Decline
	- 서버와 임의의 단말이 IP 할당 과정에서 이미 사용하는 IP 주소를 할당하려는 경우, 사용 중이던 단말이 해당 IP 주소가 사용 불가능함을 알리는 내용