---
description: API 정책 중 key-auth에서 사용하는 값을 관리합니다.
---

# API KEY

<figure><img src="../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

## API KEY AUTH 란?

API KEY를 사용하기 전에 **key-auth** 정책에 대하여 먼저 알아봅니다.

REST API에서 key-auth는 API 요청에 인증키를 함께 전송하여 API에 대한 접근을 인증하는 방식입니다.

인증키는 API를 사용하는 사용자에게 발급되며, 사용자는 API 요청 시 해당 인증키를 함께 전송해야 합니다.

인증키를 발급하는 방법은 다음과 같습니다.

1. 인증키 생성: API를 제공하는 서버에서 인증키를 생성합니다. 인증키는 보통 문자열 형태로 생성되며, 사용자에게 전달됩니다.
2. API 요청: 사용자는 API 요청 시 인증키를 함께 전송합니다. 인증키는 API 요청의 헤더 또는 쿼리 파라미터에 포함됩니다.
3. 인증 확인: API를 제공하는 서버는 인증키를 확인하여 사용자의 인증 여부를 판단합니다. 인증키가 일치하면 API 요청을 처리하고, 그렇지 않으면 거부합니다. key-auth는 간단한 인증 방식으로, 보안성이 높지 않기 때문에 중요한 API에서는 사용하지 않는 것이 좋습니다.

## key-auth 정책 사용하기

### KEY 발급하기

key-auth 정책을 API에 적용하였다면, 인증을 위한 key를 발급받아야 합니다. API KEY 화면에서 오른편 <mark style="background-color:blue;">API KEY 생성</mark> 버튼을 눌러 생성을 위한 화면으로 이동합니다.

<figure><img src="../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

이동한 페이지에서 자동으로 API KEY를 생성하여 보여줍니다. 오른쪽의 새로고침 버튼으로 랜덤한 KEY를 생성할 수 있습니다. 선택 작성 사항인 **API KEY 설명**을 확인하고 오른쪽 아래의 <mark style="background-color:blue;">생성</mark> 버튼을 눌러 화면의 내용을 저장합니다.

성공적으로 저장된 내용은 API KEY 홈 화면에서 생성된 키를 확인할 수 있으며, 생성된 KEY 값은 변경될 수 없습니다.&#x20;

<figure><img src="../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

목록에서 **Active** **활성화/비활성화**를 전환하여 해당 KEY 인증이 동작하지 않도록 할 수 있으며 사용에 주의해야 합니다.&#x20;

또한, 가장 오른쪽의 <mark style="background-color:blue;">X</mark> 버튼으로 삭제할 수 있습니다.

### key-auth 설정

"key-auth" 정책과 "jwt" 정책을 함께 적용할 경우, 2가지 인증을 모두 통과해야 합니다.

API 호출 시 프로젝트마다 위의 [생성 단계](api-key.md#key)를 수행한 API KEY로 인증합니다. 만약 가능한 API KEY가 없는 경우, API를 정상 호출할 수 없음에 유의 해야합니다.

호출 헤더의 예는 다음과 같습니다.

`headers: { "x-apim-key": "202cb962ac59075b964b07152d234b70" }`



\
