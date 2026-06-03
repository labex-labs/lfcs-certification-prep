# LFCS トレーニング 認定試験準備パス

## 言語

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/ja/learn/lfcs"><img width="128px" src="https://file.labex.io/path/OMeAELrqi3Ff.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/パスを開始-whitesmoke?style=for-the-badge)](https://labex.io/ja/learn/lfcs)

Linux Foundation Certified System Administrator（LFCS）試験に向けた、体系的かつ実践的な学習パスです。主要ディストリビューションにおける実務的な Linux 管理、パフォーマンスベースのタスク、現実のシナリオに焦点を当てます。LFCS コース、ラボ、模擬試験の演習は順次追加され、LFCS の目標に沿ったコマンドラインの習熟、サービス管理、ストレージ、ネットワーク、セキュリティ、トラブルシューティングスキルを育成します。

**コース**: 3 · **ラボ**: 89

## コース

### 1. [LFCS 対策コース](https://labex.io/ja/courses/lfcs-prep)

初心者向けの LFCS 対策コースです。Linux 管理の基本コマンドから、ユーザー管理、サービス運用、ネットワーク、ストレージまで、49 のガイド付き実験を通じて体系的に学習できます。

[コースを開始](https://labex.io/ja/courses/lfcs-prep) · ラボ: 49

#### Essential Command Workflows

|   インデックス | 名前                                     | 難易度   | 練習                                                                                                       |
|----------|----------------------------------------|-------|----------------------------------------------------------------------------------------------------------|
|        1 | 🧩  システムパフォーマンスの監視                      | 初級    | [ラボを開始](https://labex.io/ja/labs/monitor-system-performance-663397?course=lfcs-prep)                     |
|        2 | 🧩  ディスク容量の問題を特定して解決する                  | 初級    | [ラボを開始](https://labex.io/ja/labs/find-and-fix-disk-space-issues-663384?course=lfcs-prep)                 |
|        3 | 🧩  systemctl と journalctl を使用したサービスの調査 | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-services-with-systemctl-and-journalctl-663388?course=lfcs-prep) |
|        4 | 🧩  SSL 証明書の調査                          | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-ssl-certificates-663389?course=lfcs-prep)                       |
|        5 | 🧩  Git による設定ファイルの管理                    | 初級    | [ラボを開始](https://labex.io/ja/labs/track-configuration-with-git-663404?course=lfcs-prep)                   |

#### Users, Groups, and Access Control

|   インデックス | 名前                     | 難易度   | 練習                                                                                           |
|----------|------------------------|-------|----------------------------------------------------------------------------------------------|
|        1 | 🧩  ローカルユーザーの管理         | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-local-users-663391?course=lfcs-prep)                 |
|        2 | 🧩  ローカルグループとメンバーシップの管理 | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-local-groups-and-membership-663390?course=lfcs-prep) |
|        3 | 🧩  限定的な sudo アクセスの設定   | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-limited-sudo-access-663368?course=lfcs-prep)      |
|        4 | 🧩  シェル環境プロファイルの管理      | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-shell-environment-profiles-663393?course=lfcs-prep)  |
|        5 | 🧩  ユーザーリソース制限の設定       | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-user-resource-limits-663378?course=lfcs-prep)     |
|        6 | 🧩  ファイル ACL の設定        | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-file-acls-663361?course=lfcs-prep)                |
|        7 | 🧩  LDAP ユーザー検索の設定      | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-ldap-user-lookup-663367?course=lfcs-prep)         |

#### Services, Jobs, Software, and Runtime

