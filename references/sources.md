# Source notes

维护或解释本技能依据时读取；日常写作无需加载，也不依赖联网。以下是 2026-09-05 读取原始文件后的取舍记录。规则按本地用途重新编写，未整包移植；上游后续可能变化。

| 原始来源 | 采用的思路 | 本地取舍 |
|---|---|---|
| [blader/humanizer](https://github.com/blader/humanizer/blob/main/SKILL.md) | 改后检查主张是否改变；文件编辑保护非正文内容；按请求决定输出形式。 | 保留原有句式审校，默认交付所需成稿或诊断；不固定输出多轮草稿。 |
| [hannsxpeter/humanizer](https://github.com/hannsxpeter/humanizer/blob/main/SKILL.md) | 好稿应少改；语义复核可以撤销风格编辑；不借“声线”补造事实。 | 按请求和理解障碍决定力度，允许零改；不采用密度阈值、刻意节奏变化或自动添加立场。 |
| [coreyhaines31/marketingskills · copy-editing](https://github.com/coreyhaines31/marketingskills/blob/main/skills/copy-editing/SKILL.md) | 分开看清晰度、语气与证据；后一步不能破坏前一步。 | 压缩为理解与结构、语言、语义复核；不将营销情绪、转化目标和七轮审校推广到所有文体。 |
| [obra/the-elements-of-style · writing-clearly-and-concisely](https://github.com/obra/the-elements-of-style/blob/main/skills/writing-clearly-and-concisely/SKILL.md) | 相关成分靠近；修饰对象清楚；具体表达；删除冗词。 | 将读者理解放在句式清理之前；英文习惯不作为中文、法律或学术写作的统一硬规则。 |
| [ai-zixun/humanizer-zh](https://github.com/ai-zixun/humanizer-zh/blob/main/SKILL.md) | 中文翻译腔、全文主线和术语一致性需要单独处理。 | 保留自然省略、功能性破折号和专业缩写；示例自行编写并核对语义。 |

通过 [skills.sh · humanizer](https://www.skills.sh/blader/humanizer/humanizer) 和 [skills.sh · copy-editing](https://www.skills.sh/coreyhaines31/marketingskills/copy-editing) 发现并交叉核对仓库归属；技能站展示或安装量不作为写作效果证据。

当前写作规则以 SKILL.md 为准；本文件保留来源研究和维护取舍。

## 版本核对与维护取舍

2026-09-18 对照了 8 月初版的创建记录、9 月 5 日的修订记录、本轮精简前的完整文本，以及下列 Git 提交。建库前的版本从会话记录核对，不属于仓库的 Git 历史。

| 版本 | 变化 |
| --- | --- |
| 8 月初版 | 建立句式审校、事实与个人声线保护、按文体处理和交付检查。 |
| 9 月 5 日修订 | 区分修改模式，补充事实限定、文件内容保护、指代和中文翻译腔处理。 |
| 本轮精简前 | 增加清晰英语和简单句指导，保留完整句式分类。 |
| `a736b0e` | 强化口语化与回答范围，但过度压缩了句式规则和含义保护。 |
| `c058240` | 加入双逗号插入语与横线限制。 |
| `cb1b3d4` | 恢复排比等核心句式规则，尚未补齐其他遗漏。 |

本次核对后的保留位置：

| 规则组 | 权威位置与处理 |
| --- | --- |
| 事实、归属、引用和判断强度 | 主文件 Meaning，恢复独立要求与复核。 |
| 修改模式、题目范围和文件结构 | 主文件 Scope，保留后来新增的只改回答要求。 |
| 简单自然的表达、指代、术语一致性 | 主文件 Voice，补回理解和逻辑要求。 |
| 三项堆叠、排比、假对比、伪范围、设问和升华 | 主文件 Sentence patterns，中英文指南提供变体与示例。 |
| 中文省略、翻译腔及文体细节 | 语言指南和 genre profiles，恢复有独立作用的内容。 |
| 原文对照、停止修改、干净交付 | 主文件 Finish，恢复检查并保持内部执行。 |

旧版允许功能性破折号的一般建议已被用户后来的标点要求取代。口语化和简洁要求继续有效；删掉的是重复表述，保留的是有不同作用的规则。
