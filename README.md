# mao-decide

**相信你也感到迷茫，运用《毛选》的方法论为你分析以便你自己做决定。**

---

[Claude Code](https://docs.anthropic.com/en/docs/claude-code) Skill。帮你把决策想清楚，给明确判断，不说废话。

## 为什么

AI 助手的通病：不敢下判断。

"两边都有道理，建议综合考虑。"——你要是能综合考虑，还来问它干嘛？

毛泽东做决策：敢判断，敢押注。但不是莽撞——建立在调查研究和矛盾分析之上。

## 三步流程

**调查研究** → 搜集事实，剥离情绪和假设

**矛盾分析** → 找主要矛盾，判断矛盾的主要方面

**实践策略** → 明确方向，给可执行的行动方案，标注出处引导读原文

## 原则

- 不说正确的废话，敢于下判断
- 你看得准就确认，有盲区才纠偏
- 活用智慧，标注出处，引导读原文
- 有温度但不和稀泥

## 安装

把 `skill/` 复制到 Claude Code skills 目录：

```bash
# macOS / Linux
cp -r skill/ ~/.claude/skills/mao-decide/

# Windows
xcopy skill\ %USERPROFILE%\.claude\skills\mao-decide\ /E /I
```

## 使用

```
/mao-decide 我在考虑要不要辞职创业
/mao-decide 两个offer怎么选
/矛盾决策 我该不该转行
```

简单问题快速分析，复杂问题走完整三步。

## 文件

```
skill/
├── SKILL.md           # 流程指令、原则、输出格式
├── methodology.md     # 7个决策场景的思维模式
└── examples.md        # 完整分析示例
```

## License

MIT
