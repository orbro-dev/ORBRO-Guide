---
description: >-
  TwinTracker 관리는 등록된 TwinTracker 장비를 확인하고, 필요한 장비를 추가하며, 화면에 표시되는 정보 구성을 조정하는
  페이지입니다. 위치 기반 서비스를 안정적으로 운영할 때 장비 상태를 먼저 확인하는 데에 자주 사용합니다.
---

# TwinTracker 관리

### 메뉴 위치

* `애플리케이션` > `Device Manager` > `TwinTracker`

***

### TwinTracker 관리에서 할 수 있는 일

* 등록된 TwinTracker 목록 확인
* 장비별 온라인 상태 확인
* 장비 유형 확인
* MAC Address, 연결 방식, IP 정보 확인
* Primary / Secondary Address와 Port 확인
* LED Color, H/W Version, 설치 위치, 마지막 연결 시간 확인
* 필터와 컬럼 구성을 바꿔 필요한 정보만 보기
* 추가 가능한 TwinTracker 장비 선택 후 등록

***

### 화면 구성

#### 상단 도구

* `검색`: 등록된 TwinTracker를 이름이나 식별 정보로 빠르게 찾을 수 있습니다.
* `보기 설정`: 필터와 컬럼 구성을 바꿀 수 있습니다.
* `기기 추가`: 등록 가능한 TwinTracker를 선택해 목록에 추가할 수 있습니다.

#### TwinTracker 목록

* 기본 목록에서는 `Device Name`, `Status`, `Device Type`, `MAC Address`, `Connection`, `IP Mode`, `IP Address` 등을 확인할 수 있습니다.
* 표가 넓기 때문에 가로로 이동하면 `Primary Address`, `Primary Port`, `Secondary Address`, `Secondary Port`, `LED Color`, `H/W Version`, `Location`, `Last Seen`까지 확인할 수 있습니다.
* `Status`를 보면 현재 장비가 온라인인지 빠르게 파악할 수 있습니다.
* `Location`과 `Last Seen`은 설치 위치와 최근 통신 시점을 점검할 때 유용합니다.

#### 기기 추가

* `기기 추가` 버튼을 클릭하면 추가 가능한 TwinTracker 목록이 열립니다.
* 추가 창에서는 한 번에 여러 기기를 선택할 수 있습니다.
* 추가 창 안에서도 검색과 필터를 사용할 수 있어 필요한 장비만 골라 등록할 수 있습니다.
* 선택을 마친 뒤 `추가`를 클릭하면 Device Manager 목록에 반영됩니다.

#### 보기 설정

* `보기 설정`에서는 필요한 정보만 골라 화면을 정리할 수 있습니다.
* `Filters` 탭에서는 `Device Type`, `Status`, `IP Mode` 기준으로 목록을 좁혀 볼 수 있습니다.
* `Columns` 탭에서는 화면에 표시할 항목을 직접 선택할 수 있습니다.

***

### 사용 방법

1. `TwinTracker` 페이지로 이동합니다.
2. 목록에서 `Status`, `Device Type`, `Location`, `Last Seen`을 먼저 확인합니다.
3. 필요한 경우 `보기 설정`에서 필터와 컬럼을 조정해 원하는 장비만 봅니다.
4. 새 장비를 등록해야 하면 `기기 추가`를 클릭합니다.
5. 추가할 장비를 선택하고 `추가`를 눌러 등록합니다.
6. 등록 후 장비가 목록에 표시되는지와 연결 상태가 정상인지 다시 확인합니다.

***

### 함께 보면 좋은 앱

* `Tag 관리`: 위치추적에 사용하는 Tag를 함께 관리할 수 있습니다.
* `AI RTLS`: 공간별 위치추적 환경을 구성할 때 함께 확인할 수 있습니다.

***

### 참고해 주세요

* TwinTracker 상태가 `Offline`이면 위치 기반 기능 운영에 영향을 줄 수 있으므로 상태를 먼저 확인해 주세요.
* 표가 넓게 구성되어 있으므로 필요한 항목이 보이지 않으면 가로 이동 또는 컬럼 설정을 함께 확인해 주세요.
* 설치 위치 정보가 실제와 다르면 운영 확인이 어려워질 수 있으니 장비 등록 후 `Location`도 함께 점검해 주세요.
