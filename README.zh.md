语言选择 / Language Selection: 🇷🇺 [Русский](README.md) | 🇬🇧 [English](README.en.md) | 🇨🇳 [中文](README.zh.md) | 🇯🇵 [日本語](README.ja.md)

---

# CustomNPCs-constructor
适用于 Minecraft（我的世界）Custom NPCs 模组的可视化对话、任务和脚本生成器。

## 版本历史 (可点击 🌐)

### [0.0 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.0/)
**CustomNPCs 对话生成器 "Herald" (宣告者)**
* **项目启动：** 创建用于设计对话的基础标签页。

### [0.1 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.1/)
**CustomNPCs 对话生成器 "Stargazer" (占星者)**
* **更新：** 增加了 5 种不同的 UI 主题风格。

### [0.2 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.2/)
**CustomNPCs 对话生成器 "Steward" (管理者)**
* **更新：** 增加了 4 个控制按钮：
  1. 清空所有
  2. 删除最后一项
  3. 添加分支
* **注意：** 增加了用于下载对话的磁盘图标，但该功能目前尚未启用（仅作占位）。目前仍需点击底部按钮进行下载。

### [0.3 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.3/)
**CustomNPCs 对话生成器 "Warden" (守望者)**
* **齿轮菜单更新：**
  1. 创建附加对话（添加了按钮，功能暂为占位）。
  2. 访问权限级别（添加了按钮，功能暂为占位）。
* **新功能：** 增加了带有 3 个标签页和搜索功能的笔记本：
  1. 剧情线
  2. 任务
  3. 备忘录

### [0.4 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.4/)
**CustomNPCs 对话生成器 "Scientist" (科学家)**
* **齿轮菜单更新：** “创建附加对话”功能现已完全正常运行。

### [0.5 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.5/)
**CustomNPCs 对话生成器 "Master" (大师)**
* **笔记本更新：** 改为滑动抽屉式面板，避免界面杂乱。
* **功能扩展：** 允许在单个窗口中为附加对话创建多达 34 个对话/回复分支。增加了控制按钮：“清空所有”、“删除最后一项”、“添加分支”。

### [0.6 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.6/)
**CustomNPCs 对话生成器 "Lightning" (闪电)**
* **移除：** 彻底移除了巨大的“下载对话文件 (.JSON)”按钮。
* **变更：** 主题和其他设置移至齿轮菜单内。
* **新功能：** 
  1. 可调节界面透明度。
  2. 支持自定义上传电脑本地图片作为背景。
* **模板：** 增加了用于快速填充的预设：“村民”、“卫兵”、“商人”。
* **优化：** 允许完全折叠对话窗口（ID1、ID2 等），不再保留单独的浮动窗口。

### [0.7 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.7/)
**对话生成器 "Foreman" (v0.7) / 任务生成器 "Foreman" (v0.1)**
* **新功能：** 增加了“任务创建 (Quests)”标签页。
* **占位符：** 预留了未来任务设置的齿轮菜单。
* **对话更新：** 引入了对话的“可用性条件 (Availability Conditions)”系统。

### [0.8 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.8/)
**对话生成器 "Announcer" (v0.8) / 任务生成器 "Aztec" (v0.2)**
* **UI 更新：** 
  1. 增加了重置自定义本地背景图片的选项。
  2. 增加了用于页面快速上下滚动的箭头。
* **任务更新：**
  * 启用了齿轮菜单：现在可以创建额外的任务分支。
  * 增加了可创建的任务数量，并修复了导致游戏有时无法识别任务文件的结构错误。
  * 增加了在任务完成时运行控制台命令的选项（与模组的原生功能一致）。

### [0.9 版本](https://picadoni.github.io/customNPCs-constructor/ver%200.9/)
**对话生成器 "Comet" (v0.9) / 任务生成器 "Satellite" (v0.3)**
* **新功能：** 增加了全面的游戏指令手册，并集成了按名称搜索的功能。
* **修复：** 修复了任务标签页并优化了任务完成逻辑。
* **优化：** 在对话/任务生成器中选择命令窗口后，支持一键插入命令。

