---
description: APIM 게이트웨이에 대한 메트릭을 모니터링 합니다.
---

# Monitoring

<figure><img src="../.gitbook/assets/image (11) (1) (1).png" alt=""><figcaption></figcaption></figure>

APIM에서는 Prometheus를 통한 메트릭 수집을 통해 Grafana Dashboard로 모니터링 서비스를 제공합니다.

멀티클러스터의 경우, 클러스터를 먼저 선택하여 구분하고 각 게이트웨이에 대한 메트릭을 확인할 수 있습니다.

메트릭 지표는 각 게이트웨이에 모듈이 설치되어야만 동작하며 이는 APIM 게이트웨이 구성 시 포함됩니다.\
지표 값으로 게이트웨이 호출에 대한 지연, 호출 상태, 대역폭 등이 제공됩니다.

