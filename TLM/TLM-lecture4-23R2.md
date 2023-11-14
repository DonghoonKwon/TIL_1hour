# 교통물류경영(23R2)

## Lecture 4. Facility-Department Layout Planning

- 지금까지 경로 최적화와 입지 최적화 (VRP, location)등을 했다면 이제 location이 된 건물 안에 설비들을 어떻게 놓는것이 최적일지 고민해보는 파트
- 설비입지와 배치 중 배치를 보는 단계

- 참고: 산업공학개론, 한상찬, 형설출판사

## Topic 1: Layout planning basic

### Facility layout
- 새로운 facility를 만든다.
- 장비가 교체, 추가 될때
- 물류와 생산품의 자동화
- 컨베이어 장비의 변화
- 생산 물품의 변화
- 신기술 및 장비로 인한 절차 변화
- 비용감소가 필요할 때
- 안전 관련 기준 강화(안전사고)
- 작업환경 개선

### Layout planning의 6가지 원리
- Principle of `overall integration`: 물류창고, 작업자 공간, 휴식공간, 사무실 등을 종합적으로 고려할 수 있어야함
- Principle of `minimum material flow cost`: 기계와 장비들은 결국 이동간에 발생하는 시간(비용)을 최소화하는 쪽으로 가야함
- Principle of `flow`: input과 ouput의 흐름이 정해져서 생산 흐름이 결정이 되어야함. 이때 뒤로 가거나 막히는 걸 없애야함
- Principle of `cubic space`: 공간의 낭비를 줄이기 위해 3차원으로 공간활용할 수도 있음. 결국 물류비용 감소 목적
- Principle of `satisfaction and safety`: 작업자들의 환경 또한 고려되어야함
- Principle of `flexibility`: layout이 변경되는 일이 있더라도 융통성있게 바뀔 수 있게 해야함


## Topic 2: Systematic layout planning(SLP)

### SLP의 전반적 절차
1. 분석 단계
    - 물자흐름 (양적)
    - 활동 관련 (질적)
    - 물자흐름~활동 관련도
    - ~
    - 필요 공간
    - 가용 공간
2. 탐색 단계
    - 공간 관련도
    - ~
    - 수정 고려사항
    - 실질적 제한사항
    - ~
    - layout 대안

3. 선택 단계
    - 평가

절차 하나하나 봅시다.


### 입력자료 및 활동의 기초요소 PQRST

- 요소
    - Product: 무엇을 만들지
    - Quantity: 각각 얼마나 만들지?
    - Routine: 어떤 순서로 만들지?
    - Service: 물품에 맞게 준비해야하는 기능
    - Timing: 기한 관련

- 단위기간 생산량 내림차순으로 나타내기

### 물자 흐름
- Material flow: Group A,B,C로 나눠서 살펴보기
    - 결국 각각의 물품들의 흐름을 보고싶음... 중요하니까! 
    - A[소품종 대량생산]: 많이 생산하는 몇가지 물품들 / operation process chart 활용 <-- 무슨 차이임?
    - B[중품종 중량생산]: 적당한 생산량 / multi-product process chart 활용 / 5~8물건
    - C[다품종 소량생산]: 적은 생산량 / From-to chart 활용, 유입유출표
