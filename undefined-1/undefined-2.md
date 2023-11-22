---
description: 개발자 포탈 멤버의 역할에 대하여 알아봅니다.
---

# 개발자 포탈 멤버의 역할

## My Applications

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

개발자 포탈 일반 사용자 권한을 가진 유저는 **Application** > **My Applications** 항목을 이용합니다.

API를 이용하기 위해서는 먼저 사용자만의 **My Application**을 생성해야 합니다.

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

> 따라해보기.
>
> 1. **Application** 메뉴의 하위 항목 **My Applications**으로 이동합니다.
> 2.  오른쪽 <mark style="background-color:blue;">생성</mark> 버튼을 눌러 **My Application 생성** 모달 팝업이 나타나면 application 이름을 지정합니다.
>
>     \- 이름: <mark style="background-color:red;">myapp00</mark>

My Application을 생성하고 다음과 같은 화면에서 애플리케이션 이름을 눌러 **Application 기본 정보** 페이지로 이동합니다.

## Application

애플리케이션에서 **기본 정보**, **API KEY**, **API 사용**, **멤버 관리에** 대한 작업을 수행할 수 있습니다.

### **기본 정보**

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

기본 정보 화면에서 **Application 이름**과 **Application 아이콘**을 변경할 수 있습니다. 또한, **AppID**와 **생성일**을 확인할 수 있습니다.

### API KEY

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

API KEY 화면에서는 API Request 시 key-auth 정책이 사용되는 경우 필요한 **API KEY**를 확인할 수 있습니다.\
위 사진에서는 해당 API KEY를 x-apim-key 헤더의 값으로 사용합니다.

### API 사용

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

API 사용 화면에서 <mark style="background-color:blue;">추가</mark> 버튼을 눌러 나타나는 모달 팝업을 통해 API 사용 신청을 할 수 있습니다.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

> 따라해보기.
>
> \*이 과정은 Product 관리 단계가 선행되어야 합니다.
>
> 1. 추가 버튼을 눌러 나타나는 **사용승인신청** 모달 팝업을 확인합니다.
> 2.  사용하려는 API를 확인하고 아이콘 왼쪽의 체크박스를 확인합니다.
>
>     \- 사용하려는 API 이름: <mark style="background-color:red;">api00</mark>
> 3.  가장 위쪽의 **사용 목적 및 설명** 텍스트 입력 공간에 사유를 입력합니다.
>
>     \- 텍스트 입력: <mark style="background-color:red;">test</mark> &#x20;
> 4. 오른쪽 하단의 <mark style="background-color:blue;">확인</mark> 버튼을 눌러 진행합니다.

API 사용 승인 대기 상태에서는 **API URL** 정보가 보이지 않지만, 승인 후에는 확인할 수 있습니다.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### 멤버 관리

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

멤버 관리 화면에서 Application을 사용할 수 있는 일반 사용자를 추가할 수 있습니다.

최초 My Application을 생성한 사용자는 기본으로 관리자로 지정되어 있으며, 추가된 사용자를 **관리자로 지정**할 수 있습니다.

오른쪽 <mark style="background-color:blue;">추가</mark> 버튼을 눌러 나타나는 **추가할 멤버 선택** 모달 팝업에서 추가하고자 하는 사용자를 체크하고 <mark style="background-color:blue;">확인</mark> 버튼을 눌러 진행합니다.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

> 따라해보기.
>
> 1. <mark style="background-color:blue;">추가</mark> 버튼을 눌러 나타나는 모달 팝업 확인
> 2.  추가할 사용자의 왼쪽 체크박스 클릭
>
>     \- ID: <mark style="background-color:red;">app-user-00@user.com</mark>
> 3. <mark style="background-color:blue;">확인</mark>

