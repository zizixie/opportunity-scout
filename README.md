# 机会捕手｜Opportunity Scout

Skill ID：`opportunity-scout`

**用途**：把赛道痛点研究、爆款竞品拆解、副业想法评估，组合成一个循证的产品机会分析工作流。内含 4 种模式：A 发现机会、B 拆解竞品、C 评估想法、D 完整闭环。

## 如何安装

**Codex（项目范围）**：将整个 `opportunity-scout` 文件夹放在项目的 `.agents/skills/` 下。确保目录为 `.agents/skills/opportunity-scout/SKILL.md`。

**Codex（个人范围）**：将文件夹放入 `~/.agents/skills/`。随后在 Codex 中输入 `$opportunity-scout`，或直接提出“用机会捕手分析……”；具体入口依所用客户端而定。

**其他支持 SKILL.md 的工具**：按该工具的 Skills 目录要求放入整个文件夹。`SKILL.md` 是必需文件，`references/` 供分析时按需加载。

## 使用方式

打开 `assets/使用示例.md` 复制任务语句。没有联网或目标平台页面无法访问时，Skill 应退化到“假设 + 待验证步骤”，不应编造评论、销量或竞品。

## 内容清单

- `SKILL.md` — 使用范围、默认值、路由与质量约束
- `references/evidence.md` — 证据分级、近三个月采样、痛点频率计算
- `references/methods.md` — 痛点、缺口、四类产品机会和九维竞品拆解
- `references/scoring.md` — 七项评分权重、阈值和最小验证步骤
- `assets/使用示例.md` — 可复制的四种调用示例

不含任何自动抓取平台内容的程序，也不会自动访问需要登录的内容；是否能执行联网研究由宿主工具及可公开访问的数据决定。
