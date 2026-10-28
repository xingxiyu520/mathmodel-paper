# 美赛差异

美赛（MCM/ICM）仍是数学建模论文，不是英文学术期刊论文。国赛的论证要求继续有效：假设要有理由、模型要贴题、结果要回答问题、图要能独立阅读。差异在语言、必写节和页数。

现行规则以 COMAP 当年的 Contest Instructions 为准。课件中的 2021 年日期和页数只作历史例子，写稿前打开当年说明。入口：<https://www.comap.com/contests/mcm-icm>。

## 和国赛不同的地方

- 全文英文。摘要称为 Summary，单独一页，通常还有目录页。不要把国赛“不要目录”搬过来。
- 常见正文上限是 25 页，含 Summary、目录和正文，参考文献和附录另计。以当年说明为准，超过就删综述和通用定义，不删结果。
- 必写或强烈预期的节：Summary、Introduction、Assumptions and Justifications、Model、Results、Strengths and Weaknesses。ICM 常要求 Policy Recommendation 或给非技术读者的备忘录。
- 文献综述是正文的一部分，不是参考文献列表。它要比较已有做法和本题缺口，不堆论文名。
- 引用用文内作者-年份或编号，全文统一，并在 References 中可检索。不编造 DOI 和页码。
- AI 使用按当年 COMAP 政策报告。没有读到当年政策时，不替用户发明合规声明，只保留使用记录并提示用户核对。

## Summary

一页。第一段写问题和总模型，然后按问写方法与结果。数值、单位和方案必须在。英文同样禁止空话：novel, robust, scientific, significant 没有数字就不写。

Summary 不写文献综述，不解释算法历史。

## 文献综述

美赛的综述短。每段处理一类方法，不是一篇论文。

一段的结构：这类方法解决什么，用到本题时缺哪一个条件，本文因此改哪一步。两到四段足够。找不到可靠文献时，写“未检索到可直接使用的数据”，不要造一篇。

综述放在 Introduction 末尾或单独一节，紧接着转入本题的任务分解。

## Assumptions and Justifications

格式与国赛假设相同，英文写成：

> Assumption 2. The benches are rigid. Justification: the problem gives fixed lengths and does not provide a deformation modulus; treating them as rigid keeps the distance constraints geometric.

每条假设在后文模型中被用到。Justification 写条件来源和若不假设会怎样，不写 for simplicity 作为唯一理由。

## 非技术报告

ICM 若要求给市长、渔民或管理者的信，单独成页。信里不出现未解释的符号。只保留决策、代价、条件和不确定处。正文中的模型名可以提一次，不贴公式。

这封信的数字必须和正文一致。先写完正文结果，再写这封信。

## 数据节

Data Description 不是必写节。题目给了数据，或队内采集了数据时，用短节写字段、清洗和可视化结论。清洗规则要能改变后续样本，否则只在附录列。

美赛 C 题可以把数据预处理单列。其余题把数据处理放进用到它的那一问。

## 英文文风

沿用 [文风](voice.md) 的信息标准，不沿用中文连接词表。

少写：it is worth noting that, in today's world, plays a vital role, a novel and robust framework, in conclusion。

多写：变量、约束、数值和比较。一段一个动作。术语全文固定，不在 bench、board、plate 之间换词。

图表标题用英文，坐标轴带单位。图题在下，表题在上，与国赛相同。

## 页数不够时删什么

先删综述中的方法史、软件介绍、重复的流程图。再把中间表和长推导移到附录。不删每问的最终数，不把检验整个删掉。至少留一个参数扰动和它对结论的影响。
