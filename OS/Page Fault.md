---
aliases:
  - 페이지 폴트
  - 페이지 부재
---
[[주기억장치]]에 존재하지 않는 페이지를 참조하는 경우 발생하는 예외

## 처리 방법
1. [[Central Processing Unit|CPU]]가 [[실제 주소|물리 주소]] 확인 후 페이지 부재 시 [[소프트웨어 인터럽트|트랩]]을 발생
2. [[Operating System|OS]]가 [[Central Processing Unit|CPU]] 일시 정지
3. [[Operating System|OS]]가 [[Page Table|페이지 테이블]]을 확인해 [[가상 메모리]]에 페이지 존재 확인
4. 