|   インデックス | 名前                               | 難易度   | 練習                                                                                                        |
|----------|----------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|       01 | 🧩  プロセスの調査と管理                    | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-and-manage-processes-663386?course=lfcs-prep)                    |
|       02 | 🧩  systemd サービスライフサイクルの管理        | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-systemd-service-lifecycle-663395?course=lfcs-prep)                |
|       03 | 🧩  シンプルな systemd サービスの作成         | 初級    | [ラボを開始](https://labex.io/ja/labs/create-a-simple-systemd-service-663381?course=lfcs-prep)                 |
|       04 | 🧩  失敗した systemd サービスのトラブルシューティング | 初級    | [ラボを開始](https://labex.io/ja/labs/troubleshoot-a-failed-systemd-service-663405?course=lfcs-prep)           |
|       05 | 🧩  サービスのリソース制限を特定する              | 初級    | [ラボを開始](https://labex.io/ja/labs/identify-service-resource-constraints-663385?course=lfcs-prep)           |
|       06 | 🧩  cron を使用したジョブのスケジュール          | 初級    | [ラボを開始](https://labex.io/ja/labs/schedule-jobs-with-cron-663401?course=lfcs-prep)                         |
|       07 | 🧩  systemd タイマーによるジョブのスケジュール     | 初級    | [ラボを開始](https://labex.io/ja/labs/schedule-jobs-with-systemd-timers-663402?course=lfcs-prep)               |
|       08 | 🧩  ソフトウェアパッケージの管理                | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-software-packages-663394?course=lfcs-prep)                        |
|       09 | 🧩  ソフトウェアリポジトリの設定                | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-software-repositories-663374?course=lfcs-prep)                 |
|       10 | 🧩  カーネルパラメータの設定                  | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-kernel-parameters-663366?course=lfcs-prep)                     |
|       11 | 🧩  セーフ OS 障害状態からの復旧              | 初級    | [ラボを開始](https://labex.io/ja/labs/recover-from-safe-os-failure-states-663399?course=lfcs-prep)             |
|       12 | 🧩  コンテナの実行と管理                    | 初級    | [ラボを開始](https://labex.io/ja/labs/run-and-manage-containers-663400?course=lfcs-prep)                       |
|       13 | 🧩  SELinux モードとコンテキストの管理         | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-selinux-mode-and-contexts-663392?course=lfcs-prep)                |
|       14 | 🧩  libvirt を使用した仮想マシン管理の探索       | 初級    | [ラボを開始](https://labex.io/ja/labs/explore-virtual-machine-management-with-libvirt-663382?course=lfcs-prep) |

#### Networking

|   インデックス | 名前                           | 難易度   | 練習                                                                                                          |
|----------|------------------------------|-------|-------------------------------------------------------------------------------------------------------------|
|       01 | 🧩  IPv4 ネットワークとホスト名解決の設定     | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-ipv4-networking-and-hostname-resolution-663364?course=lfcs-prep) |
|       02 | 🧩  IPv6 アドレスの設定              | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-ipv6-addressing-663365?course=lfcs-prep)                         |
|       03 | 🧩  システム時刻の同期                 | 初級    | [ラボを開始](https://labex.io/ja/labs/synchronize-system-time-663403?course=lfcs-prep)                           |
|       04 | 🧩  ネットワーク接続のトラブルシューティング      | 初級    | [ラボを開始](https://labex.io/ja/labs/troubleshoot-network-connectivity-663407?course=lfcs-prep)                 |
|       05 | 🧩  OpenSSH クライアントアクセスの設定     | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-openssh-client-access-663369?course=lfcs-prep)                   |
|       06 | 🧩  OpenSSH サーバーアクセスの設定       | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-openssh-server-access-663370?course=lfcs-prep)                   |
|       07 | 🧩  ファイアウォールによるパケットフィルタリングの設定 | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-firewall-packet-filtering-663363?course=lfcs-prep)               |
|       08 | 🧩  静的ルーティングの設定               | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-static-routing-663375?course=lfcs-prep)                          |
|       09 | 🧩  ポートリダイレクトと NAT の設定        | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-port-redirection-and-nat-663372?course=lfcs-prep)                |
|       10 | 🧩  リバースプロキシエンドポイントの設定        | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-a-reverse-proxy-endpoint-663373?course=lfcs-prep)                |
|       11 | 🧩  ブリッジおよびボンドデバイスの設定         | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-bridge-and-bond-devices-663360?course=lfcs-prep)                 |

#### Storage and Filesystems

