---
description: 개발자 포털 기본 사용에 대하여 알아봅니다.
---

# 개발자 포털 시작하기

개발자 포털은 크게 관리자와 멤버 역할로 나눌 수 있습니다.  각 역할을 수행해봅니다.

## 관리자

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

개발자 포털에 처음 접속하면 기본 구성되어있는 웹페이지를 확인할 수 있습니다. 메뉴와 애플리케이션을 구성하고 API를 등록하여 공개하여 봅니다.

***

### Menu 관리

&#x20;1\. 오른쪽 위의 <mark style="background-color:blue;">Developers 관리자</mark> 버튼을 눌러 관리자 전용 편집 페이지로 이동합니다.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

2. 개발자 포털의 풀다운 메뉴 편집을 위해 왼쪽의 메뉴에서 <mark style="background-color:blue;">Menu 관리</mark> 버튼을 눌러 화면을 전환합니다.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

3. 전환된 화면에서 **메뉴 구조 설정**의 <mark style="background-color:blue;">**+**</mark> 버튼을 눌러 최상위 메뉴를 추가하고 편집할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

4. 다시 왼쪽의 <mark style="background-color:blue;">...</mark> 버튼을 눌러 나타나는 <mark style="background-color:blue;">**+**</mark> 버튼으로 하위 메뉴를 추가합니다.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

5. 다시한번 추가를 반복하여 하위 메뉴의 페이지를 추가합니다.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

6. 추가한 메뉴 구성은 반드시 <mark style="background-color:blue;">저장</mark> 버튼을 눌러 편집 내용을 저장해야 반영됩니다. 반영이 진행되면, 최하위 메뉴의 페이지를 편집할 수 있도록 이름 옆 <mark style="background-color:blue;">편집</mark> 버튼이 활성화 됩니다.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

7. <mark style="background-color:blue;">편집</mark> 버튼을 눌러 메뉴 편집 에디터로 이동하여 내용을 편집합니다.

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

8. <mark style="background-color:blue;">저장</mark> 버튼을 눌러 작성 내용을 반영하면, 상단의 메뉴에 적용된 것을 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

***

### Product 관리 - 생성

API를 등록하여 사용하기 위해서는 Project가 한 개 이상 필요합니다. Project를 생성하고, API를 등록하여 게시해봅니다.

1. 왼쪽의 메뉴에서 <mark style="background-color:blue;">Project 관리</mark> 버튼을 눌러 화면을 전환합니다.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

2. 오른쪽 생성 버튼을 눌러 나타나는 **Product 생성** 팝업에 Product 이름을 작성하고, <mark style="background-color:blue;">확인</mark> 버튼을 눌러 진행합니다.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

3. 생성이 성공하면, Product 상세 페이지로 전환됩니다.

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

***

### Product 관리 - API 추가

1. API 등록을 위하여 <mark style="background-color:blue;">API</mark> 탭을 눌러 화면을 전환하고, 우측 <mark style="background-color:blue;">추가</mark> 버튼을 눌러 **Prodcut-API 추가** 팝업을 확인합니다.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

2. 팝업에서 [API 생성](apim-console.md#api-creation) 단계에서 게시한 API를 확인할 수 있습니다. 해당 API의 선택박스를 선택하고 <mark style="background-color:blue;">API 추가</mark>를 진행합니다.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

3. API 추가를 위해서는 **API 이름 재정의**가 필요합니다. 이름을 재정의하고 <mark style="background-color:blue;">API 추가</mark> 버튼을 누릅니다.

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

> 3-1. API: <mark style="background-color:red;">my-open-api-00</mark>

4. API가 추가되면 아래와 같이 **Product 상세** 페이지에서 조회할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

5. 이제 생성된 Product를 사용자가 이용할 수 있도록 게시합니다. 다시, 왼쪽의 **Product 관리** 메뉴를 눌러 Product 목록을 조회하고, 해당 Product에서 게시여부 선택박스를 선택합니다.
6. 나타나는 팝업에서 확인 버튼을 누르면 아래와 같이 게시됨을 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

***

### API 사용자 요청 관리

1. **(이번 단계에는** [**API 사용 신청**](undefined.md#api-1) **요청이 선행 되어야 합니다.)** 왼쪽의 **API 사용 요청 관리** 메뉴로 이동합니다. 멤버의 사용 신청 요청을 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

2. **승인** 또는 **반려**를 위하여 해당 요청의 액션 <mark style="background-color:blue;">승인</mark> 버튼을 눌러 팝업을 확인합니다.
3. 기본 값으로 승인이 설정되어 있으며, <mark style="background-color:blue;">API명</mark>을 한번 클릭하여 ~~**삭선 상태로**~~ 전환하면 반려 모드로 전환됩니다.

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

3. **승인** 또는 **반려** 메시지를 작성하고 <mark style="background-color:blue;">확인</mark> 버튼을 눌러 단계를 진행합니다.&#x20;

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

4. 나타나는 검토 팝업 또한 <mark style="background-color:blue;">확인</mark>을 눌러 진행하면, 아래와 같이 **처리 완료**를 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

***

## 멤버

멤버는 Application 공간을 만들고, API 사용 요청을 통해 공개된 API를 사용할 수 있습니다.

***

### My Application - 생성

개발자 포털 상단의 **Application** 메뉴를 통해 **My Applications** 페이지로 이동하여 단계를 진행합니다.

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

1. **My Application** 페이지에서 오른쪽 생성 버튼을 눌러 신규 팝업에서 이름을 입력합니다.

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

> 1-1. Application 이름: <mark style="background-color:red;">My app 01</mark>
>
> 1-2. <mark style="background-color:blue;">확인</mark>

2. 생성이 완료되면 **Application 기본 정보** 페이지로 이동됩니다.&#x20;

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

***

### API 사용 신청

1. **API 사용 신청**을 위하여 왼쪽의 <mark style="background-color:blue;">API 사용</mark> 메뉴를 눌러 이동합니다.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

4. **API 사용** 페이지에서 오른쪽 <mark style="background-color:blue;">추가</mark> 버튼을 눌러 게시된 API를 조회합니다. 나타나는 팝업에서 원하는 API의 왼쪽 선택박스를 선택하고 팝업 상단의 **사용 목적 및 설명**을 작성한 후, <mark style="background-color:blue;">확인</mark> 버튼을 눌러 승인을 요청합니다.
5. **API 사용 페이지**에서 승인 요청된 해당 API 상태가 **대기**로 표기된 것을 확인합니다.

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

6. **(이 단계는** [**API 사용 승인 단계**](undefined.md#api)**가 선행되어야 합니다.) API 사용** 페이지에서 승인 요청된 해당 API 상태가 **완료** 표기된 것을 확인합니다.

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

7. 승인이 진행 되면, **API URL**이 나타나고 정상 호출됨을 확인합니다.

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

