---
description: API jwt 정책의 JWT KEY를 관리합니다.
---

# JWT

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>JWT 홈</p></figcaption></figure>

## JWT 란?

jwt 정책을 사용하기 위해서 먼저 JWT에 대해서 알아봅니다.

JSON Web Token (JWT)은 웹 표준으로, 데이터를 안전하게 전달하기 위한 컴팩트하고 자가수용적인 방법을 정의하는 토큰입니다. JWT는 클레임을 JSON 객체로 안전하게 전송하기 위한 방법으로 사용됩니다.

JWT는 세 부분으로 구성됩니다: Header(헤더), Payload(내용), Signature(서명). 이 세 부분은 Base64 URL로 인코딩되어 하나의 문자열로 합쳐집니다.

자세한 내용은 [jwt.io](https://jwt.io/)를  참고합니다.

## jwt 정책 사용하기

### JWT KEY 생성

jwt 정책을 API에 적용하였다면, 인증을 위한 토큰이 필요합니다. 이를 위하여 오른쪽 <mark style="background-color:blue;">JWT KEY 생성</mark> 버튼을 눌러 JWT KEY와 JWT SECRET 발급화면으로 이동합니다.

APIM에서는 JWT 사용 방법으로 **HS256**과 **RS256** 두 가지 알고리즘을 지원합니다.

* HS256

<figure><img src="../../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

HS256 알고리즘을 사용하는 경우 자동으로 KEY와 SECRET을 생성해줍니다.

* RS256

<figure><img src="../../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

RS256 알고리즘을 사용하는 경우 사용자 정의에 따라 Public KEY와 Private KEY를 구성합니다.

각 값을 확인하고, 오른쪽 아래 <mark style="background-color:blue;">생성</mark> 버튼을 눌러 생성을 진행합니다.

생성을 완료하고 JWT 홈 화면으로 이동하면 아래 이미지 예시처럼 정상적으로 생성 완료된 JWT KEY를 조회할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

홈 화면에서 조회된 목록에서 **Active** **활성화/비활성화**를 전환하여 해당 JWT KEY 인증이 동작하지 않도록 할 수 있으며 사용에 주의해야 합니다.&#x20;

또한, 가장 오른쪽의 <mark style="background-color:blue;">X</mark> 버튼으로 삭제할 수 있습니다.

### JWT 정책 사용 가이드

API Gateway는 설정에 따라 API 요청 시 포함되는 JWT 토큰 검증을 수행합니다.

RequiredPath / NotRequiredPath 설정을 통해 jwt 토큰 검증을 수행하지 않는 Method 및 Path 설정이 가능합니다. 예시) GET\_/login (요청 시, jwt 토큰이 없기 때문에 jwt 토큰 검증을 미수행해야 하는 Path)

HTTP Request Header에 **authorization: bearer {JWT Token}**의 형태로 설정 합니다.

JWT 정책이 적용된 API에 대하여 Authorization Header가 없는 경우, API를 정상 호출할 수 없음에 유의 바랍니다.

#### 참고하기

[jwt 사용 방법](https://jwt.io/introduction)

