---
description: APIM에 등록된 API의 로그 기능을 알아봅니다.
---

# Logging

SSO 인증을 이용하는 경우 아래의 사진과 같이 테넌트 변경을 진행하여 APIM 로깅을 확인을 위한 컨텍스트로 변경합니다. SSO 인증을 사용하지 않는 경우 이 단계를 건너뜁니다.

<figure><img src="../../.gitbook/assets/image (16) (1).png" alt=""><figcaption></figcaption></figure>

우측 상단 아이콘을 클릭하여 <mark style="background-color:blue;">Switch tenants</mark> 를 눌러 아래와 같은 팝업창을 불러옵니다.

<figure><img src="../../.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>

테넌트 선택 창에서 **private** 에 선택된 라디오 버튼을 **Choose from custom**으로 전환한 후**, \_apim\_tenant**로 끝나는 테넌트를 선택하고 <mark style="background-color:blue;">Confirm</mark>을 진행합니다.

테넌트가 전환이 되었다면, 좌측 메뉴에서 다음 단계를 진행합니다.

<figure><img src="../../.gitbook/assets/image (17) (1).png" alt=""><figcaption></figcaption></figure>

APIM의 로그를 확인하기 위해 Discover와 Dashboard를 알아봅니다.&#x20;
