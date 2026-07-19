# Data CartoonSynth

把文章中的抽象观点转化为清晰、克制、带黑色幽默的红黑社论插图。

这个 skill 以数据分析师为固定观察者，融合三套方法：

- 熟悉的小寓言优先，避免需要解释的抽象符号
- 一张图只表达一个矛盾、一个关键道具和一个荒诞动作
- 松弛钢笔线条、大面积留白与朱红色 `#E34234`

## 核心流程

1. 深度阅读并提炼核心矛盾
2. 从生活寓言、成语母题或数据隐喻中提出两个候选场景
3. 检查语义是否跑偏，并执行三秒可读性测试
4. 在用户确认场景后生成图片
5. 隐去标题做盲审，检查红色是否有明确作用

## 目录

- `SKILL.md`: 完整工作流与生成规范
- `references/shared-fables.md`: 通俗视觉寓言库
- `references/data-metaphors.md`: 数据分析专用隐喻库
- `references/style-guide.md`: 红黑视觉规范
- `references/cartoonsynth-source.md`: CartoonSynth 原始风格骨架
- `assets/`: 已确认的风格锚点

## 安装

安装到个人 Codex skills：

```powershell
git clone https://github.com/derrickxu1220/data-cartoon-synth.git "$env:USERPROFILE\.codex\skills\data-cartoon-synth"
```

也可以将仓库放入项目的 `.agents/skills/data-cartoon-synth`。

## 使用示例

```text
使用 $data-cartoon-synth 阅读这篇文章，先给出两个不依赖标题也能看懂的视觉寓言。不要生成图片，等我确认场景后再画。
```

默认不会直接生成一组未经确认的插图。对于明确指定并已确认的场景，可以直接进入单图生成模式。
