---
description: ORBRO OS에서 조건알림 설정 방법을 알아봅니다.
---

# 조건 알림 설정

## 기능 개요

ORBRO OS에서는 다양한 이벤트에 따라 알림을 발생시킬 수 있는 기능을 제공합니다. 그중 조건 알림은 특정 상황 또는 값에 따라 알림을 발생시키는 방식으로, 사용자가 직접 조건을 구성하고 알림 메시지 및 알림 등급을 설정할 수 있는 커스터마이징 기능입니다.

조건 알림은 관제 상황에서 중요한 이벤트를 감지하거나, 특정 데이터 임계치를 모니터링하는 데 사용됩니다.



***

## 사용 방법

#### 1. 조건 알림 설정 화면 진입

1. 화면 우측 상단의 프로필 아이콘 왼쪽에 있는 창문 아이콘을 클릭합니다.
2. 컨텍스트 메뉴에서 \[Setting] 항목을 선택하여 설정 팝업을 엽니다.
3. 설정 팝업의 좌측 메뉴에서 \[알림]을 클릭합니다.
4. 상단 탭 중 \[조건 알림] 탭을 선택합니다.
5. 우측 상단의 \[알림 추가] 버튼을 클릭하면 조건 알림 추가 팝업이 호출됩니다.

<figure><img src="../.gitbook/assets/setting user - 27.png" alt=""><figcaption></figcaption></figure>

#### 2. Alarm Info 설정&#x20;

*   **Alarm Level: 알림의 중요도를 설정합니다.**

    선택 가능한 등급은 다음과 같습니다:

    Critical / Warning / Caution / Watch / Normal

<figure><img src="../.gitbook/assets/setting user - 28.png" alt=""><figcaption></figcaption></figure>

*   **Alarm Name: 생성할 알림의 이름을 입력합니다.**

    예시: 화재 감지, 이산화탄소 과다, 군중 밀집



#### 3. Alarm Message 설정&#x20;

*   **Display Target Name (스위치):**

    ON으로 설정하면 알림 메시지 앞에 {Target Name}에서가 자동으로 포함되어, 발생 위치를 쉽게 확인할 수 있습니다.
*   **Alarm Message:**

    알림 발생 시 사용자에게 전달될 메시지를 입력합니다.

    예시: 온도가 기준치를 초과했습니다.

<figure><img src="../.gitbook/assets/setting user - 29.png" alt=""><figcaption></figcaption></figure>

#### 3. Target Setting(대상 설정)

* Category: 감시할 장치 또는 그룹의 종류를 선택합니다. (예: Emergency Bell, Sensor 등)
*   Target: 해당 Category 내에서 알림을 발생시킬 대상을 선택합니다.

    ※ 복수 선택 가능



#### 4. Set Condition

*   Data Type: 알림을 트리거할 기준 데이터를 선택합니다.

    (예: 온도, 습도, 배터리 잔량 등 — 선택지는 Category에 따라 다름)
* Value: 알림 조건의 방식 선택
  * Reference Value: 특정 값에 대한 조건
  * Scope: 범위 조건
* 조건에 따라 입력 방식이 달라집니다:
  * Reference Value 선택 시:
    * Data Value: 기준값 입력
    * Comparison Operators: 비교 연산자 선택 (Equal, Greater Than, Less Than 등)
  * Scope 선택 시:
    * Minimum Value / Maximum Value 입력

<figure><img src="../.gitbook/assets/setting user - 30.png" alt=""><figcaption></figcaption></figure>



#### 5. Alarm Setting(반복 알림 설정)&#x20;

*   Enable Repeated Notifications (선택):

    동일한 조건이 반복 발생할 때, 알림을 일정 간격으로 재전송할 수 있도록 설정합니다.
* Interval: 반복 알림 간격 (단위: 분)

<figure><img src="../.gitbook/assets/setting user - 32.png" alt=""><figcaption></figcaption></figure>

#### 6. 저장&#x20;

모든 항목을 입력한 후 \[저장] 버튼을 클릭하면 조건 알림이 등록됩니다.



{% hint style="info" %}
**참고사항**

* 알림 조건은 실시간 관제, 환경 모니터링, 긴급 상황 대응 등 다양한 시나리오에 맞춰 자유롭게 구성할 수 있습니다.
* 알림 레벨에 따라 UI나 통보 방식이 다르게 처리될 수 있으므로, 중요도에 따라 적절한 등급을 설정하세요.
{% endhint %}
