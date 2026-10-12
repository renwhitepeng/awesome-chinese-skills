# Awesome Chinese Skills · 中文垂直 Agent 技能合集 Top 12

让 Claude Code / Codex / Qoder / Cursor 等 Agent 直接学会 12 项中文场景的"接单级"手艺。每个技能都是一套带触发词、分步流程、输出格式和红线的标准 SKILL.md。

英文技能生态很强，但**中文的甲方要的东西英文技能不会做**：公众号去AI味、小红书爆款、考研复试、私域社群——这个合集补的就是这个缺口。

## 技能清单

| # | 技能 | 解决什么 | 触发词示例 |
|---|------|----------|-----------|
| 1 | [gongzhonghao-deaiwen](gongzhonghao-deaiwen/SKILL.md) ⭐ | 公众号文章去 AI 味（旗舰，含中文AI味词表7大类） | "去AI味"、"改得像人写的" |
| 2 | [xiaohongshu-baokuan](xiaohongshu-baokuan/SKILL.md) | 小红书爆款笔记：标题公式+合规自查 | "小红书文案"、"种草" |
| 3 | [dianshang-xiangqing](dianshang-xiangqing/SKILL.md) | 电商详情页/主图文案：FAB卖点+广告法自查 | "详情页"、"产品文案" |
| 4 | [jianli-zhenduan](jianli-zhenduan/SKILL.md) | 简历诊断与目标岗位重写 | "改简历"、"投了没回音" |
| 5 | [mianshi-moni](mianshi-moni/SKILL.md) | 求职面试模拟：出题+追问+四维评分 | "面试模拟"、"怎么回答" |
| 6 | [kaoyan-fushi](kaoyan-fushi/SKILL.md) | 考研复试全流程模拟 | "考研复试"、"调剂面试" |
| 7 | [duanshipin-houbai](duanshipin-houbai/SKILL.md) | 短视频口播脚本：黄金三秒+分镜表 | "口播"、"开头留不住人" |
| 8 | [hetong-shencha](hetong-shencha/SKILL.md) | 合同风险预审：分级标注+谈判话术 | "看合同"、"有没有坑" |
| 9 | [ppt-storyline](ppt-storyline/SKILL.md) | 咨询级 PPT 故事线与逐页大纲 | "汇报大纲"、"述职" |
| 10 | [shequ-neirong-rili](shequ-neirong-rili/SKILL.md) | 私域社群一周内容日历 | "社群运营"、"群里没人说话" |
| 11 | [fengchuan-jiancha](fengchuan-jiancha/SKILL.md) 📚 | 内容疯传性检查（《疯传》STEPPS 六原则打分+改写） | "会不会火"、"转发少" |
| 12 | [feibaoli-goutong](feibaoli-goutong/SKILL.md) 📚 | 非暴力沟通对话翻译（冲突原话→四步句式） | "吵架怎么回"、"沟通不炸" |

📚 = 方法论书籍蒸馏系列（框架来自书，文字全部自研）。

## 安装

**整包安装（skills.sh / Claude Code / Codex 等）：**

```bash
npx skills add renwhitepeng/awesome-chinese-skills --all
```

只装某一个：

```bash
npx skills add renwhitepeng/awesome-chinese-skills --skill gongzhonghao-deaiwen
```

**Qoder（手动导入）：**

```powershell
git clone https://github.com/renwhitepeng/awesome-chinese-skills
# 把需要的技能文件夹拷入 .qoder\skills\（项目级）或 %USERPROFILE%\.qoder-cn\skills\（全局）
```

**国内加速（Gitee 镜像）：**

```bash
git clone https://gitee.com/wellxy_admin/awesome-chinese-skills
```

## 每个技能的结构

遵循 [Agent Skills 开放标准](https://agentskills.io)：

```
skill-name/
└── SKILL.md      # frontmatter(name/description) + 核心原则 + 分步流程 + 输出格式 + 红线
```

旗舰技能 gongzhonghao-deaiwen 额外附带词表手册和对照范例（渐进式披露示例）。

## 设计共性

- **先问料，后开工**：所有技能的第 1 步都是收集真实素材，缺素材向用户提问
- **红线内置**：不编数据、不编法条、不编案例；合规自查是流程的最后一步
- **交付即成品**：每个技能定义了明确的输出格式，可直接作为服务交付物

## 商用说明

技能文档本身 MIT 开源。你可以自由用于接单、课程、企业内训——它赚的是"会用"的钱，不是"拥有"的钱。

## License

MIT
