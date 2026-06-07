<div align="center">

# AI Self-Portrait

**A Claude Skill that turns 30 minutes of conversation into a portable self-portrait any AI can read in 5 seconds.**

[Skill](#quick-start) · [Vision](VISION.md) · [中文](#中文导引)

</div>

---

## The problem

> *"What's a good restaurant near me?"*

AI doesn't know you're watching your blood sugar. Or your budget. Your taste. Your age. Your work.

So the answer is generic.

**It's not the prompt. AI doesn't know who you are.**

---

## What this is

A Claude Skill that runs a guided **~1-2 hour** self-discovery interview, then generates **two markdown files** you can paste into any AI to instantly establish your context:

- `『AI』<nickname>-introduction.md` — who you are (inferred patterns, not just restated facts)
- `『AI』<nickname>-style.md` — how you want AI to collaborate with you

Paste them at the start of any new conversation. The AI stops giving advice to *some imaginary user* and starts giving it to **you**.

---

## What's special

- **Mirror, not cheerleader** — surfaces patterns you haven't said, doesn't praise without specific evidence
- **Confidence-labeled inferences** — every claim marked as `(inference)` / `(uncertain)` / `(verified fact)`
- **Privacy by design** — never collects PII (real name, phone, address, ID, etc.)
- **Scenario-based** — abstract questions get self-narrative-filtered answers; concrete scenarios force real values out
- **Built by a builder, for builders** — designed by someone shipping in public, not by a personality-test company

---

## Quick start

1. **Save `SKILL.md`** to your Claude project, or paste its contents into Claude's system prompt
2. **Start a new conversation** with Claude
3. **Say**: `"Run the ai-self-portrait skill on me."`
4. **Spend ~1-2 hours** answering questions honestly (splittable across sessions)
5. **Save the two output files**
6. **Paste them at the start** of any future AI conversation — instant context

---

## Vision — this is Phase 1 of 3

| Phase | What | Status |
|---|---|---|
| **1** | Self-Portrait Foundation (this release) | ✅ Today |
| **2** | Path Analysis — career direction, skills to learn, resource recommendations | 🔜 2-4 weeks |
| **3** | Living Life Plan — 90-day / 1-year / 5-year concrete plans, monthly iteration | 🔜 2-3 months |

Full vision: think **MBTI Premium, but conversational** — infinitely deeper, cross-domain inference, **10 dimensions of self-knowledge** from values to skills to next concrete action. Read the full [VISION.md](VISION.md).

---

## Privacy hard rules

The Skill **never collects**:
- ❌ Real name, phone, ID, exact birthdate, home address
- ❌ Bank / payment account info
- ❌ Anything that can directly identify you

You can use any nickname. Age range only. City-level location only. Skip any question, anytime.

---

## Build in public

I'm building this in public.

Every week I post real data — followers, stars, downloads, revenue (or no revenue), what's working, what's broken.

- ⭐ Star this repo if this matters to you
- 🐛 [Open an issue](https://github.com/QY-LADK7888/ai-self-portrait/issues) if something breaks or feels off
- 💬 Ideas for Phase 2 or 3 → issues / discussions welcome
- 🔧 PRs welcome — if you ship something better, great

If you run the Skill and it surfaces things you hadn't seen, **that's the whole point**. Let me know.

---

## License

[MIT](LICENSE) — do whatever you want.

---

## About

Built by 齐缘. First-time open-source ship. Background: growth marketing on Chinese platforms + AI orchestration. No CS degree, non-native English. Building in public from one-person company territory.

If this helps you see yourself more clearly, that's the whole point.

---

## 中文导引

这是一个开源 Claude Skill。 30 分钟到 2 小时的引导对话, 产出**两份可移植 markdown 文件**, 任何 AI 5 秒读完, 立刻进入你的语境。

### 为什么

AI 给的建议大多是 generic(泛的), 不是因为 prompt 不够好, 是因为 **AI 不知道你是谁**。 一旦它知道, 它给的每条建议、每个决策辅助, 都基于真实的你, 不是它想象的"普通用户"。

### 怎么用

1. 把 `SKILL.md` 放到 Claude 项目里, 或者把内容 paste 到 Claude system prompt
2. 跟 Claude 说: `"用 ai-self-portrait skill 跟我对话"`
3. 花 1-2 小时认真答题(可以分多次)
4. 保存输出的 2 个文件
5. 以后任何新对话, 把这 2 个文件 paste 在开头 → AI 立刻进入你的语境

### 愿景

这是 **Phase 1 / 3**(总共 3 个阶段)。 完整愿景: **AI 版 "MBTI Premium"**, 但是 conversational(对话式)+ 跨域 inference + 个性化, 输出 **10 维度自我认知** — 从价值观到具体下一步行动。

| 阶段 | 内容 | 状态 |
|---|---|---|
| **1** | 自画像基础(本次发布) | ✅ 今天 |
| **2** | 方向分析 — 适合的工作、要学的技能、个性化资源推荐 | 🔜 2-4 周 |
| **3** | 活的人生计划 — 90 天 / 1 年 / 5 年具体行动, 月度迭代 | 🔜 2-3 月 |

详见 [VISION.md](VISION.md)。

### 隐私

绝不收集真名 / 手机 / 身份证 / 出生日期 / 家庭住址 / 银行卡。 用任意 nickname, 年龄段, 城市级位置就够。 任何问题都可以拒答。

### Build in public 节奏

每周公开真实数据 — followers / stars / 下载量 / 收入(或没收入)/ 跑通的、跑不通的。 follow 进展见 X(链接稍后更新)。

⭐ 觉得有用就 star。 想法 / bug → 提 issue。 想改 → PR。

License: MIT, 随便用。
