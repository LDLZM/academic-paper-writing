# academic-paper-writing

英文 SCI/SSCI 学术论文构思、写作与投稿全流程技能（Agent Skill）。源自资深教授（交通/规划领域，45+ 期刊审稿人）的论文写作与投稿课程方法论，覆盖三阶段十要素：**构思（新意/创新-贡献-附加值定位/idea 来源）→ 写作（题目、摘要、引言四段论、文献综述、方法、结果讨论、结论、语言逻辑）→ 投稿（检索体系、选刊、审稿流程、审稿意见回复、拒稿应对）**。

## 目录结构

```
academic-paper-writing/
├── SKILL.md                        # 主流程：核心心法 + 三阶段十要素 + 需求路由
├── references/
│   ├── writing-guide.md            # 写作详案：逐板块结构模板、句式、坑点、自检清单
│   └── submission-guide.md         # 投稿详案：检索体系、选刊、审稿流程、意见回复、拒稿应对
└── README.md
```

## 安装到 Codex

方式一（推荐，使用 skills CLI）：

```bash
git clone https://github.com/LDLZM/academic-paper-writing.git
npx skills add ./academic-paper-writing --global --agent codex
```

方式二（直接复制到 Codex 全局技能目录）：

```bash
git clone https://github.com/LDLZM/academic-paper-writing.git
cp -r academic-paper-writing ~/.agents/skills/
```

Windows PowerShell：

```powershell
git clone https://github.com/LDLZM/academic-paper-writing.git
Copy-Item -Recurse academic-paper-writing "$HOME\.agents\skills\"
```

## 触发场景

- 选题/想 idea/评估选题价值
- 起题目、写摘要、写引言、写综述、写结论、润色某一部分
- 全文诊断/逻辑审查（"律师定罪"标准逐段检查）
- 选刊、投稿、回复审稿意见、拒稿改投

## License

MIT
