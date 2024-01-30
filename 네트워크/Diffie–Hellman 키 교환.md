교환법칙이 성립하고 역산이 어려운 연산의 군을 이용해 암호키를 교환하는 방식.
최초의 공개 값$v$를 서로 공유한 상태에서 각자의 비밀값$a, b$을 연산한 뒤 교환하고 교환 받은 값을 다시 연산하여 공통의 암호키$k$를 생성함.
통상적인 경우 $(\mathbb{Z}_p,\exp)$ (단, $p$ 는 소수) 군을 사용하나 [[Elliptic-curve Diffie–Hellman|ECDH]] 같은 경우 [[타원곡선]] 위에서


- [[Diffie-Hellman Ephemeral|DHE]]
- 

$$v, b, a \in (G, \circ)$$
$$A: v, B: v$$
$$A: v \circ a, B: v \circ b$$
$$\text{A, B 값 교환}$$
$$A: v \circ b, B: v \circ a$$
$$A: v \circ b \circ a, B: v \circ a \circ b$$
$$v \circ b \circ a = v \circ a \circ b$$
$$\text{따라서 A 와 B 는 같은 값을 갖게 됨}$$