|   インデックス | 名前                           | 難易度   | 練習                                                                                                |
|----------|------------------------------|-------|---------------------------------------------------------------------------------------------------|
|       01 | 🧩  ブロックデバイスとマウントの調査          | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-block-devices-and-mounts-663387?course=lfcs-prep)        |
|       02 | 🧩  ファイルシステムの作成とマウント          | 初級    | [ラボを開始](https://labex.io/ja/labs/create-and-mount-filesystems-663379?course=lfcs-prep)            |
|       03 | 🧩  永続マウントの設定                 | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-persistent-mounts-663371?course=lfcs-prep)             |
|       04 | 🧩  fstab とマウント失敗のトラブルシューティング | 初級    | [ラボを開始](https://labex.io/ja/labs/troubleshoot-fstab-and-mount-failures-663406?course=lfcs-prep)   |
|       05 | 🧩  LVM ストレージの作成              | 初級    | [ラボを開始](https://labex.io/ja/labs/create-lvm-storage-663380?course=lfcs-prep)                      |
|       06 | 🧩  LVM ストレージの拡張              | 初級    | [ラボを開始](https://labex.io/ja/labs/extend-lvm-storage-663383?course=lfcs-prep)                      |
|       07 | 🧩  スワップ領域の設定                 | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-swap-space-663376?course=lfcs-prep)                    |
|       08 | 🧩  tmpfs と仮想ファイルシステムの構成      | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-tmpfs-and-virtual-filesystems-663377?course=lfcs-prep) |
|       09 | 🧩  ファイルシステムのオートマウント設定        | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-filesystem-automounts-663362?course=lfcs-prep)         |
|       10 | 🧩  リモートファイルシステムのマウント         | 初級    | [ラボを開始](https://labex.io/ja/labs/mount-remote-filesystems-663398?course=lfcs-prep)                |
|       11 | 🧩  ネットワークブロックデバイス（NBD）の使用    | 初級    | [ラボを開始](https://labex.io/ja/labs/use-network-block-devices-663408?course=lfcs-prep)               |
|       12 | 🧩  ストレージパフォーマンスの監視           | 初級    | [ラボを開始](https://labex.io/ja/labs/monitor-storage-performance-663396?course=lfcs-prep)             |

### 2. [LFCS 模擬試験 01](https://labex.io/ja/courses/lfcs-practice-exam-01)

LFCS 認定試験に向けた実践的な模擬試験です。運用・デプロイメント、ネットワーク、ストレージ、基本コマンド、ユーザーとグループ管理など、Linux 管理の主要分野を網羅した 20 個の独立した課題に挑戦できます。

[コースを開始](https://labex.io/ja/courses/lfcs-practice-exam-01) · ラボ: 20

#### Operations and Deployment

|   インデックス | 名前                      | 難易度   | 練習                                                                                                               |
|----------|-------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  失敗した systemd サービスの修復 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-a-failed-systemd-service-662858?course=lfcs-practice-exam-01)         |
|        2 | 🎯  定期メンテナンスジョブのスケジュール設定 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/schedule-a-recurring-maintenance-job-662860?course=lfcs-practice-exam-01)    |
|        3 | 🎯  カーネルパラメータの永続化設定      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-a-persistent-kernel-parameter-662848?course=lfcs-practice-exam-01) |
|        4 | 🎯  必要なパッケージのインストールと検証   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/install-and-validate-a-required-package-662856?course=lfcs-practice-exam-01) |
|        5 | 🎯  ローカルコンテナ化サービスの実行     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/run-a-local-containerized-service-662859?course=lfcs-practice-exam-01)       |

#### Networking

|   インデックス | 名前                          | 難易度   | 練習                                                                                                              |
|----------|-----------------------------|-------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ローカルホスト名の解決を設定する         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-local-hostname-resolution-662846?course=lfcs-practice-exam-01)    |
|        2 | 🎯  OpenSSH サーバーのセキュア化       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/secure-the-openssh-server-662861?course=lfcs-practice-exam-01)              |
|        3 | 🎯  ファイアウォール経由の Web トラフィック許可 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/allow-web-traffic-through-the-firewall-662844?course=lfcs-practice-exam-01) |
|        4 | 🎯  静的ルートの構成                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-a-static-route-662850?course=lfcs-practice-exam-01)               |
|        5 | 🎯  ネットワーク時刻同期の設定            | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-network-time-synchronization-662847?course=lfcs-practice-exam-01) |

#### Storage

|   インデックス | 名前                    | 難易度   | 練習                                                                                                      |
|----------|-----------------------|-------|---------------------------------------------------------------------------------------------------------|
|        1 | 🎯  永続的なファイルシステムの作成    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-persistent-filesystem-662854?course=lfcs-practice-exam-01) |
|        2 | 🎯  LVM 論理ボリュームの作成     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-an-lvm-logical-volume-662853?course=lfcs-practice-exam-01)   |
|        3 | 🎯  永続的なスワップ領域の設定      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-persistent-swap-662849?course=lfcs-practice-exam-01)      |
|        4 | 🎯  破損した fstab エントリの修復 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-a-broken-fstab-entry-662857?course=lfcs-practice-exam-01)    |

#### Essential Commands

|   インデックス | 名前                     | 難易度   | 練習                                                                                                            |
|----------|------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Git を使用した設定変更の追跡    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/track-configuration-changes-with-git-662862?course=lfcs-practice-exam-01) |
|        2 | 🎯  ディスク使用量のトラブルシューティング | 初級    | [チャレンジを開始](https://labex.io/ja/labs/troubleshoot-disk-usage-662863?course=lfcs-practice-exam-01)              |
|        3 | 🎯  TLS 証明書の調査          | 初級    | [チャレンジを開始](https://labex.io/ja/labs/inspect-a-tls-certificate-662855?course=lfcs-practice-exam-01)            |
|        4 | 🎯  サービスのリソース使用状況の分析    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/analyze-service-resource-usage-662845?course=lfcs-practice-exam-01)       |

#### Users and Groups

|   インデックス | 名前                | 難易度   | 練習                                                                                                      |
|----------|-------------------|-------|---------------------------------------------------------------------------------------------------------|
|        1 | 🎯  制限付き管理者ユーザーの作成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-limited-admin-user-662852?course=lfcs-practice-exam-01)    |
|        2 | 🎯  ユーザーリソース制限の設定  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-user-resource-limits-662851?course=lfcs-practice-exam-01) |

