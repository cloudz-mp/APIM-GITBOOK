---
description: 사용자 관리 콘솔 기본 사용에 대하여 알아봅니다.
---

# 사용자 관리 콘솔 시작하기

## 사용자 관리 콘솔

### 프로젝트 관리

#### 프로젝트 생성 <a href="#create-project" id="create-project"></a>

<figure><img src="../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. 프로젝트 관리 화면의 우측 상단 <mark style="background-color:blue;">프로젝트 생성하기</mark> 버튼을 통해 프로젝트 생성하기 화면으로 이동합니다.

프로젝트 생성을 위해서는 **프로젝트 이름**, **apim/developers 타입**, **Gateway 타입**을 지정해야 합니다.

<figure><img src="../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

2. 프로젝트 이름 <mark style="background-color:red;">project-\<MY-PROJECT-NAME></mark>, apim/developers 타입 <mark style="background-color:red;">apim</mark>, Gateway 타입 <mark style="background-color:red;">kong</mark> 을 입력하고 <mark style="background-color:blue;">프로젝트 생성</mark> 버튼을 눌러 진행합니다.

![](<../../.gitbook/assets/image (38).png>)

위와 같이 입력하여 아래와 같은 결과를 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### 프로젝트 관리 상세

3. 프로젝트 관리에서 사용자 권한 부여를 진행합니다. 프로젝트의 우측 액션 <mark style="background-color:blue;">상세</mark> 버튼을 눌러 상세 화면으로 이동합니다.

<figure><img src="../../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

#### 사용자 추가

4. 먼저, 사용자 추가를 위하여 오른쪽 아래의 <mark style="background-color:blue;">프로젝트 사용자 추가</mark> 버튼을 눌러 **프로젝트 사용자 관리** 화면으로 이동합니다.

화면 이동 후, 아래 단계 진행을 통해 사용자 추가를 할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

> 4-1. 우측 검색 박스에서 사용자 \*검색( <mark style="background-color:red;">admin</mark> 입력 후 엔터 )
>
> 4-2. 사용자 ID 왼쪽 체크박스 선택
>
> 4-3. 검색 박스 옆 <mark style="background-color:blue;">프로젝트 사용자 추가</mark> 버튼 클릭
>
> 4-4. 할당 권한에 **apim-pjt-member APIM 프로젝트 멤버** <mark style="background-color:red;">체크박스</mark> 선택
>
> 4-5. <mark style="background-color:blue;">프로젝트 사용자 권한 설정 및 추가</mark> 클릭

\*검색 이전에는 어떠한 아이디 목록도 조회되지 않습니다.

<figure><img src="../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

위와 같은 설정으로 프로젝트에 사용자 추가를 진행하여 다음 결과를 얻을 수 있습니다.

<figure><img src="../../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>

프로젝트를 생성하고, 사용자 추가를 완료하였습니다.

이제 APIM 콘솔을 사용해봅니다.

