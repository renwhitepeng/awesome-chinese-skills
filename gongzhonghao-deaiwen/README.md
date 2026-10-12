# gongzhonghao-deaiwen · 公众号文章去 AI 味 Skill

把 AI 生成或带 AI 腔的中文稿件，改写为自然的人话风格公众号文章。

## 它解决什么问题

市面上的去 AI 味工具（如 humanizer）几乎全部针对英文写作。中文的 AI 腔有独立特征：套话开头、"不是……而是……"、三段式排比、结尾升华反问。本 Skill 内置 **7 大类中文 AI 味词表 + 5 步改写流程**，覆盖诊断、结构重写、句子替换、注入具体性、自检回读。

## 安装

**Claude Code / 兼容 Agent Skills 的客户端：**

```bash
npx skills add renwhitepeng/gongzhonghao-deaiwen
```

**Qoder（手动导入）：**

将本目录克隆到技能目录：

```powershell
git clone https://github.com/renwhitepeng/gongzhonghao-deaiwen "$env:USERPROFILE\.qoder-cn\skills\gongzhonghao-deaiwen"
```

**Gitee 镜像（国内加速）：**

```bash
git clone https://gitee.com/wellxy_admin/gongzhonghao-deaiwen
```

## 使用方式

对 Agent 说以下任一句式即可自动触发：

- "帮我把这篇稿子**去 AI 味**"
- "改得**像人写的**"
- "**公众号润色**：……"

## 效果示例

**改前（AI 腔）：**

> 在当今自媒体快速发展的时代，越来越多的人开始关注公众号写作。随着读者审美的不断提高，如何写出有深度的文章，成为了许多人共同思考的问题。

**改后（人话）：**

> 我去年一共写了 84 篇公众号，只有 3 篇读完率超过 50%。后来我才明白，问题不在文笔。

更多对照范例见 [EXAMPLES.md](EXAMPLES.md)。

## 文件结构

| 文件 | 内容 |
|------|------|
| [SKILL.md](SKILL.md) | 5 步改写流程（诊断→结构→句子→具体性→自检） |
| [PHRASES.md](PHRASES.md) | 中文 AI 味词表与替换规则（7 大类） |
| [EXAMPLES.md](EXAMPLES.md) | 改写前后对照范例 |

## 注意

第 4 步"注入具体性"需要作者提供真实经历素材（数字、时间、个人经验），Agent 会主动向你提问，不会编造。这也是本 Skill 与"一键洗稿"工具的本质区别：它让你的真实经验落进文字里。

## License

MIT
