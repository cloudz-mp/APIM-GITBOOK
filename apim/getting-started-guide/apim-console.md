---
description: APIM 콘솔 기본 사용에 대하여 알아봅니다.
---

# APIM 콘솔 시작하기

## APIM 콘솔

***

### Gateway 관리

***

#### 게이트웨이 생성

APIM에서는 1개의 프로젝트에 1개의 게이트웨이를 생성하여 사용할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

1. 오른쪽 상단의 <mark style="background-color:blue;">GATEWAY 생성</mark> 버튼을 눌러 생성 화면으로 전환합니다.

<figure><img src="../../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

2. 먼저, '**프로젝트를 선택하세요.'** 라는 안내 문구를 볼 수 있습니다. 상단 프로젝트 메뉴에서 **전체** 부분을 눌러 현재 생성된 프로젝트를 조회하고 게이트웨이가 생성될 프로젝트를 선택합니다. [프로젝트 생성](tenant-manager-console.md#create-project) 단계에서 진행한 **project-00** 프로젝트를 선택하여 진행합니다.

<figure><img src="../../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

3. 프로젝트를 선택하면 아래와 유사한 화면을 확인할 수 있습니다. 게이트웨이 생성을 위한 구성을 진행합니다.

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

> 3-1. Gateway 이름: <mark style="background-color:red;">gateway-\<MY-GATEWAY-NAME></mark>
>
> 3-2. Kong Namespace: <mark style="background-color:red;">apim-gateways</mark>
>
> 3-3. Kong Storage Class: <mark style="background-color:red;">gp3</mark>
>
> 3-4. Storage capacity: <mark style="background-color:red;">5</mark>
>
> 3-5. Inner Redis: <mark style="background-color:red;">On</mark>
>
> 3-6. 오른쪽 아래의 <mark style="background-color:blue;">GATEWAY 생성</mark> 버튼 클릭

위 과정을 통해 아래와 유사한 화면을 확인할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

4. **Gateway 관리** 홈 화면으로 이동하면 생성 중이거나, 생성된 게이트웨이가 조회됩니다.&#x20;

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

5. 게이트웨이 이름을 눌러 **Gateway 생성 정보** 화면으로 이동합니다. 이 화면에서 생성된 게이트웨이 정보와 추가된 내용을 확인할 수 있습니다.
6. **Gateway 생성 정보** 화면의 하단에서 Gateway URL 정보를 편집할 수 있습니다. <mark style="background-color:blue;">추가</mark> 버튼을 눌러 다음 단계를 진행합니다.

<figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

> 6-1. Gateway URL: <mark style="background-color:red;">\<MY-SUB-DOMAIN>.rest-api.techsummit.asia</mark>
>
> 6-2. Global BasePath: <mark style="background-color:red;">/</mark>
>
> 6-3. Annotations <mark style="color:red;">**1**</mark> Key: <mark style="background-color:red;">alb.ingress.kubernetes.io/listen-ports</mark>&#x20;
>
> &#x20;      . Annotations <mark style="color:red;">**1**</mark> Value: <mark style="background-color:red;">\[{"HTTP": 80}]</mark>
>
> 6-4. Annotations <mark style="color:orange;">**2**</mark> Key: <mark style="background-color:red;">alb.ingress.kubernetes.io/scheme</mark>
>
> &#x20;      . Annotations <mark style="color:orange;">**2**</mark> Value: <mark style="background-color:red;">internet-facing</mark>
>
> 6-5. Annotations <mark style="color:green;">**3**</mark> Key: <mark style="background-color:red;">alb.ingress.kubernetes.io/target-type</mark>&#x20;
>
> &#x20;      . Annotations <mark style="color:green;">**3**</mark> Value: <mark style="background-color:red;">ip</mark>
>
> 6-6. <mark style="background-color:blue;">GATEWAY URL 정보 저장</mark> 클릭

***

### API 관리

***

#### API 생성

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

왼쪽 메뉴에서 **API 관리**를 눌러 위와 같이 처음 만나는 API 조회 페이지를 볼 수 있습니다.

7. 오른쪽 위 <mark style="background-color:blue;">API 생성</mark> 버튼을 눌러 API 생성 화면으로 전환합니다. 처음 게이트웨이를 생성할 때와 같이 '**프로젝트를 선택하세요**' 안내 메시지를 볼 수 있습니다. 이전과 같이 상단 프로젝트 메뉴에서 **전체** 부분을 눌러 현재 생성된 프로젝트를 조회하고 API가 생성될 프로젝트를 선택합니다. [프로젝트 생성](tenant-manager-console.md#create-project) 단계에서 진행한 **project-00** 프로젝트를 선택하여 진행합니다.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

8. 프로젝트를 선택하면, **API 생성 정보**에 대하여 상세 내용을 구성합니다.

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

> 8-1. API 이름: <mark style="background-color:red;">my-api-00</mark>
>
> 8-2. Gateway: 이전 단계에서 생성한 프로젝트 <mark style="background-color:red;">gateway-00</mark>
>
> 8-3. Gateway URL: 이전 단계에서 생성한 URL <mark style="background-color:red;">my.rest-api.techsummit.asia</mark>
>
> 8-4. Base Path: <mark style="background-color:red;">/api-00</mark>
>
> 8-5. Backend URL: <mark style="background-color:red;">http://go-web-server.apim.svc.cluster.local:8080</mark>
>
> 8-6. Developers Portal 게시: <mark style="background-color:red;">체크</mark>
>
> 8-7. 오른쪽 아래 <mark style="background-color:blue;">API 저장</mark> 클릭

9. API 상세 설정을 완료하고 저장을 진행하면 작성한 API의 주소에서 **Swagger Path**를 호출하여 1회 자동으로 문서유무를 확인합니다. 이때, 문서가 있으면 아래와 같은 팝업 안내를 볼 수 있습니다. 여기서는 <mark style="background-color:blue;">취소</mark>를 눌러 진행합니다.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

***

#### API 상세

10. API가 등록 성공하였다면, 아래와 같이 **API 상세** 페이지를 확인할 수 있습니다. 또한, **API 관리** 홈에서 API 이름을 눌러 각 **API 상세** 페이지로 이동할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

11. 생성한 API를 오른쪽 위 <mark style="background-color:blue;">API 배포</mark> 버튼을 눌러 배포합니다. 배포를 하지 않으면 실제로 API를 호출할 수 없습니다.

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

> 11-1. 배포 버전 설명: 첫 번째 배포

***

#### API 정책

12. API 정책을 적용해보도록 합니다. 가운데 녹색 박스에서 찾을 수 있는 <mark style="background-color:blue;">정책 변경</mark> 버튼을 눌러 API 정책 상세 페이지로 이동합니다.&#x20;

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

13. 이번 단계에서는 **request-transformer** 정책을 사용하여 커스텀 헤더를 추가해보도록 합니다. **request-transformer**의 <mark style="background-color:blue;">**+**</mark> 버튼을 눌러 해당 버튼을 왼쪽 **미적용 영역**에서 **오른쪽 적용** 영역으로 이동시킵니다.
14. **request-transformer**에 대한 상세 내용을 구성합니다. **request-transformer** 버튼을 눌러 아래 **설정** 영역의 내용을 전환합니다.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

15. 위와 같은 화면에서 **config 텍스트 공간에 다음의 내용을 작성합니다.**

> <mark style="background-color:red;">config.add.headers=\<YOUR-CUSTOM-KEY>:\<YOUR-CUSTOM-VALUE></mark>

16. 오른쪽 위의 <mark style="background-color:blue;">저장</mark> 버튼을 눌러 정책을 저장하고, **API 상세** 페이지로 돌아옵니다.
17. 정책을 적용한 API를 오른쪽 위 <mark style="background-color:blue;">API 배포</mark> 버튼을 눌러 배포합니다. 배포를 하지 않으면 변경된 정책이 실제로 호출되는 API에 적용되지 않습니다.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

***

#### API 문서

자동으로 스웨거 문서를 가져올 수 있지만, **JSON Editor**를 이용하여 직접 문서를 작성하거나 가져온 문서를 편집할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

14. 위와 같이 **API 상세** 페이지의 중간 부분에서 <mark style="background-color:blue;">API 문서 - Swagger JSON Editor</mark>를 클릭하여 문서 편집기를 확장하고, 아래의 내용을 붙여넣습니다.

```json
{
  "openapi": "3.0.0",
  "info": {
    "title": "간단한 HTTP 서버",
    "description": "클라이언트의 IP 주소를 반환하는 HTTP 서버",
    "version": "1.0.0"
  },
  "paths": {
    "/": {
      "get": {
        "summary": "클라이언트 IP 조회",
        "description": "현재 서버에 연결된 클라이언트의 IP 주소를 반환합니다.",
        "responses": {
          "200": {
            "description": "성공",
            "content": {
              "text/plain": {
                "schema": {
                  "type": "string"
                }
              }
            }
          }
        }
      },
      "post": {
        "summary": "없는 호출입니다",
        "description": "스웨거 문서를 위한 존재하지 않는 호출입니다.",
        "responses": {
          "404": {
            "description": "없는 호출입니다."
          }
        }
      }
    }
  }
}

```

14. 내용을 작성하고 <mark style="background-color:blue;">Swagger 저장</mark> 버튼을 클릭합니다. 스웨거 문서를 편집한 후에는 반드시 오른쪽 위에 위치한 <mark style="background-color:blue;">Swagger 저장</mark> 버튼을 눌러야 변경 내용이 보존됩니다.
15.