### [1.0 版本](https://picadoni.github.io/customNPCs-constructor/ver%201.0/)
**对话生成器 "Comet" (v0.9) / 任务生成器 "Satellite" (v0.3) / 脚本模块 "Emperor" (v0.1)**
*（对话和任务生成器未获得新名称，因为其功能在此版本中未作更新）。*
* **新功能：** 增加了新标签页 —— “CustomNPCs 脚本模块 'Emperor' v0.1”。
* **脚本模板：** 增加了自动生成模板和开箱即用的 JavaScript 代码预设库：
  1. 脚本自动生成器
  2. 预设脚本：在聊天栏发言、播放声音、召唤粒子、给予药水效果、随机事件。
* **已知错误：** 在脚本模块窗口内进行操作时，任务窗口仍保持高亮激活状态。

### [1.1 版本](https://picadoni.github.io/customNPCs-constructor/ver%201.1/)
**对话生成器 "Comet" (v0.9) / 任务生成器 "Satellite" (v0.3) / 脚本模块 "Commander" (v0.2)**
*（对话和任务生成器未获得新名称，因为其功能在此版本中未作更新）。*
* **脚本更新：** 在脚本模块标签页中增加了“生成随机脚本事件”按钮。

### [1.2 版本](https://picadoni.github.io/customNPCs-constructor/ver%201.2/)
**对话生成器 "Comet" (v0.9) / 任务生成器 "Satellite" (v0.3) / 脚本模块 "Pilot" (v0.3)**
*（对话和任务生成器未获得新名称，因为其功能在此版本中未作更新）。*
* **脚本更新：** 扩展了脚本模板和预设库。

### [1.3 版本](https://picadoni.github.io/customNPCs-constructor/ver%201.3/)
**对话生成器 "The Great" (v1.0) / 任务生成器 "Tower" (v0.4) / 脚本模块 "Titan" (v0.4)**
* **所有标签页全局更新：**
  * **对话生成器：** 集成了 AI 剧情生成器。
  * **任务生成器：** 集成了 AI 任务生成器。
  * **脚本模块：** 增加了新的预设功能（改变 NPC 大小、警报/警笛模式、流星雨）。

### [1.4 版本](https://picadoni.github.io/customNPCs-constructor/ver%201.4/)
**对话生成器 "The Great" (v1.0) / ... / 脚本模块 "Cosmos" (v0.5)**
*（对话生成器未获得新名称，因为其功能在此版本中未作更新）。*
* **全局代码更新：** 实现了多语言核心支持：
  1. 英语 (English)
  2. 繁体中文
  3. 日语 (日本語)
* **注意：** 本地化仅部分实现。存在错误：主标签页标题仍显示为俄语。

### [1.5 版本](https://picadoni.github.io/customNPCs-constructor/ver%201.5/)
**对话生成器 "The Great" (v1.0) / ... / 脚本模块 "Servant" (v0.6)**
*（对话和任务生成器未获得新名称，因为其功能在此版本中未作更新）。*
* **错误修复：** 彻底解决了本地化错误。标签页标题现在可以根据所选语言正确显示。

### [1.6 版本 (当前)](https://picadoni.github.io/customNPCs-constructor)
**对话生成器 "The Great" (v1.0) / 任务生成器 "Secretary" (v0.7) / 脚本模块 "Overlord" (v0.7)**
*（对话和任务生成器未获得新名称，因为其功能在此版本中未作更新）。*
* **新功能：** 增加了可切换的环境背景粒子效果（缓缓飘落的樱花花瓣、雪花或秋叶）。
* **逻辑改进：** 将任务标签页上的齿轮图标替换为交叉的双剑。由于战斗和任务参数是在此菜单中配置的，因此这样更加合乎逻辑。
