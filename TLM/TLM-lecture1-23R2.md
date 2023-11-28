# 교통물류경영(23R2)

## Lecture 1. Location Theory

- 입지 선정 문제

## Topic 1: Location Optimization Theory and Basic Features



## Categories of Location Theory

- P-median problem
    - (목적함수) 수요가중거리 합 최소화
    - (결정변수) 입지여부, assign여부
    - (제약식) 전체 개수는 P개, 입지가 안 되었을 때 assign되면 안됨, binary

- Set covering problem
    - (목적함수) 고정 건설비용 최소화
    - (결정변수) 입지여부
    - (제약식) 고객은 최소 하나 이상의 서비스를 받아야함, binary
- Maximal covering problem
    - (목적함수) cover가 된 수요 양
    - (결정변수) 입지여부, cover여부
    - (제약식) 최대 P개, 어느 한 고객의 커버 여부에 1이 들어온다는 뜻은 입지된 개수가 1 이상이어야함, binary
- P-center problem
    - (목적함수) 가장 멀리 떨어진 거리 최소화
    - (결정변수) 입지여부, assign여부
    - (제약식) 전체 개수는 P개, 입지가 안 되었을 때 assign되면 안됨, 고객은 반드시 하나의 시설로만 assign, 고객 노드들에 대해서 assign받는 노드들의 시설까지의 거리는 D와 같거나 작음, binary