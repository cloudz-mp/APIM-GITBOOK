---
description: API의 생성 후, 편집 가능한 상세 페이지에 대해서 알아봅니다.
---

# API 상세

API 상세 페이지는 Overview, API 문서, API Test 기능을 확인할 수 있습니다. 차례대로 살펴보도록 합니다.

## Overview

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Overview에서는 Frontend와 Backend 그리고 게이트웨이 정책을 확인할 수 있습니다.

각 항목에서 Frontend와 Backend의 변경은 API 생성 화면과 같은 구성의 페이지에서 내용을 편집할 수 있습니다.

다음으로 정책 변경에 대하여 자세히 알아봅니다.

### 정책 변경

Overview 중심에 위치한 <mark style="background-color:blue;">정책변경</mark> 버튼을 눌러 아래와 같은 화면을 확인할 수 있습니다.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

각 정책에서 + 버튼을 눌러 미적용 박스에서 적용 박스로 이동 후 오른쪽 위의 저장 버튼을 눌러 API에 정책을 적용할 수 있습니다. 이때 적용 후, 반드시 새로운 배포를 진행해야 실제 API에 정책이 적용됩니다.

API 정책에 대한 자세한 내용은 API 정책 문서를 참고합니다.

## API 문서

<figure><img src="../../../.gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

오른쪽 위의 <mark style="background-color:blue;">SWAGGER 가져오기</mark> 버튼을 눌러 API 생성 단계에서 지정한 Swagger path 호출을 통하여 문서를 불러올 수 있습니다. API 최초 생성 시, 올바른 경로를 설정하고 해당 문서가 존재한다면 자동으로 불러옵니다.

<mark style="background-color:blue;">API 문서 - Swagger JSON Editor</mark> 항목을 눌러 직접 JSON 형식으로 문서를 편집할 수 있습니다. Swagger 문서를 불러오거나, 직접 편집하였을 때 오른쪽 위의 <mark style="background-color:blue;">SWAGGER 저장</mark> 버튼을 눌러야 변경 사항이 반영됩니다.

## API Test&#x20;

백엔드 주소 경로를 호출 확인하기 위한 기능으로, API Gateway를 통과하여 호출하지 않습니다.

Method 변경을 통해 Rest API 호출 Method를 지원합니다. 오른쪽 아래 <mark style="background-color:blue;">API 요청 테스트</mark> 버튼으로 요청을 진행하고 아래에서 그 결과를 확인할 수 있습니다.

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
