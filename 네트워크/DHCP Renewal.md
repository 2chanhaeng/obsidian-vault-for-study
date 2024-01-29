---
aliases:
  - DHCP 갱신
---
단말이 [[DHCP Server|DHCP 서버]]에게 기존에 할당 받은 [[IP Address|IP 주소]]를 다시 사용하기 위해 갱신받는 과정
1. 단말이 서버에게 IP 주소 할당을 [[Unicast|유니캐스트]]로 [[DHCPREQUEST|요청]]
2. 단말이 서버에게 요청한 IP 주소가
	- 사용 불가능한 경우 [[DHCPNAK|비승인]]
	- 사용 가능한 경우 [[DHCPACK|승인]]

#설명/과정 #네트워크/DHCP 