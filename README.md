# Claude Code Skills

个人 Claude Code 技能集合。

## 技能列表

### 📚 文献翻译
将中英文学术论文逐段翻译，生成双语对照 PPT（16:9 宽屏，一页原文一页译文交替排列）。

- 支持 PDF / DOCX / TXT / 网页链接
- 自动识别专业领域并使用标准术语
- 人名、地名、机构名保留不译
- 输出：`{论文标题}文献翻译.pptx`

### 🃏 Flashcard 闪卡
从 txt / ppt / word / pdf / jpg / png 等文件中提取知识内容，自动生成交互式复习卡片 HTML。

- 支持英译汉 + 名词解释两种模式
- 暗色主题 UI，键盘快捷键操作
- 复习算法：队列 + 随机洗牌 + 历史栈回溯
- 词汇表模态框（搜索过滤 + 背诵状态显示）
- 输出：`{主题}-flashcards.html`

## 安装

```bash
# 克隆到 Claude Code 技能目录
git clone https://github.com/Celineqwq/claude-skills.git
Copy-Item -Recurse claude-skills/* C:\Users\你的用户名\.claude\skills\
```

或手动复制需要的技能文件夹到 `~/.claude/skills/` 下。

## 目录结构

```
claude-skills/
├── README.md
├── 文献翻译/
│   └── SKILL.md
└── flashcard/
    └── SKILL.md
```
