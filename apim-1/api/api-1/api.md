---
description: APIM에서 지원하는 API 정책에대해 알아봅니다.
---

# API 정책

게이트웨이를 통과하는 API에 APIM에서 지원하는 정책을 통하여 유량제어, 전문 변환, 로깅, 보안 등 다양한 추가 기능을 구현할 수 있습니다.

<figure><img src="../../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

각 정책은 개별로 동작하며, Inbound 정책과 Outbound 정책으로 나누어집니다.

* Inbound 정책

<table><thead><tr><th width="219">이름</th><th>설명</th></tr></thead><tbody><tr><td>ip-restriction</td><td></td></tr><tr><td>jwt</td><td></td></tr><tr><td>key-auth       </td><td></td></tr><tr><td>oidc</td><td></td></tr><tr><td>rate-limiting</td><td></td></tr><tr><td>request-termination</td><td></td></tr><tr><td>request-transformer</td><td></td></tr><tr><td>route-by-header</td><td></td></tr><tr><td>timeout</td><td></td></tr><tr><td>txid</td><td></td></tr></tbody></table>

* Outbound 정책

<table><thead><tr><th width="219">이름</th><th>설명</th></tr></thead><tbody><tr><td>cors</td><td></td></tr><tr><td>http-log</td><td></td></tr><tr><td>proxy-cache</td><td></td></tr><tr><td>response-transformer</td><td></td></tr><tr><td>stdout-log</td><td></td></tr></tbody></table>

