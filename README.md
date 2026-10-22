# learning-journal · 学习足迹

面向计算机学生的 Obsidian 知识整理 skill。覆盖 Agent 开发、机器人、电机控制、体系结构、嵌入式、通信和软件等交叉方向。

维护一个当前可用的知识库：按领域归类、相关概念同篇维护，重复问题改善原笔记；用双向链接和小图解释原理、实际用途与组件交互。**不创建学习日志、周期复盘或历史统计。**

## 安装

将本仓库克隆到 Codex 的技能目录，文件夹名保留 `learning-journal`：

```powershell
git clone https://github.com/xxxylw/learning-journal.git "$env:USERPROFILE\.codex\skills\learning-journal"
```

若技能目录已存在，先检查其来源和本地修改，不直接覆盖。重新开启会话后，在可用技能列表确认发现此 skill。

默认知识库路径为 `D:\_materials\Obsidian`。skill 文件与实际学习笔记分开：仓库存规则和模板，笔记及附件进入 vault；不会自动把私人笔记推送 GitHub。不同机器可在调用时指定其他 vault 路径。

## 使用

- `用 $learning-journal 整理今天讨论的 FOC，说明它和 MCU、逆变器、电流采样如何交互。`
- `用 $learning-journal 更新 amd64 的笔记，先检查是否已有 x86-64，避免重复。`
- `用 $learning-journal 整理机器人方向的知识地图，指出目前还待弄清的问题。`

首次使用会读取现有笔记结构，按内容需要整理 `首页.md`、`硬件/`、`软件/` 等领域目录和 `附件/`；不会预先批量生成尚未学过的知识。例如 PMSM、步进电机和舵机共同放在 `硬件/电机.md` 的不同小节。默认不附来源栏目，保留内部关联。无需第三方 Obsidian 插件。

## 文件

- [SKILL.md](SKILL.md)：技能入口与执行规则。
- [笔记规范](references/note-format.md)：简明概念模板、知识地图和链接维护。
- [agents/openai.yaml](agents/openai.yaml)：Codex 展示信息。

安装只提供技能指引；整理操作在拥有本地文件权限的助手会话中执行，不是后台监控程序，也不会自动读取所有历史聊天。
