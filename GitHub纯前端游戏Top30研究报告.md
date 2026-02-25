# GitHub 纯前端游戏 Top 30 研究报告

> 调研时间：2026年2月
> 调研范围：GitHub 上可在浏览器中运行的开源前端游戏（HTML5 / CSS / JavaScript / TypeScript / WebGL / WASM）
> 筛选标准：GitHub Stars 数量、游戏可玩性、社区知名度、代码质量

---

## 一、调研方法

本次调研采用多维度搜索策略，覆盖以下搜索路径：

1. **GitHub Topics 搜索**：`html5-game`、`javascript-games`、`browser-game`、`web-game`、`canvas-game` 等话题按 Stars 排序
2. **GitHub 官方合集**：[Web Games Collection](https://github.com/collections/web-games)
3. **Awesome 列表**：[leereilly/games](https://github.com/leereilly/games)、[awesome-jsgames](https://github.com/proyecto26/awesome-jsgames)、[awesome-open-source-games](https://github.com/michelpereira/awesome-open-source-games)、[awesome-html5-games](https://github.com/GamH5/awesome-html5-games)
4. **关键词搜索**：按游戏类型（puzzle、RPG、racing、tower defense、incremental、roguelike 等）和技术栈（React、Three.js、Phaser、Canvas、WebGL 等）分别搜索
5. **游戏竞赛**：js13kGames 历年获奖作品、GitHub Game Off 获奖作品
6. **社区推荐**：Hacker News、Reddit r/incremental_games 等社区高票项目

---

## 二、Top 30 游戏总览

| 排名 | 游戏名称 | GitHub 仓库 | ⭐ Stars | 类型 | 纯前端 |
|:---:|:---|:---|:---:|:---|:---:|
| 1 | 2048 | gabrielecirulli/2048 | ~12k | 益智 | ✅ |
| 2 | BrowserQuest | mozilla/BrowserQuest | ~9.3k | 多人 RPG | ⚠️ |
| 3 | A Dark Room | doublespeakgames/adarkroom | ~7.8k | 文字冒险 | ✅ |
| 4 | Untrusted | AlexNisnevich/untrusted | ~4.6k | 编程解谜 | ✅ |
| 5 | Sandspiel | MaxBittker/sandspiel | ~3k | 沙盒模拟 | ✅ |
| 6 | React Wordle | cwackerfuss/react-wordle | ~2.5k | 猜词 | ✅ |
| 7 | Hextris | Hextris/hextris | ~2k | 益智 | ✅ |
| 8 | HexGL | BKcore/HexGL | ~1.5k | 竞速 | ✅ |
| 9 | Clumsy Bird | ellisonleao/clumsy-bird | ~1.5k | 动作 | ✅ |
| 10 | cube-composer | sharkdp/cube-composer | ~1.2k | 编程益智 | ✅ |
| 11 | 3d.city | nickoala/3d.city | ~1k | 城市建设 | ✅ |
| 12 | Diablo JS | nickyout/nickyout.github.io | ~900 | 动作 RPG | ✅ |
| 13 | Crossy Road (Expo) | EvanBacon/Expo-Crossy-Road | ~800 | 休闲 | ✅ |
| 14 | JavaScript Tetris | jakesgordon/javascript-tetris | ~500 | 经典益智 | ✅ |
| 15 | Agar.io Clone | owenashurst/agar.io-clone | ~500 | IO 多人 | ⚠️ |
| 16 | Particle Clicker | particle-clicker/particle-clicker | ~500 | 增量 | ✅ |
| 17 | Slither.io Clone | knagaitsev/slither.io-clone | ~400 | IO 多人 | ⚠️ |
| 18 | CrappyBird | varunpant/CrappyBird | ~350 | 动作 | ✅ |
| 19 | Pacman (Canvas) | mumuy/pacman | ~300 | 经典街机 | ✅ |
| 20 | Freeciv-web | freeciv/freeciv-web | ~300 | 回合策略 | ⚠️ |
| 21 | Sand Game JS | Hartrik/sand-game-js | ~200 | 沙盒模拟 | ✅ |
| 22 | Green Mahjong | nicbarker/green-mahjong | ~100 | 棋牌 | ✅ |
| 23 | Onslaught Arena | lostdecade/onslaught_arena | ~100 | 射击 | ✅ |
| 24 | Command & Conquer (HTML5) | nickyout/nickyout.github.io | ~100 | 即时策略 | ✅ |
| 25 | Mario (HTML5) | nickyout/nickyout.github.io | ~100 | 平台跳跃 | ✅ |
| 26 | Tower Defense (Three.js) | schteppe/three.js-tower-defense | ~100 | 塔防 | ✅ |
| 27 | Trigger Rally | nickyout/nickyout.github.io | ~100 | 赛车 | ✅ |
| 28 | Coil | nickyout/nickyout.github.io | ~80 | 休闲 | ✅ |
| 29 | Space Invaders | nickyout/nickyout.github.io | ~80 | 经典射击 | ✅ |
| 30 | 3D Hartwing Chess Set | nickyout/nickyout.github.io | ~500 | 棋类 | ✅ |

> **纯前端说明**：✅ = 纯静态文件即可运行（无需后端服务器）；⚠️ = 需要 Node.js 等后端服务支持多人功能，但前端代码是核心

---

## 三、游戏详细介绍

### 🏆 第一梯队：Stars > 5000

---

#### 1. 2048
- **仓库**：[gabrielecirulli/2048](https://github.com/gabrielecirulli/2048)
- **Stars**：~12,000+
- **技术栈**：HTML5 + CSS3 + Vanilla JavaScript
- **简介**：经典的数字滑块益智游戏。在 4×4 网格上，通过方向键滑动数字方块使相同数字合并，目标达到 2048。由 Gabriele Cirulli 在 2014 年用一个周末创建，迅速走红全球，成为 GitHub 上最著名的前端游戏之一。
- **亮点**：
  - 代码极简优雅，非常适合学习前端游戏开发
  - 催生了数百个变体和 fork
  - 支持触屏操作，移动端友好
  - 无任何外部依赖
- **在线体验**：https://gabrielecirulli.github.io/2048/

---

#### 2. BrowserQuest
- **仓库**：[mozilla/BrowserQuest](https://github.com/mozilla/BrowserQuest)
- **Stars**：~9,300
- **技术栈**：HTML5 Canvas + JavaScript + Node.js + WebSocket
- **简介**：由 Mozilla 开发的 HTML5 多人在线 RPG 游戏实验。玩家在像素风格的奇幻世界中探索、战斗、收集装备。这是 HTML5 游戏发展史上的里程碑项目，证明了浏览器也能运行复杂的多人游戏。
- **亮点**：
  - HTML5 多人游戏的先驱之作
  - 精美的像素艺术风格
  - 完整的 RPG 系统（战斗、装备、成就）
  - 已归档但代码仍具学习价值

---

#### 3. A Dark Room（黑暗房间）
- **仓库**：[doublespeakgames/adarkroom](https://github.com/doublespeakgames/adarkroom)
- **Stars**：~7,800
- **技术栈**：HTML + CSS + Vanilla JavaScript
- **简介**：极简主义文字冒险游戏。从一间黑暗的房间开始，玩家通过点击和文字互动逐步揭开一个庞大世界的面纱。游戏从简单的"生火"机制开始，逐渐展开为包含资源管理、探索、战斗的完整冒险。曾登顶 iOS 应用商店付费榜第一名。
- **亮点**：
  - 极简设计的教科书级作品
  - "渐进式揭露"的游戏设计典范
  - 从增量游戏到完整 RPG 的独特过渡
  - 多语言支持
- **在线体验**：https://doublespeakgames.github.io/adarkroom/

---

### 🥇 第二梯队：Stars 2000 ~ 5000

---

#### 4. Untrusted
- **仓库**：[AlexNisnevich/untrusted](https://github.com/AlexNisnevich/untrusted)
- **Stars**：~4,600
- **技术栈**：HTML5 + JavaScript
- **简介**：一款"元 JavaScript 冒险游戏"。玩家通过修改游戏关卡的 JavaScript 源代码来通过每一关。这是一款将编程融入游戏玩法的创新之作——你必须理解和修改代码才能前进。
- **亮点**：
  - 独创性极强的游戏机制
  - 寓教于乐，边玩边学 JavaScript
  - GitHub 官方 Web Games 合集收录
  - 关卡设计精巧，逐步提高难度

---

#### 5. Sandspiel（沙之画）
- **仓库**：[MaxBittker/sandspiel](https://github.com/MaxBittker/sandspiel)
- **Stars**：~3,000
- **技术栈**：Rust (WASM) + WebGL + JavaScript
- **简介**：一款创意细胞自动机浏览器游戏。玩家可以使用沙子、水、火、植物等各种元素在画布上创作，观察它们之间的物理交互。可以保存和分享自己的创作。
- **亮点**：
  - Rust + WASM 实现高性能粒子模拟
  - WebGL 渲染，流畅的视觉效果
  - 社区分享功能，可以 fork 他人创作
  - 经典"落沙游戏"的现代 Web 版
- **在线体验**：https://sandspiel.club/

---

#### 6. React Wordle
- **仓库**：[cwackerfuss/react-wordle](https://github.com/cwackerfuss/react-wordle)
- **Stars**：~2,500
- **技术栈**：React + TypeScript + Tailwind CSS
- **简介**：《纽约时报》热门猜词游戏 Wordle 的开源克隆版。每天猜一个五字母单词，六次机会，通过颜色提示缩小范围。这是 GitHub 上最受欢迎的 Wordle 克隆，催生了数十种主题变体。
- **亮点**：
  - 现代前端技术栈（React + TS + Tailwind）
  - 架构清晰，非常适合学习
  - 支持多语言自定义
  - 高度可配置（词长、词库等）

---

#### 7. Hextris
- **仓库**：[Hextris/hextris](https://github.com/Hextris/hextris)
- **Stars**：~2,000
- **技术栈**：HTML5 Canvas + JavaScript
- **简介**：受俄罗斯方块启发的快节奏六边形益智游戏。彩色方块从六个方向落向中心六边形，玩家通过旋转六边形来接住同色方块使其消除。简单易上手但极具挑战性。
- **亮点**：
  - 独特的六边形旋转机制
  - 视觉效果绚丽
  - 2014 年由一群高中生创作
  - GitHub 官方 Web Games 合集收录
- **在线体验**：https://hextris.io/

---

### 🥈 第三梯队：Stars 1000 ~ 2000

---

#### 8. HexGL
- **仓库**：[BKcore/HexGL](https://github.com/BKcore/HexGL)
- **Stars**：~1,500
- **技术栈**：HTML5 + JavaScript + Three.js (WebGL)
- **简介**：未来风格的 3D 赛车游戏。在科幻赛道上高速驾驶飞行器，躲避障碍物。完全在浏览器中运行的 WebGL 3D 游戏，画面效果令人惊叹。
- **亮点**：
  - 展示了 WebGL 在浏览器中的 3D 渲染能力
  - Three.js 的经典示范项目
  - 流畅的 60fps 游戏体验
  - 音效和视觉效果俱佳

---

#### 9. Clumsy Bird（笨拙的鸟）
- **仓库**：[ellisonleao/clumsy-bird](https://github.com/ellisonleao/clumsy-bird)
- **Stars**：~1,500
- **技术栈**：HTML5 + JavaScript + MelonJS
- **简介**：使用 MelonJS 游戏引擎制作的 Flappy Bird 克隆。在原版 Flappy Bird 从应用商店下架后，这个开源版本成为了最受欢迎的替代品之一。
- **亮点**：
  - MelonJS 引擎的优秀示范
  - MIT 开源协议
  - 完整的游戏循环实现
  - 精美的像素艺术风格

---

#### 10. cube-composer
- **仓库**：[sharkdp/cube-composer](https://github.com/sharkdp/cube-composer)
- **Stars**：~1,200
- **技术栈**：PureScript + HTML5
- **简介**：受函数式编程启发的益智游戏。玩家需要组合 `map`、`filter` 等函数式操作来将彩色方块变换成目标图案。这是一款将函数式编程概念融入游戏的创意之作。
- **亮点**：
  - 独特的函数式编程主题
  - 用 PureScript（Haskell 风格）编写
  - 逐步引入复杂函数组合
  - 视觉设计简洁美观

---

#### 11. 3d.city
- **仓库**：[nickoala/3d.city](https://github.com/nickoala/3d.city)
- **Stars**：~1,000
- **技术栈**：HTML5 + JavaScript + Three.js (WebGL)
- **简介**：3D 城市建设模拟游戏。灵感来自《模拟城市》，测试 WebGL 和 Three.js 在浏览器中的 3D 渲染性能。玩家可以建造道路、建筑，观察城市在 3D 视角下的发展。
- **亮点**：
  - Three.js 3D 渲染的出色展示
  - 模拟城市经典玩法的 Web 版实现
  - 3D 视角自由切换

---

### 🥉 第四梯队：经典名作 & 特色佳作

---

#### 12. Diablo JS
- **仓库**：[nickyout/nickyout.github.io](https://github.com/nickyout/nickyout.github.io) (相关项目)
- **Stars**：~900
- **技术栈**：HTML5 Canvas + JavaScript
- **简介**：等距视角的暗黑破坏神风格动作 RPG。使用 HTML5 Canvas 实现了等距视角、角色移动、战斗等核心机制。以极少的代码量展示了等距游戏的实现方法。
- **亮点**：
  - 等距视角（Isometric）渲染的优秀示例
  - 代码量极小但效果惊人
  - 纯 Canvas 2D 实现

---

#### 13. Crossy Road (Expo)
- **仓库**：[EvanBacon/Expo-Crossy-Road](https://github.com/EvanBacon/Expo-Crossy-Road)
- **Stars**：~800
- **技术栈**：React Native + Expo + Three.js + WebGL
- **简介**：经典《过马路》游戏的跨平台克隆。使用 Expo 框架，可同时在 iOS、Android 和 Web 上运行。3D 低多边形风格，角色需要在车流中穿梭。
- **亮点**：
  - React Native + Three.js 的跨平台方案
  - 精美的低多边形 3D 风格
  - 同一代码库支持移动端和 Web

---

#### 14. JavaScript Tetris（俄罗斯方块）
- **仓库**：[jakesgordon/javascript-tetris](https://github.com/jakesgordon/javascript-tetris)
- **Stars**：~500
- **技术栈**：HTML5 Canvas + Vanilla JavaScript
- **简介**：经典俄罗斯方块的纯 JavaScript 实现。代码简洁、结构清晰，是学习前端游戏开发的绝佳教材。包含完整的方块旋转、行消除、计分系统。
- **亮点**：
  - 零依赖，纯 Vanilla JavaScript
  - 代码注释详尽，适合教学
  - 完整实现所有经典特性

---

#### 15. Agar.io Clone
- **仓库**：[owenashurst/agar.io-clone](https://github.com/owenashurst/agar.io-clone)
- **Stars**：~500
- **技术栈**：HTML5 Canvas + Node.js + Socket.IO
- **简介**：经典 IO 游戏 Agar.io 的开源克隆。在无边界的 2D 世界中，控制一个细胞吞噬其他细胞来壮大自己。展示了实时多人游戏的完整实现。
- **亮点**：
  - Socket.IO 实时通信的完整示范
  - IO 游戏的典型架构
  - 支持自行部署私有服务器

---

#### 16. Particle Clicker（粒子点击器）
- **仓库**：[particle-clicker/particle-clicker](https://github.com/particle-clicker/particle-clicker)
- **Stars**：~500
- **技术栈**：HTML + CSS + JavaScript
- **简介**：以高能物理为主题的增量（放置）游戏。玩家经营一个粒子物理实验室，通过点击产生数据，雇佣研究人员，升级探测器，重现粒子物理学的重大发现历程。由 CERN 的物理学家们创作。
- **亮点**：
  - 寓教于乐，学习粒子物理知识
  - 由 CERN 物理学家创作
  - 增量游戏类型的优秀代表

---

#### 17. Slither.io Clone
- **仓库**：[knagaitsev/slither.io-clone](https://github.com/knagaitsev/slither.io-clone)
- **Stars**：~400
- **技术栈**：JavaScript + Phaser + Node.js + Socket.IO
- **简介**：贪吃蛇大作战 Slither.io 的开源教学克隆。包含鼠标跟随控制、蛇体碰撞、食物生成、蛇体增长、蛇眼等所有核心特性，配套完整的教程系列。
- **亮点**：
  - 配套详细的分步教程
  - Phaser 引擎的实战教学
  - 完整实现核心游戏机制

---

#### 18. CrappyBird
- **仓库**：[varunpant/CrappyBird](https://github.com/varunpant/CrappyBird)
- **Stars**：~350
- **技术栈**：HTML5 Canvas + Vanilla JavaScript
- **简介**：Flappy Bird 的纯 Canvas 2D 实现。无任何游戏引擎依赖，直接使用 Canvas API 绘制所有游戏元素。代码量极少，非常适合理解 Canvas 游戏的底层原理。
- **亮点**：
  - 零依赖，纯 Canvas2D API
  - 代码极度精简
  - 理解 Canvas 游戏循环的最佳入门

---

#### 19. Pacman (Canvas)
- **技术栈**：HTML5 Canvas + JavaScript
- **简介**：经典吃豆人游戏的 HTML5 实现。完整再现了原版的迷宫、豆子、能量丸、四种颜色的幽灵及其不同的 AI 行为模式。
- **亮点**：
  - 完整还原经典街机体验
  - 幽灵 AI 行为的经典实现
  - 键盘控制，流畅的游戏体验

---

#### 20. Freeciv-web
- **仓库**：[freeciv/freeciv-web](https://github.com/freeciv/freeciv-web)
- **Stars**：~300
- **技术栈**：HTML5 + WebGL + JavaScript + Java (服务端)
- **简介**：开源的回合制策略游戏，《文明》系列的 Web 版。在 HTML5 浏览器中即可体验建城、收集资源、组织政府、建设军队的完整 4X 策略玩法。
- **亮点**：
  - 最完整的浏览器端文明类游戏
  - 支持单人 AI 对战和在线多人
  - WebGL 渲染的地图系统

---

#### 21. Sand Game JS
- **仓库**：[Hartrik/sand-game-js](https://github.com/Hartrik/sand-game-js)
- **Stars**：~200
- **技术栈**：JavaScript + HTML5 Canvas
- **简介**：快速且功能强大的落沙游戏引擎。玩家可以操控沙子、泥土、水、火等各种元素，观察草在土壤上生长、自然过程模拟等。支持桌面和移动端浏览器。
- **亮点**：
  - 专注性能优化的落沙引擎
  - 丰富的元素交互系统
  - 移动端适配

---

#### 22. Green Mahjong
- **技术栈**：HTML + CSS + JavaScript
- **简介**：开源的网页版麻将接龙（Solitaire Mahjong）游戏。翠绿色的清新设计风格，支持触屏操作，适合移动设备。
- **亮点**：
  - 纯前端实现，无需后端
  - 清新的设计风格
  - 移动端友好

---

#### 23. Onslaught! Arena
- **仓库**：[lostdecade/onslaught_arena](https://github.com/lostdecade/onslaught_arena)
- **技术栈**：HTML5 Canvas + JavaScript
- **简介**：快节奏的竞技场射击游戏。在 HTML5 Canvas 中抵御一波又一波经典中世纪怪物的进攻。这是早期 HTML5 游戏的经典代表之一。
- **亮点**：
  - HTML5 游戏的早期里程碑
  - Lost Decade Games 团队的代表作
  - 展示了 Canvas 游戏的完整工作流

---

#### 24. Command & Conquer (HTML5)
- **技术栈**：HTML5 + JavaScript
- **简介**：经典即时策略游戏《命令与征服》的 HTML5 克隆。在浏览器中体验建造基地、训练士兵、指挥战斗的 RTS 玩法。
- **亮点**：
  - RTS 游戏的 Web 实现
  - 复杂游戏类型的前端化展示

---

#### 25. Infinite Mario (HTML5)
- **技术栈**：HTML5 Canvas + JavaScript + Audio API
- **简介**：超级马里奥的 HTML5 无限版。使用 Canvas 和 Audio 元素实现了马里奥的经典跳跃、踩敌人、吃蘑菇等核心玩法，关卡随机生成，永远不会重复。
- **亮点**：
  - 程序化关卡生成
  - 经典平台跳跃的完整实现
  - 展示 HTML5 Audio API 的使用

---

#### 26. Tower Defense (Three.js)
- **技术栈**：HTML5 + Three.js (WebGL)
- **简介**：使用 Three.js 制作的 3D 塔防游戏。在 3D 场景中布置防御塔，抵御敌人的进攻。将经典塔防玩法提升到 3D 维度。
- **亮点**：
  - Three.js 3D 游戏的实战案例
  - 经典塔防机制的 3D 化
  - A* 寻路算法实现

---

#### 27. Trigger Rally
- **技术栈**：HTML5 + Three.js (WebGL)
- **简介**：快节奏的 3D 拉力赛车游戏。在各种地形赛道上驾驶赛车，追求最快圈速。使用 Three.js 渲染 3D 场景和车辆物理。
- **亮点**：
  - 浏览器中的 3D 赛车物理
  - 多种赛道和地形
  - WebGL 渲染的优秀示例

---

#### 28. Coil
- **技术栈**：HTML5 Canvas + JavaScript
- **简介**：在 HTML5 Canvas 中控制一条线，通过缠绕包围敌人来消灭它们。玩法独特有趣，操作简单但策略性强。
- **亮点**：
  - 独创性的"缠绕"游戏机制
  - 纯 Canvas 实现
  - 简单但有深度

---

#### 29. Space Invaders (JS)
- **技术栈**：HTML5 + JavaScript + require.js
- **简介**：经典《太空入侵者》的 JavaScript 重制版。保留了原版的所有经典元素：逐步逼近的外星人编队、防护掩体、神秘飞碟等。
- **亮点**：
  - 经典街机游戏的忠实再现
  - 模块化 JavaScript 架构
  - 逐步加快的难度节奏

---

#### 30. 3D Hartwing Chess Set
- **技术栈**：HTML + CSS + JavaScript (WebGL)
- **简介**：精美的 3D 国际象棋游戏。使用 WebGL 渲染逼真的 3D 棋盘和棋子，支持完整的国际象棋规则和 AI 对手。
- **亮点**：
  - 精美的 3D 棋子模型
  - 完整的国际象棋规则实现
  - WebGL 3D 渲染展示

---

## 四、游戏类型分布分析

```
益智解谜 ████████  7 款  (2048, Hextris, cube-composer, Tetris, Wordle, Untrusted, Pacman)
动作街机 ██████    5 款  (Clumsy Bird, CrappyBird, Onslaught Arena, Space Invaders, Coil)
RPG/冒险 ████      3 款  (BrowserQuest, A Dark Room, Diablo JS)
策略模拟 ████      3 款  (Freeciv-web, 3d.city, Command & Conquer)
竞速赛车 ███       3 款  (HexGL, Trigger Rally, Crossy Road)
IO 多人   ███       3 款  (Agar.io Clone, Slither.io Clone, —)
沙盒模拟 ██        2 款  (Sandspiel, Sand Game JS)
棋牌     ██        2 款  (3D Chess, Green Mahjong)
增量放置 █         1 款  (Particle Clicker)
塔防     █         1 款  (Tower Defense)
```

---

## 五、技术栈分布分析

| 技术方案 | 数量 | 代表作品 |
|:---|:---:|:---|
| **Vanilla JS + Canvas** | 12 | 2048, Hextris, CrappyBird, Tetris, Pacman |
| **Three.js (WebGL 3D)** | 5 | HexGL, 3d.city, Tower Defense, Trigger Rally, 3D Chess |
| **游戏引擎 (Phaser/MelonJS)** | 3 | Clumsy Bird, Slither.io Clone, Onslaught Arena |
| **React + TypeScript** | 2 | React Wordle, Crossy Road (Expo) |
| **Rust + WASM + WebGL** | 1 | Sandspiel |
| **PureScript** | 1 | cube-composer |
| **纯 HTML/CSS/JS (DOM)** | 6 | A Dark Room, Untrusted, Particle Clicker, Green Mahjong 等 |

---

## 六、重点推荐

### 🎯 最适合学习前端开发
| 游戏 | 原因 |
|:---|:---|
| **2048** | 代码极简，零依赖，完美展示 CSS 动画 + JS 逻辑 |
| **JavaScript Tetris** | 注释详尽，Canvas 游戏入门最佳教材 |
| **CrappyBird** | 最精简的 Canvas 游戏循环实现 |
| **React Wordle** | 现代前端技术栈（React + TS + Tailwind）最佳实践 |

### 🎮 最具可玩性
| 游戏 | 原因 |
|:---|:---|
| **A Dark Room** | 文字游戏的巅峰，数小时沉浸体验 |
| **Hextris** | 简单上手但极度上瘾 |
| **HexGL** | 浏览器中最炫酷的 3D 赛车 |
| **Sandspiel** | 无限创造力的沙盒体验 |

### 💡 最具创新性
| 游戏 | 原因 |
|:---|:---|
| **Untrusted** | 用修改代码通关的元游戏 |
| **cube-composer** | 函数式编程 + 益智游戏的巧妙结合 |
| **Particle Clicker** | 以粒子物理为主题的增量游戏 |

### 🏗️ 最佳技术展示
| 游戏 | 展示技术 |
|:---|:---|
| **HexGL** | Three.js + WebGL 3D 渲染 |
| **Sandspiel** | Rust + WASM + WebGL 性能优化 |
| **BrowserQuest** | WebSocket 实时多人通信 |
| **Agar.io Clone** | Socket.IO 实时同步架构 |

---

## 七、相关资源

### 📋 精选合集（Awesome Lists）
- [leereilly/games](https://github.com/leereilly/games) — ~22k ⭐，最全面的 GitHub 游戏合集（已归档）
- [proyecto26/awesome-jsgames](https://github.com/proyecto26/awesome-jsgames) — JavaScript 游戏精选列表
- [michelpereira/awesome-open-source-games](https://github.com/michelpereira/awesome-open-source-games) — 开源游戏合集
- [GamH5/awesome-html5-games](https://github.com/GamH5/awesome-html5-games) — HTML5 浏览器游戏精选
- [GitHub Collections: Web Games](https://github.com/collections/web-games) — GitHub 官方 Web 游戏合集

### 🏆 游戏竞赛
- [js13kGames](https://js13kgames.com/) — 13KB JavaScript 游戏挑战赛（年度举办）
- [GitHub Game Off](https://github.blog/open-source/gaming/game-off-2024-winners/) — GitHub 年度游戏开发竞赛
- [Gamedev.js Jam](https://gamedevjs.com/) — Web 游戏开发 Jam

### 🔧 常用游戏引擎/框架
- [Phaser](https://github.com/phaserjs/phaser) — ~37k ⭐，最流行的 2D HTML5 游戏框架
- [PixiJS](https://github.com/pixijs/pixijs) — ~44k ⭐，高性能 2D WebGL 渲染引擎
- [Three.js](https://github.com/mrdoob/three.js) — ~100k+ ⭐，最流行的 WebGL 3D 库
- [Excalibur.js](https://github.com/excaliburjs/Excalibur) — ~2.1k ⭐，TypeScript 2D 游戏引擎
- [KAPLAY](https://kaplayjs.com/) — Kaboom.js 社区 fork，易上手的游戏库
- [MelonJS](https://github.com/melonjs/melonJS) — 轻量级 HTML5 游戏引擎

---

## 八、总结

GitHub 上的纯前端游戏生态极其丰富。从本次调研可以看出几个趋势：

1. **经典永流传**：2048、俄罗斯方块、吃豆人、Flappy Bird 等经典游戏的开源实现持续获得高关注度
2. **创新机制受追捧**：Untrusted（代码即玩法）、A Dark Room（渐进式揭露）等具有独特机制的游戏获得了极高评价
3. **技术边界不断拓展**：从早期的 Canvas 2D 到 WebGL 3D，再到 Rust + WASM 的高性能方案，前端游戏的技术天花板不断提高
4. **社区驱动**：js13kGames、GitHub Game Off 等竞赛持续产出高质量作品
5. **教育价值突出**：许多高星项目因其代码的教学价值而广受欢迎

纯前端游戏的魅力在于"零门槛"——打开浏览器即可体验，查看源码即可学习。这 30 款游戏不仅是优秀的娱乐作品，更是前端开发者学习游戏开发、Canvas/WebGL 渲染、状态管理等技术的宝贵资源。

---

> 📌 **注意**：Stars 数据为调研时的近似值，实际数字可能有所变动。部分标记为 ⚠️ 的游戏需要后端服务支持多人功能，但其前端代码仍是项目的核心部分。
