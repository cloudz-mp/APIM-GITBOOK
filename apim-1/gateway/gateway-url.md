---
description: 게이트웨이에 지정되는 URL 정보입니다. (쿠버네티스의 Ingress 사양)
---

# Gateway URL 정보

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

이후, 게이트웨이에 등록되는 API가 사용할 URL과 사양을 구성합니다. 언제든지 편집이 가능합니다.

<table><thead><tr><th width="257">이름</th><th>설명</th></tr></thead><tbody><tr><td>Gateway URL</td><td>API 호출을 위한 주소</td></tr><tr><td>Global BasePath</td><td>게이트웨이에 등록되는 모든 API의 기본 BasePath</td></tr><tr><td>HTTPS ONLY</td><td>HTTPS 프로토콜만 사용하는 경우 ON</td></tr><tr><td>TLS certificates</td><td>TLS를 직접 등록하여 사용하는 경우</td></tr><tr><td>Annotations</td><td>쿠버네티스 인그래스의 Annotations 구성 내용</td></tr></tbody></table>

> 따라해보기.
>
> Gateway URL: <mark style="background-color:red;">rest-api.\<YOUR\_DOMAIN></mark>
>
> 이외의 모든 값은 <mark style="background-color:red;">기본값</mark>을 따릅니다.
>
> <mark style="background-color:blue;">GATEWAY URL 정보 저장</mark> 버튼 클릭.
