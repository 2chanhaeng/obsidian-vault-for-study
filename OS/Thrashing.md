---
aliases:
  - 스레싱
---
[[Page Fault|페이지 폴트]] 비율이 높은 상태
컴퓨터의 심각한 성능 저하 초래
동시에 메모리에 다량의 프로세스가 올라가 [[Swapping|스와핑]]이 반복적으로 일어나 발생
잦은 페이지 폴트 발생 → [[Central Processing Unit|CPU]] 이용률 저하 → [[Operating System|OS]]가 가용성을 높이기 위해 메모리에 더 많은 프로세스 올림 → 더 많은 페이지 폴트 발생 → ...
## 해결 방법

- 메모리 증량
- [[Hard Drive|HDD]]를 [[Solid State Disk|SSD]]로 변경
### OS 단의 해결법

- [[Working Set|작업 세트]]
- [[Page Fault Frequency|PFF]]