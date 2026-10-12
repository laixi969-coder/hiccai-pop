# hiccai-pop

海外短视频创意与分镜 Skill，适用于 Codex、Claude Code 和 Antigravity。

当前版本：**3.2.0**。基于新版 `tiktok.docx` 的 160 条文字方案更新：KOC 30 条、数字工具与 Faceless 50 条、实体商品 80 条。文档自述的播放量、账号与产品效果未核验，不作为已验证爆款背书。

核心创作标准：**先用熟人视角和生活小事建立关注，用可见异常与短顶部文字引导误判，再让产品的真实能力解释前面的画面。**

## 核心方法

1. **先分清故事机制**：误会重释、秘密工具、关系翻转，与情境解围、结果演示分别评价；不把所有产品效果都叫欧·亨利反转。
2. **前 2–3 秒单独验收**：逐拍交代异常、利害和未完成问题，每条显式输出 0–1 / 1–2 / 2–3 秒；结尾必须兑现开场。短顶部文字协助理解，不能替代动作。
3. **保留最后一镜揭晓**：最后一镜可以从约 70% 处开始，连续完成揭晓和短反应。用户指定样本式多镜头收尾、提前露出、直接演示或硬广尾板时切换对应模式。
4. **真正能拍**：默认一个场地、最多两名出镜人物、三个关键道具、3–6 镜；给全程画面、操作办法和成本依据。AI 路径给参考素材与关键镜头描述。
5. **混合出镜**：五条默认 2–3 条无人，其余有人；仅手部不算无人。局部无人探索不覆盖整组偏好。
6. **有依据才写效果**：未知型号不编参数，文档里的夸张性能不视为事实；循环必须交代实际接点，不机械加“因为——”。

7. **录屏可执行、证据可核对**：初始状态、实际操作、输出、核对贯通；Faceless、仅手部、完全无人分开，模拟界面不冒充实测。

## 样本与方法

- [主 Skill](SKILL.md)：调用时使用的核心规则与输出格式。
- [当前 160 条详细分析](references/tiktok-160-analysis.md)：三组差异、机制统计、钩子证据与不能继承的写法。
- [当前 160 条逐项索引](references/sample-bank-v3.md)：K/D/P 独立编号、原文段落定位与每条修正。
- [Faceless 与纯录屏拍法](references/faceless-screen-playbook.md)：出镜分类、界面曝光、操作语法和完整示例。
- [历史 90 条样本分析](references/tiktok-sample-analysis.md)：两批样本差异、七条规律、原文矛盾和更新依据。
- [历史 90 条逐项索引](references/sample-bank-v2.md)：原文定位、机制判断、可迁移结构和修正建议。
- [前三秒钩子方法](references/first-three-seconds.md)：八种钩子、逐秒节拍、样本开场诊断与五问验收。
- [原生叙事机制与完整改写](references/native-story-playbook.md)：字幕、机位、循环、三个可拍示例。
- [行为测试提示](test-prompts.json)：回归请求及验收点；不是已执行的自动化创作测试。

旧 90 条资料对应上一份同名文档，是历史快照；不与新版相加宣称独立样本数量。

## 安装方式

### 克隆到全局技能库

```bash
git clone https://github.com/laixi969-coder/hiccai-pop ~/.claude/skills/hiccai-pop
# 或
git clone https://github.com/laixi969-coder/hiccai-pop ~/.gemini/config/skills/hiccai-pop
# 或（Codex）
git clone https://github.com/laixi969-coder/hiccai-pop ~/.codex/skills/hiccai-pop
```

---

## 触发词

输入以下任一词汇或指令即可自动激活：
- `/hiccai-pop`
- `hiccai-pop`
- `爆款视频`
- `短视频脚本`
- `TikTok脚本`
- `Reels脚本`
- `出海视频`
- `带货视频`
- `视频创意`
- `hook设计`
- `分镜脚本`
- `viral video`
- `UGC脚本`

---

## 示例用法

直接丢给 AI 一个出海产品即可：

```text
/hiccai-pop 我有一款便携磁吸充电宝，主打超薄、发热低，目标人群是欧美苹果重度用户，帮我设计一个极具创意的爆款 TikTok 脚本。
```
