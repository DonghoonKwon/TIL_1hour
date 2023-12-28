# 드론 배송과 관련된 문헌검토 내용입니다.

2023-11-16~

## Salama, M. R., & Srinivas, S. (2022). Collaborative truck multi-drone routing and scheduling problem: Package delivery with flexible launch and recovery sites. Transportation Research Part E: Logistics and Transportation Review, 164, 102788.

- 트럭과 드론을 이용한 배송
- 기존의 연구는 드론을 launch할 때 customer node에서 발사시켰지만 본 연구에서는 (굳이) customer node가 아니더라도 정해진 노드(selected truck stops) 어디에서라도 트럭을 발사시킬 수 있음
- 지금까지 확인된 내용
    - 트럭은 여러 대의 드론을 실을 수 있음
    - 드론이 s에서 발사되면 s+1에서 회수됨(되어야함)
    - 드론은 하나의 customer node만 들릴 수 있음
    - 배터리가 허락되는 한 어디든 갈 수 있음
- 목적함수: 모든 배송이 완료되는 데까지 걸린 시간(경과 시간)
- 성능 비교 지표
    - 배송 완료 시간의 평균 감소율
    - 트럭 대신에 드론으로 배송된 수(드론으로 배송된 수/드론이 배송가능한 지역 수) drone utilization
    - Flexible sites 중 truck stop으로 선택된 node 비율

    
- 궁금
    - depot와 가까운 지점에서 node select 되는게 무슨 의미지?


## Moadab, A., Farajzadeh, F., & Fatahi Valilai, O. (2022). Drone routing problem model for last-mile delivery using the public transportation capacity as moving charging stations. Scientific Reports, 12(1), 6361.

- 트럭과 버스를 이용한 화물수송
- 배터리 constraints를 고려함


## Meng, S., Guo, X., Li, D., & Liu, G. (2023). The multi-visit drone routing problem for pickup and delivery services. Transportation Research Part E: Logistics and Transportation Review, 169, 102990.

- 트럭과 드론을 동시에 이용한 화물수송
- 드론의 multiple customers 방문 고려
    이때 parcel의 무게를 고려함
- pickup and delivery
- 목적함수
    min total cost
- 방법론
    two-stage heuristic algorithm