# 🎮 4399 经典网页游戏《造梦西游》全套美术与音频资源素材包
### Journey to the West (Zao Meng Xi You) Complete Game Assets Archive

<p align="center">
  <img src="https://img.shields.io/badge/Game-4399%20%E9%80%A0%E6%A2%A6%E8%A5%BF%E6%B8%B8-orange.svg?style=flat-square" alt="Game" />
  <img src="https://img.shields.io/badge/Total%20Files-1600%2B-blue.svg?style=flat-square" alt="Files" />
  <img src="https://img.shields.io/badge/Asset%20Types-Sprites%20%7C%20Audio%20%7C%20Fonts-brightgreen.svg?style=flat-square" alt="Types" />
  <img src="https://img.shields.io/badge/Archive-Retro%20Flash%20Preservation-purple.svg?style=flat-square" alt="Archive" />
</p>

---

## 📌 资源简介 (Overview)

本仓库归档并整理了 4399 经典横版动作闯关网页游戏**《造梦西游》**的全套美术贴图、动作序列帧、音效音频与字体等游戏多媒体资产包。

作为中国网页游戏黄金时代的里程碑式作品，《造梦西游》陪伴了一代玩家的童年。由于 Flash 技术的退役，许多早期怀旧网页游戏的原始资源逐渐湮灭。本仓库旨在为**游戏开发学习者、独立游戏美术设计、原型开发、游戏历史保护与逆向研究者**提供完整、成套的 2D 横版动作角色扮演（ARPG）学习素材。

---

## 🗂️ 资源分类与结构说明 (Asset Catalog)

为了方便查阅与检索，本仓库将 1,600+ 项游戏素材整理为以下核心模块：

### 1. 🖼️ 美术贴图库 (`images/`)
| 类别 | 存放路径 / 格式 | 说明 |
| :--- | :--- | :--- |
| **主角动作帧** | `images/hd/skeleton/` | 唐僧、孙悟空、猪八戒、沙僧等角色的站立、跑动、跳跃、多段普攻、受击及技能释放序列帧 |
| **关卡怪物 & BOSS** | `images/hd/skeleton/` | 经典副本 BOSS（九灵元圣、牛魔王、白骨精等）骨骼动画与高精度角色切片 |
| **套装与技能特效** | `images/hd/suit_skills/` | 特效光效、法术弹道、全屏技能粒子渲染图 |
| **地图场景切片** | `images/` | 九重天、南天门、北天门、天宫走廊等经典关卡背景与分层视差卷轴素材 |
| **UI 交互组件** | `images/` | 血条、法力槽、技能冷却蒙版、装备卡槽、强化弹窗及复古按钮 |
| **神兵道具图标** | `images/` | 武器、防具、饰品、法宝、丹药及强化石高清图标 |

---

### 2. 🎵 游戏音频库 (`sounds/`)
| 类别 | 存放路径 | 包含内容 |
| :--- | :--- | :--- |
| **背景音乐 (BGM)** | `sounds/bgm/` | 登录主界面音乐（`bgm_main.mp3`）及 0~7 号关卡经典激昂背景音乐（`bgm_level_*.mp3`） |
| **角色技能音效 (SFX)** | `sounds/sfx/skill/` | 角色普攻、挥砍、雷击、火球、法宝发动等打击音效（多达 50+ 个技能音频） |
| **战斗通用音效** | `sounds/sfx/common/` | 受击音效（`role_get_hurt`）、怪物惨叫、特写切入（`sfx_cut_in`）、战斗胜负音效（`win/lose`） |

---

### 3. 🔤 字体与系统组件
| 类别 | 存放路径 | 说明 |
| :--- | :--- | :--- |
| **复古美术字体** | `plugin_fonts/FZCuYuan-M03S.ttf` | 经典方正粗圆简体字体，完美还原原版端游 UI 文字排版 |
| **原生启动资产** | `Default*.png`, `Icon*.png` | 各类分辨率下的应用图标、启动画面及高精 HD 图标素材 |
| **移动端适配包** | `YJIOSWebViewRes.bundle/` | 移动端封装与 WebView 运行所需交互资源 |

---

## 💡 适用场景与实践建议 (Use Cases)

1. **🎮 2D 横版动作游戏开发实操**：
   - 适用于 Unity 2D、Godot 4、Cocos Creator、Phaser.js、LayaAir 等主流现代游戏引擎。
2. **🕹️ 状态机（FSM）与动画融合训练**：
   - 包含完整的待机（Idle）、跑动（Run）、连招（Combo Attack）、浮空受击（Hurt）、死亡（Die）动作序列，是掌握有限状态机（FSM）或行为树的最佳实战练习素材。
3. **💥 动作打击感与音效同步调校**：
   - 结合配套的音效包，可深入练习**顿帧（Hit Stop）**、**屏幕震动（Screen Shake）**、**打击光效（Flash Overlay）**等经典 2D 动作游戏手感调试技巧。
4. **🎨 怀旧游戏文化保护与同人二创**：
   - 供数字艺术创作者、B站/短视频 UP 主用于经典回顾、同人动态动画、二次二创插画制作。

---

## ⚠️ 免责声明与版权提示 (Disclaimer & Copyright)

* 本仓库内所有美术贴图、音频、字体及相关知识产权**均归原始游戏开发商及版权方所有**。
* 本仓库仅用于**个人学习交流、游戏开发技术教学研究与数字化怀旧文化归档**，严禁将本资源包用于任何商业盈利、商业游戏开发或非法私服架设。
* 如原版权方对本归档有异议，请提交 Issue 或联系仓库维护者，我们将第一时间响应并配合下架。