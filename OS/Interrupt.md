---
aliases:
  - 인터럽트
---
기존에 실행중인 [[Central Processing Unit|CPU]]에서 실행되는 프로세스를 중지시키는 행동

## 인터럽트 핸들러 함수

인터럽트를 처리하기 위한 함수
[[Kernel|커널]] 내부 [[Interrupt ReQuest]]통해 호출됨

인터럽트 발생 시 인터럽트 벡터에서 인터럽트 핸들러 함수 실행
우선순위에 따라 인터럽트 실행

## 구분
- [[하드웨어 인터럽트]]
- [[소프트웨어 인터럽트]]