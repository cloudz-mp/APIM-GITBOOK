---
description: APIM 콘솔 기본 사용에 대하여 알아봅니다.
---

# APIM 콘솔 시작하기

## APIM 콘솔

### Gateway 관리

#### 게이트웨이 생성

APIM에서는 1개의 프로젝트에 1개의 게이트웨이를 생성하여 사용할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

1. 오른쪽 상단의 <mark style="background-color:blue;">GATEWAY 생성</mark> 버튼을 눌러 생성 화면으로 전환합니다.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

2. 상단 프로젝트 메뉴에서 **전체** 부분을 눌러 현재 생성된 프로젝트를 조회하고 게이트웨이가 생성될 프로젝트를 선택합니다. [프로젝트 생성](tenant-manager-console.md#create-project) 단계에서 진행한 **project-00** 프로젝트를 선택하여 진행합니다.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

3. 프로젝트를 선택하면 아래와 유사한 화면을 확인할 수 있습니다. 게이트웨이 생성을 위한 구성을 진행합니다.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

> 3-1. Gateway 이름: <mark style="background-color:red;">gateway-00</mark>
>
> 3-2. Kong Namespace: <mark style="background-color:red;">apim-gateways</mark>
>
> 3-3. Kong Storage Class: <mark style="background-color:red;">gp3</mark>
>
> 3-4. Storage capacity: <mark style="background-color:red;">5</mark>
>
> 3-5. Inner Redis: <mark style="background-color:red;">On</mark>
>
> 3-6. 오른쪽 아래의 <mark style="background-color:blue;">GATEWAY 생성</mark> 버튼 클릭

위 과정을 통해 아래와 유사한 화면을 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

4. **Gateway 관리** 홈 화면으로 이동하면 생성 중이거나, 생성된 게이트웨이가 조회됩니다.&#x20;

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

5. 게이트웨이 이름을 눌러 **Gateway 생성 정보** 화면으로 이동합니다. 이 화면에서 생성된 게이트웨이 정보와 추가된 내용을 확인할 수 있습니다.
6. **Gateway 생성 정보** 화면의 하단에서 Gateway URL 정보를 편집할 수 있습니다. <mark style="background-color:blue;">추가</mark> 버튼을 눌러 다음 단계를 진행합니다.

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

> 6-1. Gateway URL: <mark style="background-color:red;">rest-api.techsummit.asia</mark>
>
> 6-2. Global BasePath: <mark style="background-color:red;">/api-00</mark>
>
> 6-3. <mark style="background-color:blue;">GATEWAY URL 정보 저장</mark> 클릭