### 3. [LFCS Practice Exam 02](https://labex.io/ja/courses/lfcs-practice-exam-02)

A second independent LFCS-style practice exam with 20 hands-on Linux administration challenges covering operations and deployment, networking, storage, essential commands, and users and groups.

[コースを開始](https://labex.io/ja/courses/lfcs-practice-exam-02) · ラボ: 20

#### Operations and Deployment

|   インデックス | 名前                             | 難易度   | 練習                                                                                                                   |
|----------|--------------------------------|-------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ヘルスチェック用の Systemd タイマーを作成する | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-systemd-timer-for-health-checks-662874?course=lfcs-practice-exam-02)    |
|        2 | 🎯  ローカル APT リポジトリの構成           | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-a-local-apt-repository-662868?course=lfcs-practice-exam-02)            |
|        3 | 🎯  設定ミスのあるサービス環境の復旧            | 初級    | [チャレンジを開始](https://labex.io/ja/labs/recover-a-misconfigured-service-environment-662878?course=lfcs-practice-exam-02) |
|        4 | 🎯  永続的なコンテナワーカーの実行             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/run-a-persistent-container-worker-662882?course=lfcs-practice-exam-02)           |
|        5 | 🎯  安全なメンテナンスブロッカーの解除           | 初級    | [チャレンジを開始](https://labex.io/ja/labs/clear-a-safe-maintenance-blocker-662865?course=lfcs-practice-exam-02)            |

#### Networking

|   インデックス | 名前                         | 難易度   | 練習                                                                                                          |
|----------|----------------------------|-------|-------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  IPv6 アドレスの設定            | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-ipv6-addressing-662867?course=lfcs-practice-exam-02)          |
|        2 | 🎯  ローカルサービスポートのトラブルシューティング | 初級    | [チャレンジを開始](https://labex.io/ja/labs/troubleshoot-a-local-service-port-662883?course=lfcs-practice-exam-02)  |
|        3 | 🎯  SSH クライアントアクセスの構成       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-ssh-client-access-662872?course=lfcs-practice-exam-02)        |
|        4 | 🎯  ローカル TCP ポートのリダイレクト     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/redirect-a-local-tcp-port-662879?course=lfcs-practice-exam-02)          |
|        5 | 🎯  リバースプロキシエンドポイントの設定      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-a-reverse-proxy-endpoint-662869?course=lfcs-practice-exam-02) |

#### Storage

|   インデックス | 名前                      | 難易度   | 練習                                                                                                                |
|----------|-------------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  LVM 論理ボリュームの拡張       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/extend-an-lvm-logical-volume-662876?course=lfcs-practice-exam-02)             |
|        2 | 🎯  一時的なランタイムファイルシステムの構成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-a-temporary-runtime-filesystem-662870?course=lfcs-practice-exam-02) |
|        3 | 🎯  オンデマンドアーカイブマウントの設定   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-an-on-demand-archive-mount-662866?course=lfcs-practice-exam-02)     |
|        4 | 🎯  ファイルシステムイメージの修復とマウント | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-and-mount-a-filesystem-image-662880?course=lfcs-practice-exam-02)      |

#### Essential Commands

|   インデックス | 名前                    | 難易度   | 練習                                                                                                            |
|----------|-----------------------|-------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Git を使用した設定の復元     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restore-a-configuration-from-git-662881?course=lfcs-practice-exam-02)     |
|        2 | 🎯  失敗したログインイベントの抽出    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/extract-failed-login-events-662877?course=lfcs-practice-exam-02)          |
|        3 | 🎯  検証済みバックアップアーカイブの作成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-verified-backup-archive-662875?course=lfcs-practice-exam-02)     |
|        4 | 🎯  サービス制約エラーの分析       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/analyze-a-service-constraint-failure-662864?course=lfcs-practice-exam-02) |

#### Users and Groups

|   インデックス | 名前                   | 難易度   | 練習                                                                                                           |
|----------|----------------------|-------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  共有ディレクトリの ACL 設定  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-shared-directory-acls-662871?course=lfcs-practice-exam-02)     |
|        2 | 🎯  制御されたサービスアカウントの作成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-controlled-service-account-662873?course=lfcs-practice-exam-02) |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

