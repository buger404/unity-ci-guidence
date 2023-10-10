# unity-ci-guidence

感谢：

* game-ci/unity-builder
* fastlane/fastlane

### 前言

本指南适用于：

* 没有 MacOS 资源，但是需要进行 iOS 游戏开发的人
* 多平台游戏项目，需要一套自动化流程
* Gamejam项目，需要组员进行及时的测试

### 准备材料

1. Apple Developer 账号
2. Unity 账号

### Github 工作流配置

1. 将本仓库的.github文件夹复制到你的游戏项目仓库
2. 创建私钥管理仓库(强烈建议**Private**)
3. 配置Secrets：
   * APPLE_CONNECT_EMAIL：你的 Apple Developer 账号ID
   * APPLE_DEVELOPER_EMAIL：你的 Apple Developer 账号ID
   * APPLE_TEAM_ID：你的 Apple Developer Team ID
   * 