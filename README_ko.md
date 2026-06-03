# LFCS 교육 인증 준비 경로

## 언어

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/ko/learn/lfcs"><img width="128px" src="https://file.labex.io/path/OMeAELrqi3Ff.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/경로-시작-whitesmoke?style=for-the-badge)](https://labex.io/ko/learn/lfcs)

Linux Foundation Certified System Administrator(LFCS) 시험을 위해 구조화된 실습 중심 학습 경로로 준비하세요. 일반적인 배포판에서의 실무 Linux 관리, 성능 기반 작업, 현실 시나리오에 초점을 맞춥니다. LFCS 과정, 랩, 모의고사 연습이 단계적으로 추가되어 LFCS 목표에 맞는 명령줄 숙련도, 서비스 관리, 스토리지, 네트워킹, 보안, 문제 해결 역량을 기릅니다.

**코스**: 3 · **실습**: 89

## 코스

### 1. [LFCS 준비 과정](https://labex.io/ko/courses/lfcs-prep)

필수 명령어 워크플로우부터 사용자, 서비스, 네트워킹, 스토리지 관리에 이르기까지 49 개의 가이드형 리눅스 관리 실습으로 구성된 초보자 맞춤형 LFCS 대비 과정입니다.

[코스 시작](https://labex.io/ko/courses/lfcs-prep) · 실습: 49

#### Essential Command Workflows

|   인덱스 | 이름                                     | 난이도   | 연습                                                                                                       |
|-------|----------------------------------------|-------|----------------------------------------------------------------------------------------------------------|
|     1 | 🧩  시스템 성능 모니터링                         | 초급    | [실습 시작](https://labex.io/ko/labs/monitor-system-performance-663397?course=lfcs-prep)                     |
|     2 | 🧩  디스크 공간 문제 찾기 및 해결                   | 초급    | [실습 시작](https://labex.io/ko/labs/find-and-fix-disk-space-issues-663384?course=lfcs-prep)                 |
|     3 | 🧩  systemctl 및 journalctl 을 이용한 서비스 점검 | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-services-with-systemctl-and-journalctl-663388?course=lfcs-prep) |
|     4 | 🧩  SSL 인증서 검사                          | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-ssl-certificates-663389?course=lfcs-prep)                       |
|     5 | 🧩  Git 을 이용한 설정 파일 추적                  | 초급    | [실습 시작](https://labex.io/ko/labs/track-configuration-with-git-663404?course=lfcs-prep)                   |

#### Users, Groups, and Access Control

|   인덱스 | 이름                 | 난이도   | 연습                                                                                           |
|-------|--------------------|-------|----------------------------------------------------------------------------------------------|
|     1 | 🧩  로컬 사용자 관리       | 초급    | [실습 시작](https://labex.io/ko/labs/manage-local-users-663391?course=lfcs-prep)                 |
|     2 | 🧩  로컬 그룹 및 멤버십 관리  | 초급    | [실습 시작](https://labex.io/ko/labs/manage-local-groups-and-membership-663390?course=lfcs-prep) |
|     3 | 🧩  제한된 sudo 액세스 구성 | 초급    | [실습 시작](https://labex.io/ko/labs/configure-limited-sudo-access-663368?course=lfcs-prep)      |
|     4 | 🧩  셸 환경 프로필 관리     | 초급    | [실습 시작](https://labex.io/ko/labs/manage-shell-environment-profiles-663393?course=lfcs-prep)  |
|     5 | 🧩  사용자 리소스 제한 구성   | 초급    | [실습 시작](https://labex.io/ko/labs/configure-user-resource-limits-663378?course=lfcs-prep)     |
|     6 | 🧩  파일 ACL 구성       | 초급    | [실습 시작](https://labex.io/ko/labs/configure-file-acls-663361?course=lfcs-prep)                |
|     7 | 🧩  LDAP 사용자 조회 구성  | 초급    | [실습 시작](https://labex.io/ko/labs/configure-ldap-user-lookup-663367?course=lfcs-prep)         |

#### Services, Jobs, Software, and Runtime

|   인덱스 | 이름                             | 난이도   | 연습                                                                                                        |
|-------|--------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|    01 | 🧩  프로세스 검사 및 관리                | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-and-manage-processes-663386?course=lfcs-prep)                    |
|    02 | 🧩  systemd 서비스 수명 주기 관리        | 초급    | [실습 시작](https://labex.io/ko/labs/manage-systemd-service-lifecycle-663395?course=lfcs-prep)                |
|    03 | 🧩  간단한 systemd 서비스 생성하기        | 초급    | [실습 시작](https://labex.io/ko/labs/create-a-simple-systemd-service-663381?course=lfcs-prep)                 |
|    04 | 🧩  실패한 systemd 서비스 문제 해결       | 초급    | [실습 시작](https://labex.io/ko/labs/troubleshoot-a-failed-systemd-service-663405?course=lfcs-prep)           |
|    05 | 🧩  서비스 리소스 제한 식별하기             | 초급    | [실습 시작](https://labex.io/ko/labs/identify-service-resource-constraints-663385?course=lfcs-prep)           |
|    06 | 🧩  cron 을 이용한 작업 스케줄링          | 초급    | [실습 시작](https://labex.io/ko/labs/schedule-jobs-with-cron-663401?course=lfcs-prep)                         |
|    07 | 🧩  systemd 타이머를 이용한 작업 예약      | 초급    | [실습 시작](https://labex.io/ko/labs/schedule-jobs-with-systemd-timers-663402?course=lfcs-prep)               |
|    08 | 🧩  소프트웨어 패키지 관리                | 초급    | [실습 시작](https://labex.io/ko/labs/manage-software-packages-663394?course=lfcs-prep)                        |
|    09 | 🧩  소프트웨어 저장소 구성                | 초급    | [실습 시작](https://labex.io/ko/labs/configure-software-repositories-663374?course=lfcs-prep)                 |
|    10 | 🧩  커널 파라미터 구성                  | 초급    | [실습 시작](https://labex.io/ko/labs/configure-kernel-parameters-663366?course=lfcs-prep)                     |
|    11 | 🧩  Safe OS 장애 상태 복구            | 초급    | [실습 시작](https://labex.io/ko/labs/recover-from-safe-os-failure-states-663399?course=lfcs-prep)             |
|    12 | 🧩  컨테이너 실행 및 관리                | 초급    | [실습 시작](https://labex.io/ko/labs/run-and-manage-containers-663400?course=lfcs-prep)                       |
|    13 | 🧩  SELinux 모드 및 컨텍스트 관리        | 초급    | [실습 시작](https://labex.io/ko/labs/manage-selinux-mode-and-contexts-663392?course=lfcs-prep)                |
|    14 | 🧩  libvirt 를 이용한 가상 머신 관리 살펴보기 | 초급    | [실습 시작](https://labex.io/ko/labs/explore-virtual-machine-management-with-libvirt-663382?course=lfcs-prep) |

#### Networking

|   인덱스 | 이름                          | 난이도   | 연습                                                                                                          |
|-------|-----------------------------|-------|-------------------------------------------------------------------------------------------------------------|
|    01 | 🧩  IPv4 네트워킹 및 호스트 이름 확인 구성 | 초급    | [실습 시작](https://labex.io/ko/labs/configure-ipv4-networking-and-hostname-resolution-663364?course=lfcs-prep) |
|    02 | 🧩  IPv6 주소 설정               | 초급    | [실습 시작](https://labex.io/ko/labs/configure-ipv6-addressing-663365?course=lfcs-prep)                         |
|    03 | 🧩  시스템 시간 동기화               | 초급    | [실습 시작](https://labex.io/ko/labs/synchronize-system-time-663403?course=lfcs-prep)                           |
|    04 | 🧩  네트워크 연결 문제 해결            | 초급    | [실습 시작](https://labex.io/ko/labs/troubleshoot-network-connectivity-663407?course=lfcs-prep)                 |
|    05 | 🧩  OpenSSH 클라이언트 액세스 구성     | 초급    | [실습 시작](https://labex.io/ko/labs/configure-openssh-client-access-663369?course=lfcs-prep)                   |
|    06 | 🧩  OpenSSH 서버 액세스 구성        | 초급    | [실습 시작](https://labex.io/ko/labs/configure-openssh-server-access-663370?course=lfcs-prep)                   |
|    07 | 🧩  방화벽 패킷 필터링 구성            | 초급    | [실습 시작](https://labex.io/ko/labs/configure-firewall-packet-filtering-663363?course=lfcs-prep)               |
|    08 | 🧩  정적 라우팅 구성                | 초급    | [실습 시작](https://labex.io/ko/labs/configure-static-routing-663375?course=lfcs-prep)                          |
|    09 | 🧩  포트 리다이렉션 및 NAT 구성        | 초급    | [실습 시작](https://labex.io/ko/labs/configure-port-redirection-and-nat-663372?course=lfcs-prep)                |
|    10 | 🧩  리버스 프록시 엔드포인트 구성         | 초급    | [실습 시작](https://labex.io/ko/labs/configure-a-reverse-proxy-endpoint-663373?course=lfcs-prep)                |
|    11 | 🧩  브리지 및 본드 장치 구성           | 초급    | [실습 시작](https://labex.io/ko/labs/configure-bridge-and-bond-devices-663360?course=lfcs-prep)                 |

#### Storage and Filesystems

|   인덱스 | 이름                       | 난이도   | 연습                                                                                                |
|-------|--------------------------|-------|---------------------------------------------------------------------------------------------------|
|    01 | 🧩  블록 장치 및 마운트 검사        | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-block-devices-and-mounts-663387?course=lfcs-prep)        |
|    02 | 🧩  파일 시스템 생성 및 마운트       | 초급    | [실습 시작](https://labex.io/ko/labs/create-and-mount-filesystems-663379?course=lfcs-prep)            |
|    03 | 🧩  영구 마운트 구성             | 초급    | [실습 시작](https://labex.io/ko/labs/configure-persistent-mounts-663371?course=lfcs-prep)             |
|    04 | 🧩  fstab 및 마운트 오류 문제 해결  | 초급    | [실습 시작](https://labex.io/ko/labs/troubleshoot-fstab-and-mount-failures-663406?course=lfcs-prep)   |
|    05 | 🧩  LVM 스토리지 생성           | 초급    | [실습 시작](https://labex.io/ko/labs/create-lvm-storage-663380?course=lfcs-prep)                      |
|    06 | 🧩  LVM 스토리지 확장           | 초급    | [실습 시작](https://labex.io/ko/labs/extend-lvm-storage-663383?course=lfcs-prep)                      |
|    07 | 🧩  스왑 공간 구성              | 초급    | [실습 시작](https://labex.io/ko/labs/configure-swap-space-663376?course=lfcs-prep)                    |
|    08 | 🧩  tmpfs 및 가상 파일 시스템 구성  | 초급    | [실습 시작](https://labex.io/ko/labs/configure-tmpfs-and-virtual-filesystems-663377?course=lfcs-prep) |
|    09 | 🧩  파일시스템 자동 마운트 구성       | 초급    | [실습 시작](https://labex.io/ko/labs/configure-filesystem-automounts-663362?course=lfcs-prep)         |
|    10 | 🧩  원격 파일 시스템 마운트         | 초급    | [실습 시작](https://labex.io/ko/labs/mount-remote-filesystems-663398?course=lfcs-prep)                |
|    11 | 🧩  네트워크 블록 장치 (NBD) 사용하기 | 초급    | [실습 시작](https://labex.io/ko/labs/use-network-block-devices-663408?course=lfcs-prep)               |
|    12 | 🧩  스토리지 성능 모니터링          | 초급    | [실습 시작](https://labex.io/ko/labs/monitor-storage-performance-663396?course=lfcs-prep)             |

### 2. [LFCS 실전 모의고사 01](https://labex.io/ko/courses/lfcs-practice-exam-01)

운영 및 배포, 네트워크, 스토리지, 필수 명령어, 사용자 및 그룹 관리 등 LFCS 의 핵심 영역을 다루는 20 개의 독립적인 리눅스 관리 실습 과제로 구성된 LFCS 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/lfcs-practice-exam-01) · 실습: 20

#### Operations and Deployment

|   인덱스 | 이름                    | 난이도   | 연습                                                                                                            |
|-------|-----------------------|-------|---------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  실패한 systemd 서비스 복구 | 초급    | [도전 시작](https://labex.io/ko/labs/repair-a-failed-systemd-service-662858?course=lfcs-practice-exam-01)         |
|     2 | 🎯  반복적인 유지보수 작업 예약    | 초급    | [도전 시작](https://labex.io/ko/labs/schedule-a-recurring-maintenance-job-662860?course=lfcs-practice-exam-01)    |
|     3 | 🎯  영구적인 커널 파라미터 구성    | 초급    | [도전 시작](https://labex.io/ko/labs/configure-a-persistent-kernel-parameter-662848?course=lfcs-practice-exam-01) |
|     4 | 🎯  필수 패키지 설치 및 검증     | 초급    | [도전 시작](https://labex.io/ko/labs/install-and-validate-a-required-package-662856?course=lfcs-practice-exam-01) |
|     5 | 🎯  로컬 컨테이너화된 서비스 실행   | 초급    | [도전 시작](https://labex.io/ko/labs/run-a-local-containerized-service-662859?course=lfcs-practice-exam-01)       |

#### Networking

|   인덱스 | 이름                         | 난이도   | 연습                                                                                                           |
|-------|----------------------------|-------|--------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  로컬 호스트 이름 확인 구성         | 초급    | [도전 시작](https://labex.io/ko/labs/configure-local-hostname-resolution-662846?course=lfcs-practice-exam-01)    |
|     2 | 🎯  OpenSSH 서버 보안 강화        | 초급    | [도전 시작](https://labex.io/ko/labs/secure-the-openssh-server-662861?course=lfcs-practice-exam-01)              |
|     3 | 🎯  방화벽을 통한 웹 트래픽 허용        | 초급    | [도전 시작](https://labex.io/ko/labs/allow-web-traffic-through-the-firewall-662844?course=lfcs-practice-exam-01) |
|     4 | 🎯  정적 경로 (Static Route) 구성 | 초급    | [도전 시작](https://labex.io/ko/labs/configure-a-static-route-662850?course=lfcs-practice-exam-01)               |
|     5 | 🎯  네트워크 시간 동기화 구성          | 초급    | [도전 시작](https://labex.io/ko/labs/configure-network-time-synchronization-662847?course=lfcs-practice-exam-01) |

#### Storage

|   인덱스 | 이름                 | 난이도   | 연습                                                                                                   |
|-------|--------------------|-------|------------------------------------------------------------------------------------------------------|
|     1 | 🎯  영구 파일 시스템 생성    | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-persistent-filesystem-662854?course=lfcs-practice-exam-01) |
|     2 | 🎯  LVM 논리 볼륨 생성    | 초급    | [도전 시작](https://labex.io/ko/labs/create-an-lvm-logical-volume-662853?course=lfcs-practice-exam-01)   |
|     3 | 🎯  영구 스왑 (Swap) 구성 | 초급    | [도전 시작](https://labex.io/ko/labs/configure-persistent-swap-662849?course=lfcs-practice-exam-01)      |
|     4 | 🎯  손상된 fstab 항목 복구 | 초급    | [도전 시작](https://labex.io/ko/labs/repair-a-broken-fstab-entry-662857?course=lfcs-practice-exam-01)    |

#### Essential Commands

|   인덱스 | 이름                       | 난이도   | 연습                                                                                                         |
|-------|--------------------------|-------|------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  Git 을 이용한 구성 변경 사항 추적 | 초급    | [도전 시작](https://labex.io/ko/labs/track-configuration-changes-with-git-662862?course=lfcs-practice-exam-01) |
|     2 | 🎯  디스크 사용량 문제 해결         | 초급    | [도전 시작](https://labex.io/ko/labs/troubleshoot-disk-usage-662863?course=lfcs-practice-exam-01)              |
|     3 | 🎯  TLS 인증서 검사            | 초급    | [도전 시작](https://labex.io/ko/labs/inspect-a-tls-certificate-662855?course=lfcs-practice-exam-01)            |
|     4 | 🎯  서비스 리소스 사용량 분석        | 초급    | [도전 시작](https://labex.io/ko/labs/analyze-service-resource-usage-662845?course=lfcs-practice-exam-01)       |

#### Users and Groups

|   인덱스 | 이름                | 난이도   | 연습                                                                                                   |
|-------|-------------------|-------|------------------------------------------------------------------------------------------------------|
|     1 | 🎯  제한된 관리자 사용자 생성 | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-limited-admin-user-662852?course=lfcs-practice-exam-01)    |
|     2 | 🎯  사용자 리소스 제한 구성  | 초급    | [도전 시작](https://labex.io/ko/labs/configure-user-resource-limits-662851?course=lfcs-practice-exam-01) |

### 3. [LFCS Practice Exam 02](https://labex.io/ko/courses/lfcs-practice-exam-02)

A second independent LFCS-style practice exam with 20 hands-on Linux administration challenges covering operations and deployment, networking, storage, essential commands, and users and groups.

[코스 시작](https://labex.io/ko/courses/lfcs-practice-exam-02) · 실습: 20

#### Operations and Deployment

|   인덱스 | 이름                          | 난이도   | 연습                                                                                                                |
|-------|-----------------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  상태 확인을 위한 Systemd 타이머 생성 | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-systemd-timer-for-health-checks-662874?course=lfcs-practice-exam-02)    |
|     2 | 🎯  로컬 APT 저장소 구성            | 초급    | [도전 시작](https://labex.io/ko/labs/configure-a-local-apt-repository-662868?course=lfcs-practice-exam-02)            |
|     3 | 🎯  잘못 구성된 서비스 환경 복구         | 초급    | [도전 시작](https://labex.io/ko/labs/recover-a-misconfigured-service-environment-662878?course=lfcs-practice-exam-02) |
|     4 | 🎯  지속 가능한 컨테이너 워커 실행        | 초급    | [도전 시작](https://labex.io/ko/labs/run-a-persistent-container-worker-662882?course=lfcs-practice-exam-02)           |
|     5 | 🎯  안전한 유지보수 차단 요소 제거        | 초급    | [도전 시작](https://labex.io/ko/labs/clear-a-safe-maintenance-blocker-662865?course=lfcs-practice-exam-02)            |

#### Networking

|   인덱스 | 이름                  | 난이도   | 연습                                                                                                       |
|-------|---------------------|-------|----------------------------------------------------------------------------------------------------------|
|     1 | 🎯  IPv6 주소 구성       | 초급    | [도전 시작](https://labex.io/ko/labs/configure-ipv6-addressing-662867?course=lfcs-practice-exam-02)          |
|     2 | 🎯  로컬 서비스 포트 문제 해결  | 초급    | [도전 시작](https://labex.io/ko/labs/troubleshoot-a-local-service-port-662883?course=lfcs-practice-exam-02)  |
|     3 | 🎯  SSH 클라이언트 액세스 구성 | 초급    | [도전 시작](https://labex.io/ko/labs/configure-ssh-client-access-662872?course=lfcs-practice-exam-02)        |
|     4 | 🎯  로컬 TCP 포트 리다이렉트  | 초급    | [도전 시작](https://labex.io/ko/labs/redirect-a-local-tcp-port-662879?course=lfcs-practice-exam-02)          |
|     5 | 🎯  리버스 프록시 엔드포인트 구성 | 초급    | [도전 시작](https://labex.io/ko/labs/configure-a-reverse-proxy-endpoint-662869?course=lfcs-practice-exam-02) |

#### Storage

|   인덱스 | 이름                     | 난이도   | 연습                                                                                                             |
|-------|------------------------|-------|----------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  LVM 논리 볼륨 확장        | 초급    | [도전 시작](https://labex.io/ko/labs/extend-an-lvm-logical-volume-662876?course=lfcs-practice-exam-02)             |
|     2 | 🎯  임시 런타임 파일 시스템 구성    | 초급    | [도전 시작](https://labex.io/ko/labs/configure-a-temporary-runtime-filesystem-662870?course=lfcs-practice-exam-02) |
|     3 | 🎯  온디맨드 아카이브 마운트 구성    | 초급    | [도전 시작](https://labex.io/ko/labs/configure-an-on-demand-archive-mount-662866?course=lfcs-practice-exam-02)     |
|     4 | 🎯  파일 시스템 이미지 복구 및 마운트 | 초급    | [도전 시작](https://labex.io/ko/labs/repair-and-mount-a-filesystem-image-662880?course=lfcs-practice-exam-02)      |

#### Essential Commands

|   인덱스 | 이름                 | 난이도   | 연습                                                                                                         |
|-------|--------------------|-------|------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  Git 을 이용한 설정 복구 | 초급    | [도전 시작](https://labex.io/ko/labs/restore-a-configuration-from-git-662881?course=lfcs-practice-exam-02)     |
|     2 | 🎯  실패한 로그인 이벤트 추출  | 초급    | [도전 시작](https://labex.io/ko/labs/extract-failed-login-events-662877?course=lfcs-practice-exam-02)          |
|     3 | 🎯  검증된 백업 아카이브 생성  | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-verified-backup-archive-662875?course=lfcs-practice-exam-02)     |
|     4 | 🎯  서비스 제약 실패 분석    | 초급    | [도전 시작](https://labex.io/ko/labs/analyze-a-service-constraint-failure-662864?course=lfcs-practice-exam-02) |

#### Users and Groups

|   인덱스 | 이름                  | 난이도   | 연습                                                                                                        |
|-------|---------------------|-------|-----------------------------------------------------------------------------------------------------------|
|     1 | 🎯  공유 디렉토리 ACL 구성   | 초급    | [도전 시작](https://labex.io/ko/labs/configure-shared-directory-acls-662871?course=lfcs-practice-exam-02)     |
|     2 | 🎯  제어 가능한 서비스 계정 생성 | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-controlled-service-account-662873?course=lfcs-practice-exam-02) |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

