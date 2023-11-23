---
description: Product 목록 입니다. Product는 여러 API의 묶음으로 구성할 수 있습니다.
---

# Product 관리

## Product 관리 홈

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

오른편의 <mark style="background-color:blue;">생성</mark> 버튼을 눌러 **My applications**에서 이용할 수 있는 API 묶음인 Product를 구성합니다.

Product를 생성하면 아래와 같이 목록에서 조회할 수 있으며, 해당 제품을 사용자가 조회하고 사용할 수 있도록 하려면 게시여부 체크박스에 체크를 진행합니다.\
&#x20;

<figure><img src="../../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

여러 Product가 생성되면 순서를 지정하여 노출 우선순위를 정렬할 수 있습니다.

## Product 상세

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

생성된 Product를 클릭하여 상세 내용을 편집할 수 있습니다.

### Product 상세 - 기본정보

기본정보 화면에서 **이름**, **요약설명**, **제품소개 링크**, **API 문서 링크**, **Application 아이콘**을 구성할 수 있습니다. 각 구성은 제품 조회 시 사용자에게 보입니다.

### Product 상세 -API

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

제품을 구성하는 API를 정의합니다. 오른편 <mark style="background-color:blue;">추가</mark> 버튼을 눌러 APIM 콘솔의 [**API 생성**](../../apim-console/api/api.md) 단계에서 진행한 **Developers Portal 게시**에 체크를 수행하고 배포한 경우 이곳에서 보입니다.\
API를 Product에 추가하기 위해서 추가 버튼을 눌러 나타나는 모달창에서 해당하는 API를 체크하고 <mark style="background-color:blue;">API 추가</mark>를 진행합니다.

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

추가 버튼을 누르고 API 이름과 설명을 정의하고 다시 <mark style="background-color:blue;">API 추가</mark> 버튼을 눌러 수행을 완료합니다.

API 추가가 완료되면, 액션 기능이 활성화 됩니다. 각 액션은 다음과 같습니다.

<table><thead><tr><th width="88">아이콘</th><th width="217">이름</th><th>설명</th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (67).png" alt="" data-size="original"></td><td>삭제</td><td>API를 삭제합니다.</td></tr><tr><td><img src="../../.gitbook/assets/image (64).png" alt="" data-size="original"></td><td>수정</td><td>API 이름 또는 설명을 수정합니다.</td></tr><tr><td><img src="../../.gitbook/assets/image (65).png" alt="" data-size="original"></td><td>SWAGGER API 숨김 설정</td><td>Swagger를 제공하는 경우, 각 API의 공개 여부를 설정합니다.</td></tr><tr><td><img src="../../.gitbook/assets/image (66).png" alt="" data-size="original"></td><td>APIM 콘솔에서 보기</td><td>APIM 콘솔에서 해당 API에 해당하는 상세 내용을 확인합니다.</td></tr></tbody></table>

> 따라해보기.
>
> \*이 과정은 API 생성 단계를 먼저 수행해야 합니다.
>
> 1.  Product 관리 홈에서 생성 버튼을 눌러 Product를 생성합니다.
>
>     &#x20;   \- <mark style="background-color:red;">이름: My Product 00</mark>
> 2. 생성된 Product를 클릭하여 Product 상세로 이동합니다.
> 3.  Product 상세 화면에서 API 탭을 클릭하여 전환하고, API를 추가합니다.
>
>     a. API 생성 단계에서 게시한 API를 체크합니다.
>
>     &#x20;   \- <mark style="background-color:red;">project: project-00</mark>\
>     &#x20;   \- <mark style="background-color:red;">gateway: gateway-00</mark>\
>     &#x20;   \- <mark style="background-color:red;">API: api-00</mark>
>
>     b. API 이름을 재정의하고 API를 추가합니다.
>
>     &#x20;   \- <mark style="background-color:red;">이름: api00</mark>

