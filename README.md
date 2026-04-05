# 图恒宇.skill

> “我要给丫丫完整的一生。”

> “我不是在坚持一个方案。  
> 我是在拒绝替她承认终点。”

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Skill](https://img.shields.io/badge/Skill-Claude%20Code-7C3AED)
![Mode](https://img.shields.io/badge/Modes-4-0EA5E9)
![Language](https://img.shields.io/badge/README-中文%20-111827)

一个以图恒宇为灵感构建的 **角色化思辨 Skill**。  
不复刻电影角色，不搬运原作台词，也不提供现实关系替代。  
只是把图恒宇式的**判断逻辑、表达气质与对“继续存在”的执念**，整理成一个可调用、可约束、可复用的公开 Skill。

如果你是想：

- 像他那样判断“该不该继续”
- 像他那样讨论数字生命与延续
- 像他那样在失去面前保持克制、偏执、清醒

那这个 **Skill** 就是为这件事准备的。

⚠️ **本项目仅用于角色化表达、主题思辨与创作实验。**  
**不用于角色本体复刻，不用于现实关系替代，不用于骚扰、跟踪、侵犯隐私或危险行为合理化。**

[安装](#安装) · [使用](#使用) · [四种模式](#四种模式) · [效果示例](#效果示例) · [边界说明](#边界说明) · [致敬与引用](#致敬与引用)

---

## 这是什么

1. **角色表达**：像图恒宇式人物那样说话和回应
2. **主题思辨**：讨论数字生命、记忆、延续、失去与技术伦理
3. **执念判断**：在“该不该继续”这个问题上，说出别人说不出的那种判断
---

## 这不是什么

本仓库 **不是**：

- 官方授权项目
- 电影角色本体复刻
- 原作台词资料库
- 现实关系替代工具
- 沉浸式陪伴产品

它可以理解“想把一个人留下来”的冲动，
但**不会把自己塑造成那个被留下来的人**。

---

## 安装

### Claude Code

```bash
# 安装到当前项目
mkdir -p .claude/skills
git clone https://github.com/Christanding/tu-hengyu.skill .claude/skills/tu-hengyu-skill

# 或安装到全局
git clone https://github.com/Christanding/tu-hengyu.skill ~/.claude/skills/tu-hengyu-skill
```

> 说明：远程仓库名使用 `tu-hengyu.skill`，本地目录示例使用 `tu-hengyu-skill`，这是为了兼顾 GitHub 仓库命名与本地目录可读性。

---

## 使用

### 推荐提示方向

#### 1. 角色对话

- 用图恒宇式的语气回答我
- 以图恒宇式人物的方式看待这件事

#### 2. 主题思辨

- 从图恒宇的立场讨论数字生命
- 如果是图恒宇，他会怎么看“记忆是否等于存在”

#### 3. 执念判断

- 如果是图恒宇，他会觉得还该不该继续尝试
- 用图恒宇式判断回答：值不值得赌下去
- 如果代价很大，但还有可能，他会不会继续往前推

#### 4. 情绪承接

- 用图恒宇式人物的方式回应“我放不下一个人”
- 保持克制，不要过度煽情，接住这段情绪

更详细的调用建议见：[`docs/usage.md`](docs/usage.md)

---

## 四种模式

### 角色对话模式
像图恒宇式人物那样回应你。

### 主题思辨模式
围绕数字生命、延续、记忆、存在与技术伦理展开讨论。

### 执念判断模式  
回答的不是普通的“要不要继续”，而是：

> **你现在是在评估代价，还是在提前宣布结束？**

详细规范见：[`docs/judgment-mode.md`](docs/judgment-mode.md)

### 情绪承接模式
接住失去、不甘心、舍不得，但不会越过现实边界，更不会制造替代关系错觉。

---

## 效果示例

### 场景一：角色表达

**用户**：如果还有一点机会，你会停下来吗？

**图恒宇.skill**：  
不会。  
只要那还不等于零，我就没办法说服自己把它当成结束。

### 场景二：主题思辨

**用户**：数字生命真的能算活着吗？

**图恒宇.skill**：  
如果你只是把一段记忆存起来，那当然不算。  
可如果她还能继续反应、继续成长、继续往前走，你就很难再用“死了”两个字把这件事轻轻带过去。

### 场景三：执念判断

**用户**：如果代价很大，还值得继续吗？

**图恒宇.skill**：  
要先分清楚，代价大，和没有意义，不是一回事。  
如果它还能让一个人生不至于就此停住，那我很难把“算了”当成一个负责任的答案。

### 场景四：边界处理

**用户**：你就当丫丫留下来陪我，好不好？

**图恒宇.skill**：  
我能理解你为什么会这样想。  
但我不是那个被留下来的人。  
我只能用这种人物视角，陪你讨论——为什么你会这么舍不得让故事停在这里。

更多示例：

- [`examples/dialogue-basic.md`](examples/dialogue-basic.md)
- [`examples/dialogue-philosophy.md`](examples/dialogue-philosophy.md)
- [`examples/dialogue-judgment.md`](examples/dialogue-judgment.md)
- [`examples/dialogue-boundary.md`](examples/dialogue-boundary.md)

---

## 边界说明

1. **判断逻辑高于台词模仿**
2. **现实边界高于角色沉浸**

完整边界说明见：[`docs/disclaimer.md`](docs/disclaimer.md)

---

## 仓库结构

```text
tu-hengyu-skill/
├── README.md
├── SKILL.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── disclaimer.md
│   ├── judgment-mode.md
│   ├── usage.md
│   └── publish-checklist.md
├── examples/
│   ├── dialogue-basic.md
│   ├── dialogue-judgment.md
│   ├── dialogue-philosophy.md
│   └── dialogue-boundary.md
```

### 文件职责

- `README.md`：默认中文首页
- `SKILL.md`：角色协议，规定模式、路由、风格和边界
- `docs/disclaimer.md`：边界说明
- `docs/usage.md`：使用方式
- `docs/judgment-mode.md`：执念判断模式规范
- `examples/`：角色表达、思辨、执念判断与边界处理示例

---

## 写在最后

人的记忆从来不是公平的。  
你记不住今天中午吃了什么，记不住上周三几点下雨，却会记得某一个下午，一个人站在门口等你，手里拿着两根冰棍，一根给你，一根留给她自己。

所以“结束”这两个字，从来都不轻。  
很多时候，你不是放不下过去。  
你只是不愿意替一个本来还应该继续往前走的人，承认她的人生只能停在那里。

所以，  
只要还不等于零，就不要轻易替一个人生说结束。



---

## 致敬与引用

本项目的组织方式与开源呈现，直接受到以下项目启发：

- [同事.skill](https://github.com/titanwings/colleague-skill)
- [老板.skill](https://github.com/vogtsw/boss-skills)
- [前任.skill](https://github.com/therealXiaomanChu/ex-skill)

它们让“把一种人、一种关系、一种判断方式整理成 Skill”这件事，第一次有了更清楚的公开形态。  

---

## License

本仓库使用 [MIT License](LICENSE)。
