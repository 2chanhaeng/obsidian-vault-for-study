---
aliases:
  - DHCP 임대
---
1. [[DHCPDISCOVER|Discover]]
2. [[DHCPOFFER|Offer]]
3. 단말이 제안 받은 [[IP Address|IP 주소]]에 [[Address Resolution Protocol|ARP]]를 시도
	- 응답이 없을 경우 사용 가능한 IP 주소로 판단하고 [[DHCPREQUEST|Request]]
	- 응답이 올 경우 이미 사용 중인 IP 주소로 판단하고 [[DHCPDECLINE|Decline]]
4. [[DHCPACK|Acknowledgement]]