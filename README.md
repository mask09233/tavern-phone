# 酒馆小手机（Tavern Phone）v2.1.2

把「手机」搬进 SillyTavern 聊天楼层：微信私聊/群聊、朋友圈、电话、贴吧、小红书、X、记忆、档案、
游戏（含麻将/命运抽卡/炒股）、小剧场、状态栏、音乐等 App。数据本地存储、按聊天隔离。

## 安装（SillyTavern 扩展面板，推荐）

1. 顶部「扩展」面板（拼图图标）→「Install extension」→ 输入本仓库地址：
   `https://github.com/mask09233/tavern-phone`
2. 安装后**刷新页面**，桌面出现悬浮球，点开手机。
3. 装后两步：
   - 手机 → 设置 → 「正则·世界书」→ **一键安装到酒馆**（正则必须装，楼层占位符 <TPH/> 靠它渲染成挂载点）；
   - 世界书：用酒馆原生「世界书 → 导入」导入本仓库 `世界书条目.json`（教 AI 输出 <TPH/>，可选但推荐）。

## AI 通道

- **推荐**：同时安装[酒馆助手(JS-Slash-Runner)](https://github.com/N0VI028/JS-Slash-Runner)，
  全功能自动可用（读楼层、酒馆生成通道、事件联动）；
- 未装酒馆助手：脚本自动进入演示模式（UI/存储照常），去 手机 → 功能 → 「AI 通道」
  配置任意 OpenAI 兼容接口（纯 fetch，无需酒馆助手）即可使用 AI 功能。

## 备用安装方式

- **MieMie Hub**：装了 [MieMie Hub](https://github.com/SheepSheepLab/MieMie-Hub) 0.8.2+ 时，
  可在 Hub 扩展中心直接在线安装/更新/卸载本产品（Extension Package v1，productId `mask09233.tavern-phone`）；
  已接 Runtime/蜂窝 Launcher/Surface：蜂窝里有「小手机」入口，Hub「已安装」页可开「显示悬浮球」
  （原生浮出动画，拖动与位置记忆照旧）；
- **酒馆助手脚本导入**：酒馆助手 → 脚本库 → 导入本仓库 `酒馆助手脚本-主程序.json`
  （导入不去重，更新前先删旧脚本；正则/世界书仍按上面第 3 步装）。