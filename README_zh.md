# LFCS 培训 认证备考路径

## 支持语言

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/zh/learn/lfcs"><img width="128px" src="https://file.labex.io/path/OMeAELrqi3Ff.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/开始路径-whitesmoke?style=for-the-badge)](https://labex.io/zh/learn/lfcs)

通过结构化的动手学习路径备考 Linux 基金会认证系统管理员（LFCS）考试。本路线图侧重主流发行版上的实践型 Linux 管理、性能型考试任务与真实场景。后续将逐步加入 LFCS 课程、实验环境与模拟考试练习，帮助你建立与 LFCS 目标一致的命令行熟练度、服务管理、存储、网络、安全与故障排查能力。

**课程**: 3 · **实验**: 89

## 课程

### 1. [LFCS 备考指南](https://labex.io/zh/courses/lfcs-prep)

专为初学者设计的 LFCS 备考课程，包含 49 个引导式 Linux 管理实验，内容涵盖从基础命令工作流到用户管理、服务配置、网络设置及存储管理等核心领域。

[开始课程](https://labex.io/zh/courses/lfcs-prep) · 实验: 49

#### Essential Command Workflows

|   序号 | 名称                                | 难度   | 练习                                                                                                      |
|------|-----------------------------------|------|---------------------------------------------------------------------------------------------------------|
|    1 | 🧩  监控系统性能                         | 初级   | [开始实验](https://labex.io/zh/labs/monitor-system-performance-663397?course=lfcs-prep)                     |
|    2 | 🧩  查找并修复磁盘空间问题                    | 初级   | [开始实验](https://labex.io/zh/labs/find-and-fix-disk-space-issues-663384?course=lfcs-prep)                 |
|    3 | 🧩  使用 systemctl 和 journalctl 检查服务 | 初级   | [开始实验](https://labex.io/zh/labs/inspect-services-with-systemctl-and-journalctl-663388?course=lfcs-prep) |
|    4 | 🧩  检查 SSL 证书                      | 初级   | [开始实验](https://labex.io/zh/labs/inspect-ssl-certificates-663389?course=lfcs-prep)                       |
|    5 | 🧩  使用 Git 跟踪配置文件                  | 初级   | [开始实验](https://labex.io/zh/labs/track-configuration-with-git-663404?course=lfcs-prep)                   |

#### Users, Groups, and Access Control

|   序号 | 名称                 | 难度   | 练习                                                                                          |
|------|--------------------|------|---------------------------------------------------------------------------------------------|
|    1 | 🧩  管理本地用户          | 初级   | [开始实验](https://labex.io/zh/labs/manage-local-users-663391?course=lfcs-prep)                 |
|    2 | 🧩  管理本地组与成员资格      | 初级   | [开始实验](https://labex.io/zh/labs/manage-local-groups-and-membership-663390?course=lfcs-prep) |
|    3 | 🧩  配置受限的 sudo 访问权限 | 初级   | [开始实验](https://labex.io/zh/labs/configure-limited-sudo-access-663368?course=lfcs-prep)      |
|    4 | 🧩  管理 Shell 环境配置文件 | 初级   | [开始实验](https://labex.io/zh/labs/manage-shell-environment-profiles-663393?course=lfcs-prep)  |
|    5 | 🧩  配置用户资源限制        | 初级   | [开始实验](https://labex.io/zh/labs/configure-user-resource-limits-663378?course=lfcs-prep)     |
|    6 | 🧩  配置文件 ACL        | 初级   | [开始实验](https://labex.io/zh/labs/configure-file-acls-663361?course=lfcs-prep)                |
|    7 | 🧩  配置 LDAP 用户查询    | 初级   | [开始实验](https://labex.io/zh/labs/configure-ldap-user-lookup-663367?course=lfcs-prep)         |

#### Services, Jobs, Software, and Runtime

|   序号 | 名称                    | 难度   | 练习                                                                                                       |
|------|-----------------------|------|----------------------------------------------------------------------------------------------------------|
|   01 | 🧩  检查与管理进程            | 初级   | [开始实验](https://labex.io/zh/labs/inspect-and-manage-processes-663386?course=lfcs-prep)                    |
|   02 | 🧩  管理 systemd 服务生命周期  | 初级   | [开始实验](https://labex.io/zh/labs/manage-systemd-service-lifecycle-663395?course=lfcs-prep)                |
|   03 | 🧩  创建简单的 systemd 服务   | 初级   | [开始实验](https://labex.io/zh/labs/create-a-simple-systemd-service-663381?course=lfcs-prep)                 |
|   04 | 🧩  排查 systemd 服务故障    | 初级   | [开始实验](https://labex.io/zh/labs/troubleshoot-a-failed-systemd-service-663405?course=lfcs-prep)           |
|   05 | 🧩  识别服务资源限制           | 初级   | [开始实验](https://labex.io/zh/labs/identify-service-resource-constraints-663385?course=lfcs-prep)           |
|   06 | 🧩  使用 cron 调度任务       | 初级   | [开始实验](https://labex.io/zh/labs/schedule-jobs-with-cron-663401?course=lfcs-prep)                         |
|   07 | 🧩  使用 systemd 定时器调度任务 | 初级   | [开始实验](https://labex.io/zh/labs/schedule-jobs-with-systemd-timers-663402?course=lfcs-prep)               |
|   08 | 🧩  管理软件包              | 初级   | [开始实验](https://labex.io/zh/labs/manage-software-packages-663394?course=lfcs-prep)                        |
|   09 | 🧩  配置软件仓库             | 初级   | [开始实验](https://labex.io/zh/labs/configure-software-repositories-663374?course=lfcs-prep)                 |
|   10 | 🧩  配置内核参数             | 初级   | [开始实验](https://labex.io/zh/labs/configure-kernel-parameters-663366?course=lfcs-prep)                     |
|   11 | 🧩  从安全操作系统故障状态中恢复     | 初级   | [开始实验](https://labex.io/zh/labs/recover-from-safe-os-failure-states-663399?course=lfcs-prep)             |
|   12 | 🧩  运行与管理容器            | 初级   | [开始实验](https://labex.io/zh/labs/run-and-manage-containers-663400?course=lfcs-prep)                       |
|   13 | 🧩  管理 SELinux 模式与上下文  | 初级   | [开始实验](https://labex.io/zh/labs/manage-selinux-mode-and-contexts-663392?course=lfcs-prep)                |
|   14 | 🧩  使用 libvirt 探索虚拟机管理 | 初级   | [开始实验](https://labex.io/zh/labs/explore-virtual-machine-management-with-libvirt-663382?course=lfcs-prep) |

#### Networking

|   序号 | 名称                  | 难度   | 练习                                                                                                         |
|------|---------------------|------|------------------------------------------------------------------------------------------------------------|
|   01 | 🧩  配置 IPv4 网络与主机名解析 | 初级   | [开始实验](https://labex.io/zh/labs/configure-ipv4-networking-and-hostname-resolution-663364?course=lfcs-prep) |
|   02 | 🧩  配置 IPv6 地址       | 初级   | [开始实验](https://labex.io/zh/labs/configure-ipv6-addressing-663365?course=lfcs-prep)                         |
|   03 | 🧩  同步系统时间           | 初级   | [开始实验](https://labex.io/zh/labs/synchronize-system-time-663403?course=lfcs-prep)                           |
|   04 | 🧩  排查网络连接故障         | 初级   | [开始实验](https://labex.io/zh/labs/troubleshoot-network-connectivity-663407?course=lfcs-prep)                 |
|   05 | 🧩  配置 OpenSSH 客户端访问 | 初级   | [开始实验](https://labex.io/zh/labs/configure-openssh-client-access-663369?course=lfcs-prep)                   |
|   06 | 🧩  配置 OpenSSH 服务器访问 | 初级   | [开始实验](https://labex.io/zh/labs/configure-openssh-server-access-663370?course=lfcs-prep)                   |
|   07 | 🧩  配置防火墙包过滤         | 初级   | [开始实验](https://labex.io/zh/labs/configure-firewall-packet-filtering-663363?course=lfcs-prep)               |
|   08 | 🧩  配置静态路由           | 初级   | [开始实验](https://labex.io/zh/labs/configure-static-routing-663375?course=lfcs-prep)                          |
|   09 | 🧩  配置端口重定向与 NAT     | 初级   | [开始实验](https://labex.io/zh/labs/configure-port-redirection-and-nat-663372?course=lfcs-prep)                |
|   10 | 🧩  配置反向代理端点         | 初级   | [开始实验](https://labex.io/zh/labs/configure-a-reverse-proxy-endpoint-663373?course=lfcs-prep)                |
|   11 | 🧩  配置网桥与绑定设备        | 初级   | [开始实验](https://labex.io/zh/labs/configure-bridge-and-bond-devices-663360?course=lfcs-prep)                 |

#### Storage and Filesystems

|   序号 | 名称                  | 难度   | 练习                                                                                               |
|------|---------------------|------|--------------------------------------------------------------------------------------------------|
|   01 | 🧩  检查块设备与挂载点        | 初级   | [开始实验](https://labex.io/zh/labs/inspect-block-devices-and-mounts-663387?course=lfcs-prep)        |
|   02 | 🧩  创建并挂载文件系统        | 初级   | [开始实验](https://labex.io/zh/labs/create-and-mount-filesystems-663379?course=lfcs-prep)            |
|   03 | 🧩  配置持久化挂载          | 初级   | [开始实验](https://labex.io/zh/labs/configure-persistent-mounts-663371?course=lfcs-prep)             |
|   04 | 🧩  排查 fstab 与挂载故障   | 初级   | [开始实验](https://labex.io/zh/labs/troubleshoot-fstab-and-mount-failures-663406?course=lfcs-prep)   |
|   05 | 🧩  创建 LVM 存储        | 初级   | [开始实验](https://labex.io/zh/labs/create-lvm-storage-663380?course=lfcs-prep)                      |
|   06 | 🧩  扩展 LVM 存储        | 初级   | [开始实验](https://labex.io/zh/labs/extend-lvm-storage-663383?course=lfcs-prep)                      |
|   07 | 🧩  配置交换空间           | 初级   | [开始实验](https://labex.io/zh/labs/configure-swap-space-663376?course=lfcs-prep)                    |
|   08 | 🧩  配置 tmpfs 和虚拟文件系统 | 初级   | [开始实验](https://labex.io/zh/labs/configure-tmpfs-and-virtual-filesystems-663377?course=lfcs-prep) |
|   09 | 🧩  配置文件系统自动挂载       | 初级   | [开始实验](https://labex.io/zh/labs/configure-filesystem-automounts-663362?course=lfcs-prep)         |
|   10 | 🧩  挂载远程文件系统         | 初级   | [开始实验](https://labex.io/zh/labs/mount-remote-filesystems-663398?course=lfcs-prep)                |
|   11 | 🧩  使用网络块设备 (NBD)    | 初级   | [开始实验](https://labex.io/zh/labs/use-network-block-devices-663408?course=lfcs-prep)               |
|   12 | 🧩  监控存储性能           | 初级   | [开始实验](https://labex.io/zh/labs/monitor-storage-performance-663396?course=lfcs-prep)             |

### 2. [LFCS 模拟考试 01](https://labex.io/zh/courses/lfcs-practice-exam-01)

这是一场实战型 LFCS 模拟考试，包含 20 个独立的 Linux 系统管理挑战，涵盖了运维与部署、网络、存储、基础命令以及用户与用户组管理等核心领域。

[开始课程](https://labex.io/zh/courses/lfcs-practice-exam-01) · 实验: 20

#### Operations and Deployment

|   序号 | 名称                  | 难度   | 练习                                                                                                           |
|------|---------------------|------|--------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复故障的 systemd 服务 | 初级   | [开始挑战](https://labex.io/zh/labs/repair-a-failed-systemd-service-662858?course=lfcs-practice-exam-01)         |
|    2 | 🎯  调度周期性维护任务        | 初级   | [开始挑战](https://labex.io/zh/labs/schedule-a-recurring-maintenance-job-662860?course=lfcs-practice-exam-01)    |
|    3 | 🎯  配置持久化内核参数        | 初级   | [开始挑战](https://labex.io/zh/labs/configure-a-persistent-kernel-parameter-662848?course=lfcs-practice-exam-01) |
|    4 | 🎯  安装并验证所需的软件包      | 初级   | [开始挑战](https://labex.io/zh/labs/install-and-validate-a-required-package-662856?course=lfcs-practice-exam-01) |
|    5 | 🎯  运行本地容器化服务        | 初级   | [开始挑战](https://labex.io/zh/labs/run-a-local-containerized-service-662859?course=lfcs-practice-exam-01)       |

#### Networking

|   序号 | 名称                | 难度   | 练习                                                                                                          |
|------|-------------------|------|-------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  配置本地主机名解析      | 初级   | [开始挑战](https://labex.io/zh/labs/configure-local-hostname-resolution-662846?course=lfcs-practice-exam-01)    |
|    2 | 🎯  加固 OpenSSH 服务器 | 初级   | [开始挑战](https://labex.io/zh/labs/secure-the-openssh-server-662861?course=lfcs-practice-exam-01)              |
|    3 | 🎯  通过防火墙允许 Web 流量 | 初级   | [开始挑战](https://labex.io/zh/labs/allow-web-traffic-through-the-firewall-662844?course=lfcs-practice-exam-01) |
|    4 | 🎯  配置静态路由         | 初级   | [开始挑战](https://labex.io/zh/labs/configure-a-static-route-662850?course=lfcs-practice-exam-01)               |
|    5 | 🎯  配置网络时间同步       | 初级   | [开始挑战](https://labex.io/zh/labs/configure-network-time-synchronization-662847?course=lfcs-practice-exam-01) |

#### Storage

|   序号 | 名称                | 难度   | 练习                                                                                                  |
|------|-------------------|------|-----------------------------------------------------------------------------------------------------|
|    1 | 🎯  创建持久化文件系统      | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-persistent-filesystem-662854?course=lfcs-practice-exam-01) |
|    2 | 🎯  创建 LVM 逻辑卷     | 初级   | [开始挑战](https://labex.io/zh/labs/create-an-lvm-logical-volume-662853?course=lfcs-practice-exam-01)   |
|    3 | 🎯  配置持久化交换空间      | 初级   | [开始挑战](https://labex.io/zh/labs/configure-persistent-swap-662849?course=lfcs-practice-exam-01)      |
|    4 | 🎯  修复损坏的 fstab 条目 | 初级   | [开始挑战](https://labex.io/zh/labs/repair-a-broken-fstab-entry-662857?course=lfcs-practice-exam-01)    |

#### Essential Commands

|   序号 | 名称               | 难度   | 练习                                                                                                        |
|------|------------------|------|-----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 Git 跟踪配置变更 | 初级   | [开始挑战](https://labex.io/zh/labs/track-configuration-changes-with-git-662862?course=lfcs-practice-exam-01) |
|    2 | 🎯  排查磁盘使用情况      | 初级   | [开始挑战](https://labex.io/zh/labs/troubleshoot-disk-usage-662863?course=lfcs-practice-exam-01)              |
|    3 | 🎯  检查 TLS 证书     | 初级   | [开始挑战](https://labex.io/zh/labs/inspect-a-tls-certificate-662855?course=lfcs-practice-exam-01)            |
|    4 | 🎯  分析服务资源使用情况    | 初级   | [开始挑战](https://labex.io/zh/labs/analyze-service-resource-usage-662845?course=lfcs-practice-exam-01)       |

#### Users and Groups

|   序号 | 名称           | 难度   | 练习                                                                                                  |
|------|--------------|------|-----------------------------------------------------------------------------------------------------|
|    1 | 🎯  创建受限管理员用户 | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-limited-admin-user-662852?course=lfcs-practice-exam-01)    |
|    2 | 🎯  配置用户资源限制  | 初级   | [开始挑战](https://labex.io/zh/labs/configure-user-resource-limits-662851?course=lfcs-practice-exam-01) |

### 3. [LFCS 模拟考试 02](https://labex.io/zh/courses/lfcs-practice-exam-02)

第二套独立的 LFCS 风格模拟考试，包含 20 个 Linux 系统管理实战挑战，涵盖运维与部署、网络、存储、基础命令以及用户与用户组管理。

[开始课程](https://labex.io/zh/courses/lfcs-practice-exam-02) · 实验: 20

#### Operations and Deployment

|   序号 | 名称                     | 难度   | 练习                                                                                                               |
|------|------------------------|------|------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  为健康检查创建 Systemd 定时器 | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-systemd-timer-for-health-checks-662874?course=lfcs-practice-exam-02)    |
|    2 | 🎯  配置本地 APT 仓库         | 初级   | [开始挑战](https://labex.io/zh/labs/configure-a-local-apt-repository-662868?course=lfcs-practice-exam-02)            |
|    3 | 🎯  恢复配置错误的系统服务         | 初级   | [开始挑战](https://labex.io/zh/labs/recover-a-misconfigured-service-environment-662878?course=lfcs-practice-exam-02) |
|    4 | 🎯  运行一个持久化的容器工作进程      | 初级   | [开始挑战](https://labex.io/zh/labs/run-a-persistent-container-worker-662882?course=lfcs-practice-exam-02)           |
|    5 | 🎯  清除安全维护阻塞            | 初级   | [开始挑战](https://labex.io/zh/labs/clear-a-safe-maintenance-blocker-662865?course=lfcs-practice-exam-02)            |

#### Networking

|   序号 | 名称              | 难度   | 练习                                                                                                      |
|------|-----------------|------|---------------------------------------------------------------------------------------------------------|
|    1 | 🎯  配置 IPv6 地址   | 初级   | [开始挑战](https://labex.io/zh/labs/configure-ipv6-addressing-662867?course=lfcs-practice-exam-02)          |
|    2 | 🎯  排查本地服务端口     | 初级   | [开始挑战](https://labex.io/zh/labs/troubleshoot-a-local-service-port-662883?course=lfcs-practice-exam-02)  |
|    3 | 🎯  配置 SSH 客户端访问 | 初级   | [开始挑战](https://labex.io/zh/labs/configure-ssh-client-access-662872?course=lfcs-practice-exam-02)        |
|    4 | 🎯  重定向本地 TCP 端口 | 初级   | [开始挑战](https://labex.io/zh/labs/redirect-a-local-tcp-port-662879?course=lfcs-practice-exam-02)          |
|    5 | 🎯  配置反向代理端点     | 初级   | [开始挑战](https://labex.io/zh/labs/configure-a-reverse-proxy-endpoint-662869?course=lfcs-practice-exam-02) |

#### Storage

|   序号 | 名称             | 难度   | 练习                                                                                                            |
|------|----------------|------|---------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  扩展 LVM 逻辑卷  | 初级   | [开始挑战](https://labex.io/zh/labs/extend-an-lvm-logical-volume-662876?course=lfcs-practice-exam-02)             |
|    2 | 🎯  配置临时运行时文件系统 | 初级   | [开始挑战](https://labex.io/zh/labs/configure-a-temporary-runtime-filesystem-662870?course=lfcs-practice-exam-02) |
|    3 | 🎯  配置按需挂载的归档文件 | 初级   | [开始挑战](https://labex.io/zh/labs/configure-an-on-demand-archive-mount-662866?course=lfcs-practice-exam-02)     |
|    4 | 🎯  修复并挂载文件系统镜像 | 初级   | [开始挑战](https://labex.io/zh/labs/repair-and-mount-a-filesystem-image-662880?course=lfcs-practice-exam-02)      |

#### Essential Commands

|   序号 | 名称            | 难度   | 练习                                                                                                        |
|------|---------------|------|-----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  从 Git 恢复配置 | 初级   | [开始挑战](https://labex.io/zh/labs/restore-a-configuration-from-git-662881?course=lfcs-practice-exam-02)     |
|    2 | 🎯  提取失败的登录事件  | 初级   | [开始挑战](https://labex.io/zh/labs/extract-failed-login-events-662877?course=lfcs-practice-exam-02)          |
|    3 | 🎯  创建已验证的备份归档 | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-verified-backup-archive-662875?course=lfcs-practice-exam-02)     |
|    4 | 🎯  分析服务约束故障   | 初级   | [开始挑战](https://labex.io/zh/labs/analyze-a-service-constraint-failure-662864?course=lfcs-practice-exam-02) |

#### Users and Groups

|   序号 | 名称            | 难度   | 练习                                                                                                       |
|------|---------------|------|----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  配置共享目录 ACL | 初级   | [开始挑战](https://labex.io/zh/labs/configure-shared-directory-acls-662871?course=lfcs-practice-exam-02)     |
|    2 | 🎯  创建受控服务账户   | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-controlled-service-account-662873?course=lfcs-practice-exam-02) |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

