# Cursor Checker 使用说明

## 项目简介
Cursor Checker 是一款专为 Cursor 用户打造的账号状态与用量检测工具，支持自动检测账号状态、会员类型、剩余试用天数及 Premium 用量。

## 主要功能
- 启动即自动获取本地 Cursor 令牌，无需手动输入。
- 展示账号状态、会员类型、剩余试用天数、Premium 用量。
- 支持账号信息自动刷新，状态栏与活动页面实时展示。
- 极简操作，专注于账号健康与额度透明。

## 安装方法（推荐）

### 直接安装 VSIX 包
1. 前往 [Releases](https://github.com/lbjlaq/CursorChecker/releases) 下载最新的 `cursor-checker-*.vsix` 文件。
2. 打开 Cursor 客户端。
3. 按 `Ctrl+Shift+P`（Windows/Linux）或 `Cmd+Shift+P`（Mac），或点击左下角齿轮 > 命令面板，输入并选择 `Extensions: Install from VSIX...`。
4. 在弹出的文件选择框中，选中刚刚下载的 VSIX 文件，点击“打开”进行安装。
5. **或直接将 VSIX 文件拖拽到扩展面板（侧边栏"扩展"页）进行安装。**
6. 安装完成后，重启 Cursor 客户端即可自动生效。

> **提示：**
> - 安装后如未自动激活，可在扩展管理页手动启用。
> - 如遇"来源不明扩展"提示，选择"仍然安装"即可。

## 常见问题
- **无法自动获取令牌？**
  - 请确保本地已登录 Cursor 客户端。
  - 支持 Windows/macOS/Linux，自动查找本地数据库。
- **账号信息未刷新？**
  - 可点击活动页面"刷新"按钮，或在状态栏菜单设置自动刷新间隔。

## 联系方式
- 作者：Ctrler
- 微信公众号：Ctrler
- GitHub项目地址：[https://github.com/lbjlaq/CursorChecker](https://github.com/lbjlaq/CursorChecker)
