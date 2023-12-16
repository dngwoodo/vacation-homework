# 블랙잭 게임

## 규칙

### 게임의 목표  

플레이어는 딜러와 대결하여 손의 총 합계가 21에 가장 가깝도록 카드를 뽑아야 합니다.  
21을 초과하면 즉시 패배합니다.

### 게임 규칙

- 딜러와 게이머 단 2명만 존재합니다.
- 52장의 카드가 존재합니다. 
  - 4가지 무늬(하트, 다이아몬드, 클럽, 스페이드) 각각에 13장의 카드(2에서 10까지의 숫자 카드, J, Q, K, A)가 포함되어 있습니다.
- 카드 셔플링: 게임 시작 전에 덱은 섞여야 합니다. 
  - 이는 카드가 무작위 랜덤임을 의미합니다.

- 딜러와 게이머는 순차적으로 카드를 한번씩 번걸아가며 뽑아서 각자 2개의 카드를 소지합니다.

- 딜러 혹은 게이머가 뽑은 카드의 합이 21을 초과하면 그 즉시 패배합니다.
  - 21을 초과하지 않는 동안에는 게이머는 계속해서 카드를 뽑을 수 있습니다.
  - 딜러는 2카드의 합계 점수가 16점 이하이면 반드시 1장을 추가로 뽑고, 17점 이상이면 추가할 수 없습니다.
- 게이머가 원하는 시점에 카드 점수를 계산할 수 있습니다.
- 카드 점수 계산
  - 숫자 카드(2-10)는 그 숫자 그대로 점수를 가집니다. 
  - J, Q, K는 10점으로 계산됩니다. 
  - **에이스(A)는 1점 또는 11점으로 계산될 수 있으며, 플레이어의 점수 합계가 21을 초과하지 않는 범위에서 최대한 높은 값**을 가집니다.
  - 카드를 오픈하면 딜러와 게이머 중 소유한 카드의 합이 21에 가장 가까운 쪽이 승리합니다.

## 요구사항

### 필수 요구 사항

- E2E 테스트 코드를 모두 통과해야 합니다.
- Lint, Prettier 를 따릅니다.
- PR에서 소나큐브 Review에서 모두 통과 되어야 합니다.
- `jest.mock` 등 Mocking은 사용해선 안됩니다.

### 선택 요구 사항

- 단위 테스트 등 본인이 필요한 테스트 코드는 얼마든지 추가해도 됩니다.
- 브랜치 커버리지 100%를 목표로 해도 좋습니다.

### 해야 될 것

- [] 테스트 코드 작성
- [] 소나큐브 확인
- [] type -> enum 으로 변경