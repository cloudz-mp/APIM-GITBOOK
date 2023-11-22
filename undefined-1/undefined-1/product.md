---
description: Product 목록 입니다. Product는 여러 API의 묶음으로 구성할 수 있습니다.
---

# Product 관리

## Product 관리 홈

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

오른편의 `생성` 버튼을 눌러 `My applications`에서 이용할 수 있는 API 묶음인 Product를 구성합니다.

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

제품을 구성하는 API를 정의합니다. 오른편 `추가` 버튼을 눌러 APIM 콘솔의 [**API 생성**](../../apim-1/api/api.md) 단계에서 진행한 <mark style="background-color:red;">Developers Portal 게시</mark>에 체크를 수행하고 배포한 경우 이곳에서 보입니다.\
API를 Product에 추가하기 위해서 추가 버튼을 눌러 나타나는 모달창에서 해당하는 API를 체크하고 <mark style="background-color:red;">API 추가</mark>를 진행합니다.

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

추가 버튼을 누르고 API 이름과 설명을 정의하고 다시 <mark style="background-color:red;">API 추가</mark> 버튼을 눌러 수행을 완료합니다.

API 추가가 완료되면, 액션 기능이 활성화 됩니다. 각 액션은 다음과 같습니다.

<table><thead><tr><th width="88">아이콘</th><th width="217">이름</th><th>설명</th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (67).png" alt="" data-size="original"></td><td>삭제</td><td>API를 삭제합니다.</td></tr><tr><td><img src="../../.gitbook/assets/image (64).png" alt="" data-size="original"></td><td>수정</td><td>API 이름 또는 설명을 수정합니다.</td></tr><tr><td><img src="../../.gitbook/assets/image (65).png" alt="" data-size="original"></td><td>SWAGGER API 숨김 설정</td><td>Swagger를 제공하는 경우, 각 API의 공개 여부를 설정합니다.</td></tr><tr><td><img src="../../.gitbook/assets/image (66).png" alt="" data-size="original"></td><td>APIM 콘솔에서 보기</td><td>APIM 콘솔에서 해당 API에 해당하는 상세 내용을 확인합니다.</td></tr></tbody></table>

