# 용어 설명

## 워크스페이스 및 계정 관련

<table><thead><tr><th width="167.12890625">용어</th><th>설명</th></tr></thead><tbody><tr><td>워크스페이스(Workspace)</td><td>ORBRO OS의 프로젝트 단위 공간으로, 위치 추적 및 장비 관리가 이루어지는 독립된 운영 환경입니다.</td></tr><tr><td>워크스페이스 이름</td><td>각 워크스페이스를 구분하기 위해 사용자가 설정한 명칭입니다.</td></tr><tr><td>워크스페이스 로고</td><td>해당 워크스페이스를 대표하는 이미지로, 로그인시 표시됩니다.</td></tr><tr><td>네비게이션 로고</td><td>좌측 메뉴 상단에 표시되는 브랜드 또는 프로젝트 식별용 로고입니다.</td></tr><tr><td>Local Account</td><td>특정 워크스페이스 전용으로 생성된 로컬 사용자 계정입니다.</td></tr><tr><td>Orbro Account</td><td>ORBRO에서 제공하는 통합 사용자 계정으로, 여러 워크스페이스에서 공통 로그인 가능합니다.</td></tr></tbody></table>

## 위치 추적 및 모니터링 기능

<table><thead><tr><th width="167.12890625">용어</th><th>설명</th></tr></thead><tbody><tr><td>Zone (존)</td><td>객체의 출입을 감지하고 이벤트를 설정할 수 있는 가상의 공간 영역입니다.</td></tr><tr><td>In/Out Tracking</td><td>객체의 Zone 출입 여부를 실시간으로 추적하고 이벤트 로그로 기록하는 기능입니다.</td></tr><tr><td>Reverse Tracking (리버스 트래킹)</td><td>객체가 설정된 이동 방향과 반대로 이동(역주행)할 경우 이를 감지하여 알림을 제공하는 기능입니다. 특정 Zone(구역)에 대해 이동 방향을 사전에 설정해두면, 해당 구역에서 역방향 이동이 발생했을 때 이를 실시간으로 탐지할 수 있습니다</td></tr></tbody></table>

## 운영 시나리오 및 대시보드

<table><thead><tr><th width="167.12890625">용어</th><th>설명</th></tr></thead><tbody><tr><td>보드 (Board)</td><td>위치, 상태, 영상 등의 다양한 정보를 위젯 형태로 배치해 모니터링할 수 있는 사용자 대시보드입니다.</td></tr><tr><td>Heatmap (히트맵)</td><td>UWB Tag 디바이스 기반 객체의 이동 경로 및 체류 빈도를 시각적으로 표현하는 기능으로, Record Application에서 제공됩니다.</td></tr><tr><td>Record (기록)</td><td>UWB Tag 디바이스 객체의 위치 변화와 상태 데이터를 시간순으로 저장 및 조회할 수 있는 기능이며, Record Application에서 제공됩니다.</td></tr><tr><td>SOP (표준 운영 절차)</td><td>특정 조건 발생 시 자동으로 실행되는 사전 정의된 시나리오(알림, 명령, 인터페이스 동작 등)입니다.</td></tr></tbody></table>

## 영상 기반 추적 및 설정

<table><thead><tr><th width="167.12890625">용어</th><th>설명</th></tr></thead><tbody><tr><td>Region of Interest (ROI)</td><td>영상 내에서 이벤트 감지 또는 분석의 대상이 되는 관심 영역입니다.</td></tr><tr><td>Camera Mapping (카메라 매핑)</td><td>영상 기반 위치추적을 위해 **실내 도면(2D Map)**과 실제 CCTV 영상을 매칭시키는 기능입니다. 이 과정을 통해 객체가 도면 상 어느 위치에 있는지 직관적으로 확인할 수 있으며, 도면 상의 ROI(관심 영역)과 영상 위치를 연동하여 AI 분석 정확도를 높입니다.</td></tr><tr><td>Camera Categories (카메라 분류)</td><td>AI 영상분석 기능을 통해 **카메라가 인식하는 객체(예: 사람, 차량, 버스 등)**를 분류하는 체계입니다. 분류 가능한 카테고리는 시스템에서 사전에 제공하는 항목으로 한정되며, 사용자가 임의로 추가하거나 정의할 수 없습니다. 이는 AI 모델이 사전 학습한 객체 범위에 기반하기 때문입니다.</td></tr></tbody></table>

## 장비 구성요소 및 통신

<table><thead><tr><th width="167.12890625">용어</th><th>설명</th></tr></thead><tbody><tr><td>Tag (태그)</td><td>사람, 차량, 자산 등에 부착되어 실시간 위치 데이터를 송신하는 장비입니다.</td></tr><tr><td>Anchor (앵커)</td><td>Tag의 신호를 수신하여 위치 계산 기준점을 제공하는 장비입니다.</td></tr><tr><td>Sensor (센서)</td><td>온도, 습도, 움직임 등 다양한 환경 데이터를 수집하는 장비로, ORBRO OS와 연동하여 모니터링에 활용됩니다.</td></tr><tr><td>Access (액세스)</td><td>ORBRO에서 제공하는 출입 통제 전용 장비 시리즈를 의미하며, Access Lite / Access Auto / Access Pro 모델이 포함됩니다.</td></tr></tbody></table>
