# 게이트웨이 생성

게이트웨이 생성을 진행합니다.

이름, 설명, 태그를 지정하고 게이트웨이의 클러스터 등 스펙을 설정합니다.

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="212">이름</th><th>설명</th></tr></thead><tbody><tr><td>Gateway 타입</td><td>프로젝트에 지정된 게이트웨이의 종류</td></tr><tr><td>Gateway 이름</td><td>생성될 게이트웨이의 이름</td></tr><tr><td>Gateway 설명</td><td>게이트웨이 조회 시 보일 설명 (편집 가능)</td></tr><tr><td>Gateway 태그</td><td>검색 등에 사용되는 게이트웨이에 지정되는 태그 (편집 가능)</td></tr><tr><td>Gateway CPU</td><td>게이트웨이에 할당되는 CPU 사양</td></tr><tr><td>Gateway Memory</td><td>게이트웨이에 할당되는 Memory 사양</td></tr><tr><td>DataBase CPU</td><td>게이트웨이의 데이터베이스에 할당되는 CPU 사양</td></tr><tr><td>DataBase Memory</td><td>게이트웨이의 데이터베이스에 할당되는 Memory 사양</td></tr><tr><td>Kong Cluster</td><td>게이트웨이가 생성될 클러스터</td></tr><tr><td>Kong Namespace</td><td>게이트웨이가 생성될 네임스페이스</td></tr><tr><td>Kong Storage Class</td><td>게이트웨이가 사용하는 스토리지 클래스의 타입</td></tr><tr><td>Storage capacity</td><td>게이트웨이가 사용하는 스토리지의 크기</td></tr><tr><td>Inner Redis</td><td>게이트웨이가 사용하는 레디스의 사양(off 선택 시, 사용자의 레디스 설정 필요)</td></tr></tbody></table>

> 따라해보기.
>
> Gateway 이름: gateway-00
>
> 모든 CPU와 Memory: 500
>
> Kong Cluster: \<YOUR\_CLUSTER>
>
> Kong Namespace: \<YOUR\_NAMESPACE>
>
> Kong Storage Class: \<YOUR\_STORAGE\_CLASS>
>
> Storage capacity: 5
>
> Inner Redis: ON
>
> 우측 하단의 \`GATEWAY 생성\` 버튼 클릭
