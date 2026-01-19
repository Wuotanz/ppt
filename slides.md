---
theme: seriph
background: lasa.jpg
class: text-center
highlighter: shiki
lineNumbers: false
info: |
 ## Slidev Starter Template
 Presentation slides for developers.

 Learn more at [Sli.dev](https://sli.dev)
drawings:
 persist: false
transition: slide-left
title: xgh博士申请考核
mdc: true

---

# 博士研究生申请考核汇报  
## 伦理学方向

**解光环**  
西藏民族大学  
---

# 考生基本情况  
## Self-Introduction

Good morning, professors.

My name is Guanghuan Xie.  
I hold a bachelor’s degree in Applied Psychology and am currently completing my master’s studies.

My academic background combines psychology, philosophy, and ethics.  
In recent years, my main research interest has focused on artificial intelligence ethics,  
especially moral judgment, responsibility, and ethical risks in AI-assisted decision-making.

Thank you for your attention.

---

# 教育背景

- **本科阶段**  
  安徽师范大学 · 应用心理学  
  学习心理学理论、统计方法与实验研究

- **硕士阶段**  
  西藏民族大学 · 宗教学  
  接受哲学、伦理学与跨学科研究训练  
  研究逐步转向伦理学与技术问题

---

# 学习成绩与获奖情况

- 获得研究生学业奖学金  
  （2023–2024 学年，2025–2026 学年）

- 全国哲学研究生学术创新论坛  
  论文二等奖（中国人民大学）

- 硕士阶段在系统完成宗教学与哲学相关课程训练的基础上，重点接受了规范伦理学、诠释学与证词哲学方向的科研训练，积极参与校内外学术交流。期间多次参加全国性学术会议与研究生论坛，包括第一届中国科技伦理高峰论坛、第九届中国诠释学青年论坛、2024年中国诠释学专业委员会年会等，并在中国人民大学哲学院举办的全国哲学研究生学术创新论坛中进行论文汇报并获二等奖。同时，围绕证词哲学与人工智能伦理问题开展研究，已有论文发表于学术期刊，另有英文论文进入国际期刊外审阶段，逐步形成较为清晰且稳定的研究方向。

---

# 外语与技术能力

- **英语能力**  
  能够阅读本领域英文文献  
  并借助 AI 工具进行学术写作与整理

- **德语基础**  
  系统学习德语  
  用于阅读德国哲学与伦理学文献

- **计算机与技术能力**  
  - 国家计算机三级（优秀）  
  - 熟悉 AI 工具与科研辅助系统  
  - 具备基础编程理解能力

---

# 科研能力  

## 研究兴趣的形成

- 本科阶段关注心理机制与判断行为  
- 硕士阶段转向伦理学与规范问题  
- 随着 AI 技术进入判断与决策领域  
  开始系统关注人工智能伦理问题

研究核心：  
**当判断不再完全由人类完成时，伦理结构如何变化**

---

# 硕士阶段科研工作

- 关注大语言模型在伦理判断中的作用  
- 分析 AI 是否能够提供可依赖的道德建议  
- 探讨人类在 AI 介入下的责任变化与能力退化风险

研究以规范伦理分析为主  
而非技术系统设计

---

# 已取得的科研成果

- *Why AI Cannot Be a Moral Expert: A Critique of Computational Reflective Equilibrium and the AI Illusion*  
  提出对 AI 道德专家论的系统批判  
  （Science and Engineering Ethics，外审中）


- 本文聚焦当代 **AI 道德专家论**，重点分析以大语言模型（LLMs）与**计算反思平衡**为核心的主流论证路径  
- 该立场依赖两项关键前提：  
  - 反思平衡方法足以奠定道德判断的规范正当性  
  - LLM 生成的道德判断具有可靠的认识论地位  
- 文章论证表明，上述前提分别面临**输入依赖问题**与**AI 幻觉引发的认识论不足**，并在论证中形成循环  
- 基于此，本文不赞成 AI 作为**独立道德专家**的强主张，转而支持更为审慎的 **AI 道德助手论**

---

```mermaid

flowchart TD
    A[问题提出<br/>AI 是否可以成为道德专家？] --> B[支持者立场：AI 道德专家论]

    %% 支持论证结构
    B --> B1[技术基础：<br/>LLMs + 计算反思平衡（CRE）]
    B --> B2[经验辩护：<br/>AI 在道德建议上表现优于或不弱于人类专家]
    B --> B3[规范辩护：<br/>满足“专家”定义 → 具备认知优势]

    %% 支持者核心推理
    B1 --> C1[CRE 与反思平衡法在结构上类比]
    B1 --> C2[LLMs 具备大规模道德相关知识]
    B3 --> C3[若具备认知优势 → 可被合理信任]

    %% 第一条核心批判
    C1 --> D1[问题一：反思平衡方法的不足]
    D1 --> D1a[反思平衡无法保证道德正当性]
    D1 --> D1b[不合理前见<br/>可通过反思平衡被“合理化”]
    D1 --> D1c[需要预设道德知识<br/>→ CRE 不具备独立技能]

    %% 推论
    D1 --> E1[结论一：<br/>CRE 不能凭反思平衡本身成为道德专家]

    %% 第二条核心批判
    C2 --> D2[问题二：AI 幻觉（Hallucination）]
    D2 --> D2a[LLMs 基于统计相关性<br/>而非理解与因果推理]
    D2 --> D2b[可能生成“看似合理但虚假”的道德论证]
    D2 --> D2c[缺乏信念、理由与可解释性]

    %% 认识论后果
    D2 --> E2[结论二：<br/>AI 提供的道德判断不构成知识]

    %% 循环论证揭示
    E1 --> F[循环论证显现]
    E2 --> F
    F --> F1[CRE 的权威性依赖道德知识]
    F1 --> F2[但道德知识又依赖 CRE 的可靠性]

    %% 总结性否定
    F --> G[总体结论：<br/>AI 道德专家论不成立]

    %% 退一步方案
    G --> H[替代方案：AI 道德助手论]
    H --> H1[AI 提供多角度道德分析与信息整合]
    H --> H2[最终判断与责任<br/>仍由人类主体承担]

    %% 最终立场
    H --> I[研究立场：<br/>AI 适合作为道德决策的辅助工具<br/>而非独立道德权威]
    
%% ========= 高亮样式定义 =========
classDef critique fill:#e6f2ff,stroke:#2563eb,stroke-width:3px;
classDef fatal fill:#fee2e2,stroke:#dc2626,stroke-width:3px;
classDef stance fill:#fff7cc,stroke:#f59e0b,stroke-width:3px;

%% ========= 应用高亮 =========

%% 两条核心批判（蓝色）
class D1,D1a,D1b,D1c,E1 critique;
class D2,D2a,D2b,D2c,E2 critique;

%% 循环论证（红色，全文最关键）
class F,F1,F2 fatal;

%% 结论与立场（黄色）
class G,H,H1,H2,I stance;

```

---

# 研究立场与方法

- 不将 AI 视为独立道德主体  
- 反对将伦理判断完全技术化  
- 强调规范伦理学的基础研究

主要方法：
- 规范伦理分析  
- 概念澄清  
- 哲学与道德心理学结合

---

# 博士阶段研究计划

- 博士阶段研究以**人工智能伦理学**为核心研究方向，重点关注技术系统介入判断与决策过程后，伦理判断结构与责任结构的变化  
- 研究聚焦三类基础问题：  
  - 人工智能是否具备道德判断能力，以及其判断在何种意义上具有规范相关性  
  - 人类在依赖 AI 进行伦理判断与决策时，道德能力是否发生转移或削弱  
  - 人机协同决策情境中，道德责任如何在个体、制度与技术系统之间分配  
- 方法上以**规范伦理学与应用伦理学**为基础，结合对大语言模型行为特征的分析，避免将技术能力直接等同于伦理正当性  
- 研究目标
  - 通过概念澄清与论证分析，为 AI 在伦理领域中的合理定位提供规范依据

  
开展**扎实、可积累的基础伦理研究**

---

```mermaid
flowchart TD
    %% ======================
    %% 核心问题
    %% ======================
    A[研究核心问题<br/>人工智能介入伦理判断后<br/>规范性如何成立]

    %% ======================
    %% 三条研究主线
    %% ======================
    A --> B[研究主线一<br/>AI 是否具备道德判断能力]
    A --> C[研究主线二<br/>AI 作为道德增强工具的条件与风险]
    A --> D[研究主线三<br/>生活伦理中的责任结构重构]

    %% ======================
    %% 第一主线：AI 道德专家论
    %% ======================
    B --> B1[AI 道德专家论]
    B1 --> B2[计算反思平衡<br/>与规范正当性]
    B2 --> B3[判断能力 vs 规范权威]
    B3 --> B4[结论：<br/>AI 不构成道德专家]

    %% ======================
    %% 第二主线：道德增强与风险
    %% ======================
    C --> C1[道德认知卸载<br/>与道德增强]
    C1 --> C2[技术辅助的合理条件]
    C2 --> C3[伦理风险：<br/>能力退化与责任转移]
    C3 --> C4[结论：<br/>AI 仅适合作为辅助系统]

    %% ======================
    %% 第三主线：责任结构
    %% ======================
    D --> D1[日常生活中的 AI 决策系统]
    D1 --> D2[人机协作决策]
    D2 --> D3[多主体责任结构]
    D3 --> D4[规范框架的再调整]

    %% ======================
    %% 方法论整合
    %% ======================
    B4 --> E[研究方法]
    C4 --> E
    D4 --> E

    E --> E1[规范伦理学分析]
    E --> E2[认识论与责任理论]
    E --> E3[技术实践的哲学反思]

    %% ======================
    %% 总体目标
    %% ======================
    E --> F[总体目标<br/>为 AI 伦理判断提供<br/>稳健的规范分析框架]

    %% ======================
    %% 样式定义
    %% ======================
    classDef core fill:#fde68a,stroke:#92400e,stroke-width:2px;
    classDef line1 fill:#e0f2fe,stroke:#0369a1,stroke-width:1.5px;
    classDef line2 fill:#ede9fe,stroke:#6d28d9,stroke-width:1.5px;
    classDef line3 fill:#ffedd5,stroke:#c2410c,stroke-width:1.5px;
    classDef conclusion fill:#fee2e2,stroke:#991b1b,stroke-width:2px;
    classDef method fill:#dcfce7,stroke:#166534,stroke-width:1.5px;
    classDef goal fill:#bbf7d0,stroke:#14532d,stroke-width:2px;

    %% ======================
    %% 样式应用
    %% ======================
    class A core

    class B,B1,B2,B3 line1
    class B4 conclusion

    class C,C1,C2,C3 line2
    class C4 conclusion

    class D,D1,D2,D3 line3
    class D4 conclusion

    class E,E1,E2,E3 method
    class F goal
```

---

# 学术目标与态度

- 长期从事伦理学基础问题研究  
- 保持对技术发展的审慎态度  
- 避免技术乐观主义与空泛规范

---


# 感谢各位老师的聆听。
