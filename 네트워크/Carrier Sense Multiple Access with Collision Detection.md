---
aliases:
  - CSMA/CD
---
[[유선 LAN]]에서 충돌을 피하기 위해 사용*했었던* 방식
- Carrier Sense Multiple Access
	- 데이터 전송 전 회선 사용 여부 감지 후 전송 시작
	- 여러 단말이 동시에 보내 충돌이 일어나지 않도록 하기 위한 수단
- Collision Detection
	- 만약 충돌이 일어났다면 두 장비 모두 랜덤한 시간 이후 다시 전송

**현재는 안 씀**.
예전에는 [[유선 LAN]]이 대부분 [[Bus Topology]]로 구성됐었기 때문에 이런 절차가 필요했음.
그러나 현대 유선 LAN은 대부분 [[Switching|스위치]]를 중심으로 한 [[Star Topology]]로 구성되어있고, 단말과 스위치가 [[Full Duplex|전이중화 통신]]이 가능하기 때문에 필요가 없어짐.

#설명/과정 #네트워크 