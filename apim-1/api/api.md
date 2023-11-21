---
description: 게이트웨이에 등록하여 사용하는 API를 생성합니다.
---

# API 생성

<figure><img src="../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

프로젝트를 지정하여 Gateway에 API를 생성합니다. 여기서 구성되는 값은 이후에도 편집이 가능합니다.

API는 구성에 따라 개발자포탈을 통해 공개될 수 있습니다.

<table><thead><tr><th width="241">이름</th><th>설명</th></tr></thead><tbody><tr><td>API 이름</td><td>등록할 API 이름</td></tr><tr><td>API 설명</td><td>API 설명</td></tr><tr><td>API 태그</td><td>API에 지정되는 태그</td></tr><tr><td>API 타입</td><td>API는 http, lambda 그리고 websocket 타입중 하나의 타입을 사용</td></tr><tr><td>HTTP Method</td><td>API 호출에 사용되는 Method 형태를 제한</td></tr><tr><td>Gateway</td><td>API를 등록할 게이트웨이를 이전 생성 과정에서 만든 게이트웨이 중에서 선택</td></tr><tr><td>Gateway URL</td><td>선택한 게이트웨이의 URL 중 하나를 선택하여 API 호출에 사용</td></tr><tr><td>Gateway URL Base Path</td><td>게이트웨이 생성 과정에서 구성한 Base Path를 보여줌</td></tr><tr><td>Base Path</td><td>이 API 만의 Base Path 를 지정</td></tr><tr><td>Strip Path</td><td>Backend 호출 시 Base Path의 제거 여부</td></tr><tr><td>API URL</td><td>이 API를 호출 URL</td></tr><tr><td>Backend URL</td><td>실제로 호출될 Backend URL</td></tr><tr><td>Swagger 가져오기 Path</td><td>API의 Swagger 문서를 가져올 주소</td></tr><tr><td>Developers Portal 게시</td><td>개발자 포탈에 API의 게시 여부</td></tr></tbody></table>

> 따라해보기.
>
> API 이름: api-00
>
> Gateway: gateway-00
>
> Gateway URL: rest-api.
>
> Base Path: game-00
>
> Backend URL: service-2048.game-2048.svc.cluster.local:80
>
> Developers Portal 게시: 체크
>
> 이외의 모든 값은 기본 값을 따릅니다.
