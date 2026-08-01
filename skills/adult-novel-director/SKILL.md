---
name: "adult-novel-director"
description: "成人色情小说创作总纲与调度中枢。统一文风规范、决策各子skill的调用时机、管理写作流程与最终自查。撰写、续写、润色或大纲设计任何成人小说章节时，必须先读取本文件确定调用哪个子skill。"
---

# 成人小说创作总纲（Director）

本 skill 是成人色情小说写作的**指挥中枢**。它不提供微观写作技法，而是负责：规定写作全流程、决定何时调用哪个子 skill、统一优先级与冲突裁决规则、汇总最终自查。

适用于**多种背景**的成人色情小说（都市、校园、仙侠、末世、职场、古代等），不绑定任何具体女主或世界观。

## 一、子 skill 体系与调用规则

创作任何内容前，先根据任务类型读取对应子 skill：

| 任务类型 | 必须调用的子 skill |
|---------|------------------|
| 任何写作/续写/润色任务 | [adult-novel-style-and-taboo](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-style-and-taboo/SKILL.md)（文风与禁忌，始终执行） |
| 需要身体描写/拟声词/体液词汇 | [adult-novel-vocabulary](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-vocabulary/SKILL.md) |
| 需要场景/体位/交合动作描写 | [adult-novel-scene-craft](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-scene-craft/SKILL.md) |
| 需要内心独白/心理转化/权力关系 | [adult-novel-psychology](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-psychology/SKILL.md) |
| 需要章节结构/节奏/自查 | [adult-novel-chapter-craft](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-chapter-craft/SKILL.md) |
| 大纲设计 | [adult-novel-chapter-craft](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-chapter-craft/SKILL.md) + [adult-novel-psychology](file:///e:/SNOVEL/%E5%9F%BA%E5%BA%95/skills/adult-novel-psychology/SKILL.md) |

## 二、规则优先级

冲突时按以下顺序裁决：

1. **语言禁忌与标点规范**（style-and-taboo 第二部分）
2. **文风原则**（style-and-taboo 第一部分）
3. **细节描写技法**（vocabulary / scene-craft）
4. **结构与节奏**（chapter-craft）

## 三、标准写作流程

1. 读取本文件 + 任务对应的子 skill（写正文时至少读取 style-and-taboo 与 scene-craft）。
2. 校准大纲（如用户提供）：明确场景、体位、角色、道具、体液累积目标、心理线位置。
3. 分段生成（每段 2000-5000 字），段与段之间情节连续不中断。
4. 合并：去除中间过渡标题，确保行文如一次性成文般流畅。
5. 逐项核对自查清单（chapter-craft 第五部分）。

## 四、通用要求（所有写作必须遵守）

- **合规内的极限强化**：在零违规（禁用词/标点/结构）前提下，把反差、破坏感、体液饱和、淫语直给度推到极限——宁可在合规边缘"过"，不可"点到为止"式收着写。执行标准：style-and-taboo 的 0.2 细节三实、1.4 饱和终局三层、1.5.1 插入深度层级；scene-craft 的铁链悬吊写法；psychology 的淫语三层递进。
- 超长单章 8000-15000 字；短章/番外按用户指定字数执行。
- **强制强化六要素**：身体、淫荡表现、体液、性爱动作、性器、迎合六类描写必须密集铺陈（详见 style-and-taboo 的 0.1 强制强化六要素），任何 H 段落不得一笔带过。
- 女主必须体现主动享受与沉溺（主动迎合、主动索求、主动榨取），严禁"冷漠工具"或"麻木死鱼"。
- 场景切换禁止使用分割线（---），靠自然段落或视角切换词过渡。
- 章末禁止上帝视角总结、抒情或点题旁白，一律停留在身体状态与画面本身。
- 对话用中文双引号（" "）；内心独白用（ ）括号标注。
- 每种背景（都市/校园/仙侠/末世/职场）都要让"身份反差"适配该背景的社会结构，而不是机械套用同一套身份。
