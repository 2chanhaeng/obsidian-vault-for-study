[[TCP]]단에서 일어나는 [[Head Of Line Blocking]]

TCP에서는 패킷의 순서를 보장하기 위해 순차적으로 주고 받게 됨.
중간에 손실이 일어나서 재전송하게 되면 이는 곧 후속 패킷들의 지연으로 이어지게 됨.
이를 TCP의 HOL Blocking이라고 함.

## 방지법
- [[CUBIC TCP|CUBIC]]
- [[Proportional Rate Reduction for TCP|PRR]]
- [[Bottleneck Bandwidth and Round-trip propagation time|BBR]]