---
aliases:
  - 페이지 폴트
  - 페이지 부재
---
[[주기억장치]]에 존재하지 않는 페이지를 참조하는 경우 발생하는 예외

## 처리 방법
1. [[Central Processing Unit|CPU]]가 [[실제 주소|물리 주소]] 확인 후 페이지 부재 시 [[소프트웨어 인터럽트|트랩]]을 발생
2. [[Operating System|OS]]가 [[Central Processing Unit|CPU]] 일시 정지
3. [[Operating System|OS]]가 [[Page Table|페이지 테이블]]을 확인해 [[가상 메모리]]에 페이지 존재 여부 확인
4. 없을 시 [[Process|프로세스]] 중단 후 물리 메모리에 비어있는 프레임 확인
5. 빈 프레임 없다면 [[Swapping|스와핑]] 발동
6. 비어있는 프레임에 페이지 로드
7. 페이지 테이블 갱신
8. [[Central Processing Unit|CPU]] 재개