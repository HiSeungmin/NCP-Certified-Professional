강의 출처 : https://bizschool.naver.com/online/course/65189/lecture/1461898

## 클라우드의 역사
- 1960년대 가상화라는 용어 사용
    - 당시에는 전 가상화 기법을 사용하여 구현
    - 에뮬레이터도 존재

- 다양한 하이퍼바이저의 출현
    - IBM의 Logical Partition(IBM의 유닉스 머신에 사용되는 하이퍼바이저)
    - VMWare
    - Xen
    - KVM
    - Hyper-v

## 클라우드의 역사 - 서버 가상화

[Before]
하나의 물리적 리소스 위에서 한개의 OS 실행

[After]
하나의 물리적 리소스 위에서 여러 OS를 동시에 실행

1. 위치와 역할에 따른 분류
    - Type 1.
        - Native (bare metal)
        - e.g. IBM xen, VMware ESX Server, MS Hyper-v, ...
    - Type 2.
        - Hosted
        - e.g. VMware Server, VMware Workstation, MS Virtual Server, Oracle Virtual Box
2. 가상화 방식에 따른 분류
    - 전가상화 (Full Virtualization)
        - 하드웨어를 모두 가상화한 것을 말함.
        - 게스트 OS가 직접 CPU에게 하드웨어 제어를 의뢰함
    - 반가상화 (Para-Virtualization)
        - 하드웨어를 완전히 가상화 하지 않음
        - 게스트 OS가 하이퍼바이저에게 하드웨어 제어를 의뢰함

