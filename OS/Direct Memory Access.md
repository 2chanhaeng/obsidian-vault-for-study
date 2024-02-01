---
aliases:
  - DMA
  - 직접 메모리 접근
---
[[Central Processing Unit|CPU]] 개입 없이 [[Memory|메모리]]에 직접 접근할 수 있는 기능
## 동작 방식
1. **요청(Request):** 외부 장치 또는 입출력 장치가 데이터 전송을 요청
2. **허가(Grant):** [[DMA Controller|DMA 컨트롤러]]가 CPU에게 데이터 전송 요청, CPU는 승인
3. **메모리 접근(Memory Access):** DMA 컨트롤러가 직접 메모리에 접근해 데이터 전송
4. **전송 완료(Completion):** 데이터 전송이 완료 후 DMA 컨트롤러는 CPU 완료 알림 인터럽트
