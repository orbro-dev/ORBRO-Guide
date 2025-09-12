---
description: ORBRO OS에서 Camera 단말기를 등록하려면 다음의 절차를 따르세요.
---

# Camera 단말기

## 기능 개요

Camera 단말기 등록 기능은 ORBRO OS에서 실시간 영상 기반 위치 추적 기능을 제공하기 위한 카메라를 시스템에 등록하는 절차입니다.

등록된 카메라는 AI 기반 객체 감지 및 위치 추적 시스템과 연동되어, 사람·차량·버스 등의 움직임을 감지하고 시각적으로 표현하는 데 활용됩니다.



***

## 사용 방법

#### 1. 기기 관리 화면으로 이동&#x20;

1. 화면 우측 상단의 프로필 아이콘 왼쪽에 위치한 창문 아이콘을 클릭합니다.
2. 컨텍스트 메뉴가 열리면, \[Setting] 항목을 클릭하여 설정 팝업을 엽니다.
3. 좌측 메뉴에서 \[기기] 항목을 클릭합니다.
4. 상단의 탭 중 \[Camera] 탭을 선택합니다.

<figure><img src="../../.gitbook/assets/setting user - 16.png" alt=""><figcaption></figcaption></figure>

#### 2. Device Type 선택&#x20;

* Device Type 필드에서 해당 카메라의 유형을 선택합니다.
  * 일반적인 실내 카메라는 IP Camera로 등록합니다.
  * Fisheye Lens Camera는 어안렌즈 기반의 카메라로, 특히 Fisheye Lens Camera는 이후 Camera Mapping 방식이 달라지므로 등록 후 수정이 불가능합니다.

{% hint style="warning" %}
**주의** : Fisheye Lens Camera로 등록하면 전용 맵핑 기능이 적용되므로, 정확한 타입 선택이 필수입니다.
{% endhint %}

<figure><img src="../../.gitbook/assets/setting user - 21.png" alt=""><figcaption></figcaption></figure>

#### 3. 기본 정보 입력

다음 입력 필드에 카메라 정보를 입력합니다:

* Device Name: 카메라 이름
* IP Address: 카메라가 연결된 네트워크 주소
* Port: 영상 스트리밍에 사용되는 포트 번호
* URL: 영상 스트리밍 URL



#### 4. 계정 정보 입력(선택사항)

* ID / Password 필드는 선택 입력 항목입니다.
* 계정이 필요한 카메라에만 입력하며, 공개형 카메라라면 입력하지 않아도 됩니다.

<figure><img src="../../.gitbook/assets/setting user - 23.png" alt=""><figcaption></figcaption></figure>

#### 5. 기기 등록 완료&#x20;

* 모든 필드를 입력한 후, \[추가] 버튼을 클릭하면 카메라 기기 등록이 완료됩니다.



{% hint style="success" %}
**참고 사항**

카메라 등록 후 AI 기반 위치 추적 기능을 사용하려면 다음의 추가 설정이 필요합니다:

* Camera Mapping
* Region of Interest 설정
{% endhint %}

