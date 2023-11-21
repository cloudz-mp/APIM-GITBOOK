---
description: APIM을 사용하기 위한 프로젝트를 생성합니다.
---

# 프로젝트 생성하기

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

프로젝트 관리 화면의 우측 상단 `프로젝트 생성하기` 버튼을 통해 프로젝트 생성하기 화면으로 이동합니다.

프로젝트 생성을 위해서는 `프로젝트 이름`, `apim/developers 타입`, `Gateway` 타입을 지정해야 합니다.

* 프로젝트 이름: 사용자에게 보이게 되는 프로젝트 이름입니다. 영문과 한글을 지원합니다.
* apim/developers 타입: apim 또는 developers를 선택합니다. apim 타입은 해당 프로젝트에 게이트웨이를 직접 생성하고 관리할 수 있으며, developers 타입은 DEV. PORTAL을 통하여 MYAPP에서 이용하기 위하여 사용됩니다.
* Gateway 타입: kong 또는 aws 타입을 선택합니다. kong 선택 시 클러스터에 게이트웨이를 직접 설치하여 이용할 수 있으며, aws 선택 시 AWS에서 제공하는 서비스를 이용하여 프로비저닝 할 수 있습니다.

> 따라해보기.
>
> 프로젝트 이름: project-00
>
> apim/developers 타입: apim
>
> Gateway 타입: kong
>
> ![](<../.gitbook/assets/image (38).png>)

#### 참고하기

[AWS GATEWAY란 무엇인가?](https://aws.amazon.com/ko/api-gateway/)

[KONG GATEWAY란 무엇인가?](https://docs.konghq.com/gateway/latest/)
