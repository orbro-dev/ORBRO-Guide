---
description: ORBRO OS에서 Anchor 단말기를 등록하려면 다음의 절차를 따르세요.
---

# Anchor 단말기

## 기능 개요

Anchor 단말기는 ORBRO OS에서 BLE/UWB 신호를 수신하여 Tag 단말기의 위치를 계산하는 핵심 역할을 수행합니다.

ORBRO OS가 설치된 장비(ORBRO Server 또는 ORBRO Edge)에 Anchor 단말기를 물리적으로 연결하면, 시스템에서 해당 장치를 자동으로 인식하고 등록합니다.



***

## Anchor 단말기 등록 방식

Anchor 단말기는 수동 등록이 필요하지 않으며, ORBRO OS가 설치된 장비에 장치를 연결하면 시스템이 자동으로 등록을 처리합니다.



### 등록 조건

* Anchor 단말기가 ORBRO OS가 설치된 서버 또는 엣지 장비에 물리적으로 연결되어 있어야 합니다.
* 연결 후, 기기 관리 화면의 \[Anchor] 탭에서 자동 등록된 Anchor 목록을 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/setting user - 15.png" alt=""><figcaption></figcaption></figure>

### Anchor 단말기 종류

현재 ORBRO OS에서 지원하는 Anchor 단말기 유형은 다음과 같습니다:

* TwinTracker BLE
* TwinTracker UWB



### &#x20;확인 방법&#x20;

Anchor 단말기 연결 후 등록 여부는 아래 경로에서 확인할 수 있습니다:

1. 화면 우측 상단의 프로필 아이콘 왼쪽에 있는 창문 아이콘 클릭
2. \[Setting] > \[기기] 선택
3. 상단 탭 중 \[Anchor] 탭 클릭
4. 등록된 Anchor 목록 확인



{% hint style="info" %}
**참고사항**

* Anchor 단말기가 정상적으로 등록되지 않는 경우, 연결 상태나 장비 전원을 점검해 주세요.
* Anchor 단말기는 실시간 위치 계산의 기준이 되는 중요한 장치로, 설치 위치와 방향 설정이 정확해야 합니다. 관련 내용은 설치 가이드를 참고하세요.
{% endhint %}
