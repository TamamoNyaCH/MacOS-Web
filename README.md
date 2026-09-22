<div align="center">

# macOS Web

**把 macOS 桌面搬进浏览器** —— 窗口系统、Dock、菜单栏、右键环形菜单、聚光灯、飘落粒子,以及 **20 个应用模块**
(卡牌收集 / 实时聊天室 / GALGAME 图鉴 / 影音播放 / 电子书 / 词典 / 小游戏 …)。

**[中文](#中文) · [English](#english)**

</div>

![桌面全景](./screenshots/01-desktop.png)

> 📷 截图放 `intro/screenshots/`,文件名见文末 [截图清单](#截图清单)。

---

<a id="中文"></a>

## 中文

一句话:**一个跑在浏览器里的 macOS 桌面**。不是静态模板 —— 窗口能拖能缩、应用能开能联机、数据存在云上、账号能登录签到。

### 桌面体验

| 功能 | 说明 |
| --- | --- |
| **窗口系统** | 拖拽移动、八向缩放、最小化到 Dock、最大化、点击聚焦置顶;打开 / 关闭 / 最小化 / 还原都有动画;同一应用默认只开一个窗口 |
| **菜单栏** | 左上显示当前应用名并可下拉(关于本机 / 系统设置等),右侧系统状态与时间 |
| **Dock** | 图标 + 运行指示点;点击打开应用,再点最小化,从 Dock 还原时会飞回原位置 |
| **桌面图标** | 自由拖拽 + 网格自动吸附 + 一键「整理图标」;每个应用可单独隐藏(桌面与 Dock 一起) |
| **主题与壁纸** | 明暗双主题一键切换;壁纸支持**内置图片 / 自定义图片 / 自定义视频**,亮度可调(过亮压暗、过暗提亮) |
| **右键环形菜单** | 桌面右键单击,在光标处展开一圈**圆形按钮**(小组件 / 整理图标 / 系统设置 / 访达…);再点右键、Esc、点菜单外都能收起 |
| **右键聚光灯** | 按住右键时用一个**圆形遮罩揭示下层图片**,圆心跟着鼠标走;**滚轮临时缩放**这个圆,松手即还原 |
| **飘落粒子** | **雪花 / 樱花 / 月饼**三种图案飘落,可调速度、图案大小、数量、透明度;可选「盖在所有窗口之上」或「只盖壁纸」 |
| **桌面小组件** | 可拖动可关闭的桌面卡片,右键环形菜单里一键添加(见下) |

![右键环形菜单 + 聚光灯](./screenshots/02-ring-menu.png)

![多窗口同屏](./screenshots/03-windows.png)

### 内置应用(20 个模块)

桌面 / Dock 上能直接点开的是 **17 个**;另 **3 个是子窗口**(播放窗口、影片详情、作品详情),由父应用点开后弹出。

> 「在线播放器」和「里番播放器」**默认隐藏**,可在 **系统设置 → 桌面管理 → 应用显示** 里打开。

#### 效率与工具(8)

| 应用 | 能干什么 |
| --- | --- |
| **访达** | 网站的用户中心:注册 / 登录 / 忘记密码(邮箱验证码)、资料卡(头像・用户名・QQ・邮箱・**积分**)、资料编辑、**每日签到** |
| **备忘录** | 左列表 + 右编辑器,自动保存,离线可用 |
| **计算器** | 标准 / 科学两种模式,鼠标点按与键盘输入都支持 |
| **终端** | 模拟终端(不执行真实系统命令),但命令**真的和桌面联动**:`open <app>` 打开应用、`theme dark` 切主题、`exit` 关掉当前窗口。输入 `help` 看全部命令 |
| **实用工具** | 11 个小工具合体(汇率、哈希、Base64、密码、取色、IP、二维码、条形码、抛硬币、骰子、转盘) |
| **词典** | StarDict 词典查询,左侧可切换多本词典 |
| **电子书** | 本地书库:**导入 TXT / EPUB** → 书架 → 阅读器,记住每本书的阅读进度 |
| **黄页导航** | **19 分类 / 1526 个站点**的导航页,支持跨分类搜索;数据走 CDN,断网有缓存兜底 |

#### 影音(6)

| 应用 | 能干什么 |
| --- | --- |
| **音乐** | CD 封面 + 播放界面,KV 云端歌单;**关掉窗口也不中断播放**(后台播放) |
| **视频** | 扁平列表 + 直链播放 |
| **在线播放器** | **5219 个节点**的多级分类目录,逐层点到具体集数,点开后弹独立的**播放子窗口** |
| **视频播放**(子窗口) | 播放器本体;**最小化后继续后台播放**,关闭即停 |
| **里番播放器** | **421 部**影片:分页网格 + 名称搜索,点封面弹详情 |
| **影片详情**(子窗口) | 剧情简介、标签、集数列表,直接选集播放 |

![影音播放](./screenshots/07-media.png)

#### 深度功能(4)

| 应用 | 能干什么 |
| --- | --- |
| **联动卡牌** | 全站最重的一个应用,详见下一节 |
| **聊天室** | **WebSocket 实时聊天**:文字 / EMOJI / 图片,回复、@、撤回、管理员禁言,拖图片进来先预览再发,点图看大图灯箱 |
| **GALGAME 数据库** | **720 部**作品的图鉴,详见下一节 |
| **作品详情**(子窗口) | 标题 → 标签 → 封面 → 简介 → 制作人员 → **正文图轮播**(左右按钮 + 方向键,带滑动动画) |

#### 其它(2)

| 应用 | 能干什么 |
| --- | --- |
| **系统设置** | 外观(明暗 / 壁纸 / 亮度 / 粒子)、桌面管理(应用显示 / Dock / 聚光灯 / 滚轮步进) |
| **小游戏** | 合集外壳:2048 / 翻牌记忆 / 扫雷 / 数独,进入才加载对应游戏 |

![系统设置 · 外观](./screenshots/08-settings.png)

### 联动卡牌(卡牌收集 + 数值养成 + 回合制战斗)

一个完整的「收集 → 养成 → 战斗 → 排行 → 社交」闭环,数据全在云端(卡池 **2862 张**在数据库,卡图 **2818 张**在对象存储)。

- **建号**:首次打开填昵称即建号,自带**九项属性**(生命 / 魔法 / 攻击 / 防御 / 魔法攻 / 魔法防 / 暴击 / 暴击伤害 / 抗暴)
- **每日抽卡**:多卡池(免费 / 金币 / 水晶)、每池独立概率与出卡张数,**每天有免费次数**;抽完弹结果弹窗
- **卡牌图鉴**:已解锁卡牌 **3 列 × 6 行 = 18 张/页**,点卡弹详情;**重复卡自动分解成代币**
- **背包**:分类 + 分页,道具可使用(战斗内道具与场外道具分开);每种道具有叠加上限
- **回合制战斗**:每回合三选一(物理 / 花魔法的技能 / 战斗道具),按攻防、暴击与抗暴结算伤害
- **副本**:线性固定场次(**小怪 → 精英 → BOSS**),当前血量跨场保留,**奖励在离开副本时统一结算**
- **排行榜**:战力 / 财富 / 图鉴三榜,每天定时重算,前三名有奖牌
- **信箱**:系统邮件带道具 / 卡牌附件,可领取、可收藏(收藏会移入收藏夹长期保留)
- **公告**:所有玩家可见的公告板
- **GM 面板**:只有 GM 账号可见 —— 发信(带附件预览与二次确认)、公告管理、**审计日志**

![联动卡牌 · 图鉴](./screenshots/04-cards.png)

### 聊天室

- **WebSocket 实时**,单房间上限 **100 人**;**闲置 60 秒自动退出**释放名额
- 文字(≤1000 字)/ EMOJI / **图片(≤5MB)**
- **回复**、**@ 提醒**、**撤回**(普通用户只能撤自己的)、**管理员禁言**
- 拖文件进窗口**先预览再确认发送**;点图开**灯箱**看大图

![聊天室](./screenshots/06-chat.png)

### GALGAME 数据库

- **720 部**作品:元数据(标题・副标题・标签・资源 id・封面・简介・制作人员・正文图)统一取自一份图鉴数据,封面与正文图 CDN 直链
- 列表页 **3 列 × 6 行 = 18 条/页** + 搜索 + 翻页
- 卡片是横向布局:**左边 4:3 封面区 + 右边标题 / 标签 / 简介**
- 标题过长自动截断,**鼠标悬停 0.4 秒后横向滚动到底**
- 详情是**独立子窗口**:标题 → 标签 → 封面 → 简介 → 制作人员 → **正文图轮播**(左右按钮 + 键盘方向键,切换带滑动特效)

![GALGAME 数据库](./screenshots/05-galgame.png)

### 桌面小组件

右键环形菜单里一键添加,可拖动、可关闭、位置会记住。

| 小组件 | 说明 |
| --- | --- |
| **世界时钟** | 多城市表盘,指针实时走动 |
| **每日一言** | 每次刷新取一句随机句子(外部接口,取不到会优雅降级) |
| **Live2D 看板娘** | 桌面上的 Live2D 模型(Cubism),透明背景直接站在壁纸上 |

![桌面小组件与粒子](./screenshots/09-particles.png)

### 实用工具(11 个)

汇率换算 · 哈希编码 · Base64 转换 · 密码生成器 · 颜色选择器 · IP 地址查询 · 二维码生成器 · 条形码生成器 · 抛硬币 · 掷骰子 · 自定义转盘

### 小游戏(4 款)

| 游戏 | 说明 |
| --- | --- |
| **2048** | 合并相同数字,冲击 2048 |
| **翻牌记忆** | 翻开配对 EMOJI,三档难度 |
| **扫雷** | 经典排雷,三档难度 |
| **数独** | 五档难度,保证唯一解 |

### 账号与权限

- 游客可以直接用大部分应用(备忘录、计算器、终端、工具箱、词典、电子书、导航、音乐、小游戏…)
- 下面这些**需要注册登录**,未登录点开会统一拦截并提示登录:

  **视频** · **在线播放器** · **视频播放** · **里番播放器** · **影片详情** · **联动卡牌** · **聊天室** · **GALGAME 数据库** · **作品详情**

- 注册用**邮箱验证码**(验证码有有效期、错误次数限制与发送冷却);双令牌自动续期,长期不用会要求重新登录

---

<a id="english"></a>

## English

**A macOS desktop, rebuilt in the browser.** Not a static mock-up — windows really drag and resize, apps really open and talk to a backend, data really lives in the cloud, and accounts really log in and check in daily.

### Desktop experience

| Feature | What it does |
| --- | --- |
| **Window system** | Drag, 8-way resize, minimize to Dock, maximize, click-to-focus, animated open / close / minimize / restore, one window per app by default |
| **Menu bar** | Current app name with a dropdown (About / Settings) on the left, system status and clock on the right |
| **Dock** | App icons with running indicators; click to open, click again to minimize, restore flies back to where it came from |
| **Desktop icons** | Free dragging with grid snapping, one-click "tidy up", per-app show/hide (desktop and Dock together) |
| **Themes & wallpapers** | Light/dark themes; wallpapers can be **built-in images, your own image, or your own video**, with adjustable brightness |
| **Right-click ring menu** | Right-click the desktop to fan out **circular buttons** around the cursor (widgets, tidy up, Settings, Finder…). Close with another right-click, Esc, or clicking outside |
| **Right-click spotlight** | Hold right-click to reveal artwork beneath the desktop through a **circular mask** that follows the cursor; the **scroll wheel temporarily resizes** it |
| **Falling particles** | **Snowflakes / cherry blossoms / mooncakes**, with adjustable speed, size, count and opacity; layer above all windows or wallpaper-only |
| **Desktop widgets** | Draggable, closable desktop cards, added from the ring menu |

![Right-click ring menu and spotlight](./screenshots/02-ring-menu.png)

![Several windows at once](./screenshots/03-windows.png)

### Built-in apps (20 modules)

**17** are directly openable from the desktop / Dock; **3** are child windows (player, video detail, work detail) opened from their parent app.

> "Online player" and "Hentai player" are **hidden by default** — enable them in **Settings → Desktop → App visibility**.

#### Productivity & tools (8)

| App | What it does |
| --- | --- |
| **Finder** | The account hub: sign up / sign in / forgot password (email codes), profile card (avatar, username, QQ, email, **points**), profile editing, **daily check-in** |
| **Notes** | List + editor, auto-saved, works offline |
| **Calculator** | Standard and scientific modes, mouse and keyboard input |
| **Terminal** | A simulated shell (no real system commands) whose commands **do drive the desktop**: `open <app>`, `theme dark`, `exit` to close the focused window. Type `help` |
| **Toolbox** | 11 utilities in one (currency, hashing, Base64, passwords, color picker, IP lookup, QR codes, barcodes, coin flip, dice, spin wheel) |
| **Dictionary** | StarDict lookups with a switchable dictionary list |
| **Books** | Local library: **import TXT / EPUB** → shelf → reader, with per-book reading progress |
| **Site directory** | **1,526 sites across 19 categories**, with cross-category search; cached for offline use |

#### Media (6)

| App | What it does |
| --- | --- |
| **Music** | CD-style UI with a cloud playlist; **keeps playing after the window closes** |
| **Video** | Flat list with direct-link playback |
| **Online player** | A **5,219-node** multi-level category tree, opening each item in a dedicated **player child window** |
| **Video player** (child) | The player itself; **keeps playing when minimized**, stops when closed |
| **Hentai player** | **421 titles** as a paged grid with name search |
| **Video detail** (child) | Synopsis, tags and episode list with direct playback |

![Media playback](./screenshots/07-media.png)

#### Deeper features (4)

| App | What it does |
| --- | --- |
| **Cards** | The biggest app here — see below |
| **Chat room** | **Realtime WebSocket chat**: text / EMOJI / images, replies, @-mentions, recalls, admin mute, drag-and-drop image preview, lightbox viewer |
| **GALGAME database** | A **720-title** illustrated database — see below |
| **Work detail** (child) | Title → tags → cover → synopsis → staff → **artwork carousel** (arrow buttons and keyboard arrows, with slide transition) |

#### Other (2)

| App | What it does |
| --- | --- |
| **Settings** | Appearance (theme / wallpaper / brightness / particles) and desktop management (app visibility / Dock / spotlight / wheel step) |
| **Mini games** | Shell hosting 2048 / Memory match / Minesweeper / Sudoku, loaded on demand |

![Settings · Appearance](./screenshots/08-settings.png)

### Cards — collection, progression and turn-based battles

A full collect → grow → fight → rank → social loop, stored server-side (a **2,862-card** pool in the database, **2,818 card images** in object storage).

- **Create a player** on first launch with a nickname; you get **nine stats** (HP / MP / ATK / DEF / magic ATK / magic DEF / crit / crit damage / crit resist)
- **Daily gacha**: multiple pools (free / coins / crystals) with independent odds and pull counts, **free pulls every day**
- **Codex**: unlocked cards as a **3 × 6 = 18 per page** grid with a detail modal; **duplicate cards auto-disenchant into tokens**
- **Bag**: categorised and paged, usable items (in-battle and out-of-battle), with a stack cap per item
- **Turn-based battles**: pick one of three each turn (physical / MP-costing skill / battle item); damage resolves from attack, defence, crit and crit resist
- **Dungeons**: fixed linear waves (**mobs → elite → BOSS**), HP carries between waves, **rewards settle on exit**
- **Leaderboards**: power, wealth and codex, recomputed on a schedule, with medals for the top three
- **Mailbox**: system mail with item and card attachments; claim or favourite them into a long-term folder
- **Announcements**: a board visible to every player
- **GM panel**: visible only to GM accounts — send mail (with attachment preview and double confirmation), manage announcements, and read the **audit log**

![Cards · Codex](./screenshots/04-cards.png)

### Chat room

- **Realtime over WebSocket**, **100 users** per room, **auto-leave after 60 seconds idle** to free up a slot
- Text (≤1000 chars) / EMOJI / **images (≤5MB)**
- **Replies**, **@-mentions**, **recalls** (users can only recall their own), **admin mute**
- Drop a file in to **preview before sending**; click an image for a **lightbox**

![Chat room](./screenshots/06-chat.png)

### GALGAME database

- **720 titles** with unified metadata (title, subtitle, tags, resource id, cover, synopsis, staff, artwork); covers and artwork served straight from a CDN
- List view of **3 columns × 6 rows = 18 per page**, plus search and paging
- Horizontal cards: **4:3 cover on the left, title / tags / synopsis on the right**
- Overlong titles are truncated and **scroll horizontally on hover after 0.4s**
- Detail opens as a **separate child window**: title → tags → cover → synopsis → staff → **artwork carousel** (arrow buttons and keyboard arrows, with a slide effect)

![GALGAME database](./screenshots/05-galgame.png)

### Desktop widgets

Added from the ring menu, draggable, closable, and their positions are remembered.

| Widget | What it does |
| --- | --- |
| **World clock** | Multi-city clock faces with live hands |
| **Daily quote** | A random sentence fetched from an external API, with a graceful fallback |
| **Live2D mascot** | A Live2D (Cubism) model standing on your wallpaper with a transparent background |

![Widgets and particles](./screenshots/09-particles.png)

### Toolbox (11 tools)

Currency converter · Hashing · Base64 · Password generator · Color picker · IP lookup · QR code generator · Barcode generator · Coin flip · Dice roll · Custom spin wheel

### Mini games (4)

| Game | What it does |
| --- | --- |
| **2048** | Merge matching numbers and chase 2048 |
| **Memory match** | Flip EMOJI pairs, three difficulties |
| **Minesweeper** | Classic mine clearing, three difficulties |
| **Sudoku** | Five difficulties, always uniquely solvable |

### Accounts & access

- Guests can use most apps (Notes, Calculator, Terminal, Toolbox, Dictionary, Books, Site directory, Music, Mini games…)
- These **require signing in** and are intercepted with a login prompt otherwise:

  **Video** · **Online player** · **Video player** · **Hentai player** · **Video detail** · **Cards** · **Chat room** · **GALGAME database** · **Work detail**

- Sign-up uses **email verification codes** (with expiry, attempt limits and a resend cooldown); token pairs refresh automatically, and long-idle sessions ask you to sign in again

---

### 截图清单

> 这一节是给**仓库维护者**看的,不是页面内容。把截图放进 `intro/screenshots/`,文件名对上即可 ——
> **缺图只是那张不显示,不影响其它内容**(上面的 9 处引用会留一个带 alt 文字的破图占位)。
>
> This section is for the repo maintainer, not page content. Drop images into `intro/screenshots/`
> using the exact filenames below; a missing image simply doesn't render.

| 文件名 / Filename | 拍什么 / What to capture | 建议 / Tips |
| --- | --- | --- |
| `01-desktop.png` | **主视觉**:桌面全景(壁纸 + 菜单栏 + 桌面图标 + Dock + 一个小组件) | 窗口 1600×1000 以上,关掉浏览器边框 |
| `02-ring-menu.png` | 桌面右键,**环形菜单展开 + 聚光灯把下层图挖出来**的那一刻 | 鼠标停在有内容的壁纸区域,效果最明显 |
| `03-windows.png` | 多窗口同屏(备忘录 + 计算器 + 词典),展示拖拽与聚焦 | 窗口错开摆放,能看出层级 |
| `04-cards.png` | 联动卡牌 → **图鉴**(卡牌网格) | 3×6 铺满一页最好看 |
| `05-galgame.png` | GALGAME 数据库列表页(搜索栏 + 卡片网格 + 翻页) | 需要登录;详情子窗口另存一张 `05b-galgame-detail.png` 也行 |
| `06-chat.png` | 聊天室(含图片消息 + 成员栏) | 注意别带上真实用户昵称 / 头像 |
| `07-media.png` | 在线播放器分类目录,或音乐应用的 CD 界面 | 展示影音能力 |
| `08-settings.png` | 系统设置 → 外观(明暗 / 壁纸 / 粒子特效那几组) | 能体现「配置很细」 |
| `09-particles.png` | **飘落粒子 + 夜间主题**(樱花或雪花) | 粒子透明度调高一点更明显 |

文件建议 **PNG、单张 < 500KB**(GitHub 直接把仓库里的图片当 CDN 用);建议在 Retina 屏上截或用 **2 倍图**,缩到页面里更清晰。
Recommended: PNG, **under 500KB each**, captured at **2×** on a Retina display for crispness.
