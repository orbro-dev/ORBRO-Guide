---
description: >-
  Nearby Search는 등록된 Tag가 얼마나 감지되고 있는지 날짜별로 분석하는 애플리케이션입니다. 선택한 날짜를 기준으로
  Detection Rate, Registered Tag, Detected Tag, Undetected Tag를 확인하고, 시간대별 감지
  흐름과 TwinTracker 또는 Tag 기준 상세 결과를 함께 분석할 때 사용합니다.
---

# Nearby Search

### 메뉴 위치

* `애플리케이션` > `Nearby Search`

***

### 사용 전에 확인해 주세요

* 등록된 Tag 데이터가 있어야 분석 결과를 확인할 수 있습니다.
* Nearby Search는 감지 이력이 누적되어야 의미 있는 결과를 보여줍니다.
* 날짜별 비교와 시간대별 추이를 함께 보면 감지 상태를 더 정확하게 파악할 수 있습니다.

***

### 이런 때 사용합니다

* 등록된 Tag 중 실제로 얼마나 감지되고 있는지 확인하고 싶을 때
* 특정 날짜의 감지율과 미감지 수량을 확인하고 싶을 때
* 시간대별로 감지 수량이 어떻게 달라지는지 보고 싶을 때
* `TwinTracker`별 또는 `Tag`별 상세 감지 현황을 비교하고 싶을 때

***

### 주요 메뉴와 화면

* `날짜 목록`: 화면 왼쪽에서 날짜별 요약 정보를 확인합니다. 각 날짜 카드에는 `Detected Tag`, `Undetected Tag` 수가 함께 표시됩니다.
* `상단 요약 정보`: 선택한 날짜를 기준으로 `Date`, `Detection Rate`, `Registered Tag`, `Detected Tag`, `Undetected Tag`를 확인합니다.
* `Detection Rate`: 등록된 Tag 중 실제로 감지된 Tag 비율을 의미합니다.
* `시간대별 감지 그래프`: 선택한 날짜의 시간대별 감지 수량 변화를 그래프로 확인합니다.
* `TwinTracker` 탭: 각 TwinTracker 장비별 감지 현황을 확인합니다. 카드에는 장비 이름, MAC Address, Device Type, Location Info, 시간대별 감지 그래프가 표시됩니다.
* `Tag` 탭: Tag 기준으로 상세 감지 현황을 확인합니다.
* `필터`: 상단 드롭다운에서 전체 또는 특정 조건을 선택해 결과를 좁혀 볼 수 있습니다.

***

### 기본 사용 흐름

1. `Nearby Search`를 실행합니다.
2. 화면 왼쪽 날짜 목록에서 조회할 날짜를 선택합니다.
3. 상단 요약 영역에서 `Detection Rate`, `Registered Tag`, `Detected Tag`, `Undetected Tag`를 확인합니다.
4. 시간대별 감지 그래프를 보며 감지 수량이 높거나 낮은 구간을 확인합니다.
5. `TwinTracker` 탭에서 장비별 감지 현황을 확인하거나, `Tag` 탭에서 Tag 기준 결과를 확인합니다.
6. 필요하면 필터를 적용해 특정 기준의 결과만 다시 확인합니다.

***

### 참고해 주세요

* `Detected Tag`와 `Undetected Tag`를 함께 봐야 현재 감지 상태를 더 정확하게 이해할 수 있습니다.
* `Detection Rate`가 낮게 보이면 특정 시간대나 특정 장비에서 감지가 줄어든 구간이 있는지 함께 확인하는 것이 좋습니다.
* `TwinTracker` 탭에서는 장비별 감지 분포를 비교할 수 있어, 장비별 수집 상태를 점검할 때 도움이 됩니다.
