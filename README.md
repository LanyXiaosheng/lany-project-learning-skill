# 项目学习：把阅读变成一次行动

本技能将既有学习材料重写为独立方法笔记，不是原文复刻。说明、步骤与边界均可在本仓库内阅读：[方法笔记](references/methods.md)。

## 什么时候用

已经有真实卡点，但阅读笔记总停在“有道理”；也适合练一个明确能力。

## 需要给什么

当前项目问题、实际可读材料、已有理解；可补充可用时间和实践约束。

## 怎么调用

```text
$lany-project-learning-skill
虚构练习：我要给同事解释一个难懂流程，只有半小时。材料说“先分清结构、工具和表达”。请据此设计一次练习，不查别的书，也不要生成整套课程。
```

## 示例结果（虚构演示）

本轮只使用所给片段，不代表读过整本书。
问题：同事是否能知道每一步为什么出现、该怎么操作。
方法：先画流程骨架，给每一步配输入与输出，再用自己的话说明。
练习：用 10 分钟写三步草稿，邀请一位自愿同事复述；记录他首先卡住的位置。
反例：如果卡点是缺少操作权限，改表达无法解决。
复盘：区分结构不清、步骤缺失和术语不懂，下轮只改一个主要问题。
该方案是基于片段的编者操作化，尚未执行。


## 交付与边界

技能会提供具体判断、动作和验证方式。它不会把示例当成你的经历，也不会仅凭作者的成功故事承诺结果。文件创建或更新仅在当前任务确有需要且范围明确时进行。

[查看完整技能定义](SKILL.md)。

## 补充用法

增加闭卷重建与自己的例子/反例检查，定位真正缺失的理解环节。用户只要摘要时不会强迫做练习。

调用示例：`$lany-project-learning-skill 这是我读后写的解释和原文，请找第一个逻辑缺口，给一个迁移练习，不替我声称已经掌握。`

[阅读方法笔记](references/methods.md)。

## 独立仓库与安装

仓库：[lany-project-learning-skill](https://github.com/LanyXiaosheng/lany-project-learning-skill)。本仓库根目录即技能目录，包含 `SKILL.md`、本说明及 `references/`。

确认目标目录不存在后，可在未设置 `CODEX_HOME` 的默认环境下安装：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/LanyXiaosheng/lany-project-learning-skill.git ~/.codex/skills/lany-project-learning-skill
```

已设置 `CODEX_HOME` 时，将目标改为该目录下的 `skills/lany-project-learning-skill`。已有同名技能时先比较或备份，不覆盖。客户端发现技能后，使用 `$lany-project-learning-skill` 调用。

当前版本附自包含方法笔记，无需访问外部原文；现有仓库提交历史保留。

## 操作手册

[本地操作手册](references/workbook.md)包含可填写模板、完整虚构案例、反例与验收步骤，可与方法笔记配合使用，无需访问原文网站。
