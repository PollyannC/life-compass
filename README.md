# Life Compass

Life Compass 是一个以中文进行人生方向探索、行动实验和定期复盘的 AI skill。它从 Anti-vision 出发，帮助使用者澄清 Vision 和价值，再通过实践、反馈与复盘形成可持续调整的过程。

## 开始使用

将 `life-compass` 目录放入所用客户端的个人 skill 目录，或让支持本地文件的 AI 读取 `life-compass/SKILL.md` 及其引用的 `references/` 文件。安装并刷新客户端后，可尝试输入：

```text
$life-compass 带我开始第一次人生探索
```

客户端的 skill 发现、文件权限和图形展示能力各不相同；路径可读不代表已经安装或获得写入权限。

## 主要功能

- 使用用户选定的中文问题开展 Anti-vision 深度探索，并转向 Vision 和行动。
- 在复盘中先看真实进展，再直接指出差距，区分用户报告、记录、推断、假设和未知。
- 将每次记录及图形快照保存为本地 Markdown，以 Obsidian 内部链接组织主题；需要时可生成兼容的 Canvas。
- 长期跟踪由用户确认的方向、实验和模式，允许更正、暂停或改变目标。

日记默认放在 `~/Desktop/Life coach/Journal/`；可以指定其他目录。日记、图形与敏感个人信息不属于 skill 代码，不应上传到仓库。文件通常是明文，实际同步及备份取决于设备设置。skill 需要用户实际提供信息；它不自动知晓现实生活，也不是心理治疗或诊断。

首次探索问题基于 Dan Koe 的 [How to fix your entire life in 1 day](https://letters.thedankoe.com/p/how-to-fix-your-entire-life-in-1)；两年展望是独立补充。定时邮件需要另行配置可用调度和邮箱工具，单独安装 skill 不会创建提醒或保证发送。
