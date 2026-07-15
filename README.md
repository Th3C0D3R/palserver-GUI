# palserver GUI (v1)

![STATUS](https://img.shields.io/badge/STATUS-DEPRECATED-red)
[![palserver GUI 2.0](https://img.shields.io/badge/palserver_GUI_2.0-click-blue)](https://github.com/io-software-ai/palserver-gui)
[![Website](https://img.shields.io/badge/website-click-blue)](https://palserver-gui.iosoftware.ai/)
[![Discord](https://img.shields.io/badge/discord-click-blue)](https://discord.gg/sgMMdUZd3V)

#### [繁體中文](#繁體中文) / [简体中文](#简体中文) / [English](#english) / [日本語](#日本語)

---

## 繁體中文

> **v1 已停止維護。** 這個版本(最終版 1.1.0)不再更新,也不保證支援 Palworld 1.0 之後的遊戲版本。
> 請改用全面重寫的 **[palserver GUI 2.0](https://github.com/io-software-ai/palserver-gui)** —— 你的世界可以完整搬過去(見下方遷移指南)。

### 為什麼要換 2.0

- **瀏覽器管理**:主機上跑一支 agent,開瀏覽器就能管 —— 手機、平板、另一台電腦都行,朋友用一條連結也能共同管理
- **多實例**:一台機器開多個伺服器,各自獨立的世界、埠號與設定
- **一鍵安裝與更新**:自動下載伺服器檔案、比對 Steam 最新版一鍵更新
- **完整管理功能**:世界設定與引擎微調全圖形化、玩家管理、即時地圖、排程備份、模組管理(PalDefender)
- **四語介面**:繁體中文 / 简体中文 / English / 日本語
- 一樣**免費開源**

下載與教學:**[官方網站](https://palserver-gui.iosoftware.ai/)** · 問題先看 **[FAQ](https://faq.toc.icu/)** 或來 **[Discord](https://discord.gg/sgMMdUZd3V)**

### 遷移指南:把 v1 的世界搬進 2.0

2.0 內建「**匯入存檔**」,不用複製檔案、不用跑指令:

1. **完全關閉 v1 伺服器**(執行中複製的存檔是壞的)。
2. 到[官網](https://palserver-gui.iosoftware.ai/)安裝 2.0,用瀏覽器開啟管理面板。
3. 首頁按「建立伺服器」旁的「**匯入存檔**」→ 來源選「**舊版 1.0 GUI**」→ 貼上 v1 的伺服器資料夾路徑(在 v1 介面按「開啟伺服器資料夾」就能找到)→「掃描」→ 選你的世界。
4. 「**建立並匯入**」—— 匯入前會自動備份,世界自動設為啟用;啟動伺服器,玩家用原本的角色進來即可。

> **v1 和 2.0 在同一台機器?** 更省事:「建立伺服器」時把「既有伺服器路徑」填成 v1 的伺服器目錄,原地接管,連搬都不用搬。

完整教學(含本機共玩存檔、手動遷移):**[存檔遷移教學](https://github.com/io-software-ai/palserver-gui/blob/main/docs/MIGRATION.md)**

v1 的舊版安裝檔仍可在本 repo 的 [Releases](https://github.com/Dalufishe/palserver-GUI/releases) 下載,但不再提供支援。

---

## 简体中文

> **v1 已停止维护。** 这个版本(最终版 1.1.0)不再更新,也不保证支持 Palworld 1.0 之后的游戏版本。
> 请改用全面重写的 **[palserver GUI 2.0](https://github.com/io-software-ai/palserver-gui)** —— 你的世界可以完整搬过去(见下方迁移指南)。

### 为什么要换 2.0

- **浏览器管理**:主机上跑一个 agent,打开浏览器就能管 —— 手机、平板、另一台电脑都行,朋友用一条链接也能共同管理
- **多实例**:一台机器开多个服务器,各自独立的世界、端口与设置
- **一键安装与更新**:自动下载服务器文件、比对 Steam 最新版一键更新
- **完整管理功能**:世界设置与引擎调优全图形化、玩家管理、实时地图、定时备份、MOD 管理(PalDefender)
- **四语界面**:简体中文 / 繁體中文 / English / 日本語
- 一样**免费开源**

下载与教程:**[官方网站](https://palserver-gui.iosoftware.ai/)** · 有问题先看 **[FAQ](https://faq.toc.icu/)** 或来 **[Discord](https://discord.gg/sgMMdUZd3V)**

### 迁移指南:把 v1 的世界搬进 2.0

2.0 内置「**导入存档**」,不用复制文件、不用敲命令:

1. **完全关闭 v1 服务器**(运行中复制的存档是坏的)。
2. 到[官网](https://palserver-gui.iosoftware.ai/)安装 2.0,用浏览器打开管理面板。
3. 首页点「创建服务器」旁的「**导入存档**」→ 来源选「**旧版 1.0 GUI**」→ 粘贴 v1 的服务器文件夹路径(在 v1 界面点「打开服务器文件夹」就能找到)→「扫描」→ 选你的世界。
4. 「**创建并导入**」—— 导入前会自动备份,世界自动设为激活;启动服务器,玩家用原来的角色进来即可。

> **v1 和 2.0 在同一台机器?** 更省事:「创建服务器」时把「既有服务器路径」填成 v1 的服务器目录,原地接管,连搬都不用搬。

完整教程(含本机联机存档、手动迁移):**[存档迁移教程](https://github.com/io-software-ai/palserver-gui/blob/main/docs/MIGRATION.md)**

v1 的旧版安装包仍可在本 repo 的 [Releases](https://github.com/Dalufishe/palserver-GUI/releases) 下载,但不再提供支持。

---

## English

> **v1 is no longer maintained.** This version (final release 1.1.0) will not receive updates and is not guaranteed to work with Palworld 1.0 and later.
> Please switch to the fully rewritten **[palserver GUI 2.0](https://github.com/io-software-ai/palserver-gui)** — your world can be migrated over completely (see the migration guide below).

### Why switch to 2.0

- **Manage from your browser**: run one agent on the host machine and manage everything from a browser — phone, tablet, or another PC; teammates can co-manage via a single link
- **Multiple instances**: run several servers on one machine, each with its own world, port and settings
- **One-click install & updates**: auto-downloads server files and updates against the latest Steam build
- **Full management suite**: graphical world settings & engine tuning, player management, live map, scheduled backups, mod management (PalDefender)
- **4-language UI**: English / 繁體中文 / 简体中文 / 日本語
- Still **free and open source**

Download & docs: **[official website](https://palserver-gui.iosoftware.ai/)** · questions: **[FAQ](https://faq.toc.icu/)** or **[Discord](https://discord.gg/sgMMdUZd3V)**

### Migration guide: move your v1 world to 2.0

2.0 has a built-in **Import save** flow — no file copying, no commands:

1. **Fully stop the v1 server** (saves copied while running are corrupt).
2. Install 2.0 from the [official site](https://palserver-gui.iosoftware.ai/) and open the panel in your browser.
3. On the home page, click **Import save** next to "Create server" → pick source "**v1 GUI (legacy)**" → paste your v1 server folder path (find it via "Open server folder" in the v1 UI) → **Scan** → select your world.
4. **Create & import** — an automatic backup is taken first and the world is set active; start the server and players join with their existing characters.

> **v1 and 2.0 on the same machine?** Even easier: when creating a server, point "existing server path" at the v1 server directory to take it over in place — no moving at all.

Full guide (incl. local co-op saves and manual migration): **[Save migration guide](https://github.com/io-software-ai/palserver-gui/blob/main/docs/MIGRATION.md)**

v1 installers remain available under this repo's [Releases](https://github.com/Dalufishe/palserver-GUI/releases), but are no longer supported.

---

## 日本語

> **v1 の開発・サポートは終了しました。** このバージョン(最終版 1.1.0)は今後更新されず,Palworld 1.0 以降での動作は保証されません。
> 完全に書き直された **[palserver GUI 2.0](https://github.com/io-software-ai/palserver-gui)** をご利用ください —— ワールドはそのまま引っ越しできます(下記の移行ガイド参照)。

### 2.0 に乗り換える理由

- **ブラウザで管理**:ホスト機で agent を 1 つ動かすだけ。スマホ・タブレット・別の PC からも管理でき,リンク 1 本で仲間と共同管理も可能
- **マルチインスタンス**:1 台で複数サーバーを運用。ワールド・ポート・設定はそれぞれ独立
- **ワンクリックの導入と更新**:サーバーファイルを自動ダウンロードし,Steam の最新版と比較してワンクリック更新
- **充実の管理機能**:ワールド設定・エンジン調整の完全 GUI 化,プレイヤー管理,リアルタイムマップ,定期バックアップ,MOD 管理(PalDefender)
- **4 言語対応 UI**:日本語 / English / 繁體中文 / 简体中文
- 変わらず**無料・オープンソース**

ダウンロードとドキュメント:**[公式サイト](https://palserver-gui.iosoftware.ai/)** · 困ったら **[FAQ](https://faq.toc.icu/)** または **[Discord](https://discord.gg/sgMMdUZd3V)**

### 移行ガイド:v1 のワールドを 2.0 へ

2.0 には「**セーブデータをインポート**」機能が内蔵されています。ファイルコピーもコマンドも不要:

1. **v1 サーバーを完全に停止**します(稼働中にコピーしたセーブは壊れます)。
2. [公式サイト](https://palserver-gui.iosoftware.ai/)から 2.0 をインストールし,ブラウザで管理パネルを開きます。
3. ホーム画面の「サーバー作成」横の「**セーブデータをインポート**」→ ソースは「**旧版 1.0 GUI**」を選択 → v1 のサーバーフォルダのパスを貼り付け(v1 の「サーバーフォルダを開く」で確認できます)→「スキャン」→ ワールドを選択。
4. 「**作成してインポート**」—— インポート前に自動バックアップが取られ,ワールドは自動的に有効化されます。サーバーを起動すれば,プレイヤーは元のキャラクターのまま参加できます。

> **v1 と 2.0 が同じマシンにある場合**:もっと簡単です。「サーバー作成」時に「既存サーバーのパス」へ v1 のサーバーディレクトリを指定すれば,その場で引き継げます(移動すら不要)。

詳細ガイド(ローカル協力プレイのセーブ・手動移行を含む):**[セーブデータ移行ガイド](https://github.com/io-software-ai/palserver-gui/blob/main/docs/MIGRATION.md)**

v1 のインストーラーは本リポジトリの [Releases](https://github.com/Dalufishe/palserver-GUI/releases) から引き続き入手できますが,サポート対象外です。
