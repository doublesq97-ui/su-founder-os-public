# Su-Founder OS｜公开参考版

> 让 AI 按需调用长期判断，而不只是记住过去的结论。

AI 可以越来越快地给方案、写内容和推进执行，但速度不会自动保存一个人为什么这样选择、主动放弃了什么，以及什么变化出现后值得重新评估。

Su-Founder OS 是一套个人判断操作系统。它不收集所有聊天，也不替人思考；它保存经过验证的原则、重要选择的理由、实验结果和可复用能力，让未来的自己与 AI 能够继续沿着同一条判断链工作。

![Su-Founder OS Router 运行图](assets/founder-os-router-flow.svg)

## 它与知识库有什么不同

| 知识库更擅长回答 | Founder OS 更擅长回答 |
|---|---|
| 我知道什么？ | 我为什么这样选？ |
| 有哪些资料、观点和方法？ | 当时有哪些约束、证据和取舍？ |
| 最后的结论是什么？ | 什么变化出现后值得重审？ |

Founder OS 保护的不是过去答案的永久正确，而是判断的连续性：看得见过去，理解得了现在，也保留主动改变的权利。

## 公开结构

| 模块 | 作用 |
|---|---|
| 判断底座 | 保存长期定位、价值原则与判断边界 |
| 产品判断 | 从真实场景、用户摩擦和证据走向功能取舍 |
| 用户与商业 | 理解用户阻力、购买触发和交付边界 |
| 决策记录 | 保存重要选择的理由与复查条件 |
| 实验与失败 | 记录假设、证据、停止条件和可迁移经验 |
| [AI 路由](docs/router-system.md) | 为当前问题调用最少但足够的长期上下文 |
| 执行接口 | 保存可复用提示、能力与交接方式 |
| 维护机制 | 管理捕获、验证、晋升与定期清理 |

完整说明见 [《Founder OS 公开介绍》](docs/introduction.md)。

## 最短使用方式

1. 阅读公开介绍，理解系统解决什么问题。
2. 复制一份 [Decision Log](templates/decision-log.md)，记录下一次重要取舍。
3. 复制一份 [Experiment Review](templates/experiment-review.md)，记录下一次真实验证。
4. 当你已经积累了一些原则、历史决定或可复用能力后，使用下面的快捷调用。

```text
使用 Founder OS Router 分析下面的问题。
按需读取相关 Reference、Skill 与历史 Decision；
先解决当前问题，再判断是否值得沉淀：

[你的问题]
```

使用说明和缺失上下文的处理方式见 [《快捷调用》](docs/quick-call.md)。完整的通用路由规则与 Prompt 分别见 [《公开路由系统》](docs/router-system.md) 和 [Router Prompt](prompts/founder-os-router.md)。

## 公开版不包含什么

这个仓库只公开结构、方法、空白模板和通用示例，不包含：

- 个人成长、家庭或身份经历；
- 真实产品、客户、金额和资源配置；
- 私人 Decision Log、失败记录和未公开商业判断；
- 本机路径、私密仓库、内部工具配置和历史提交。

公开版可以帮助你搭建自己的 Founder OS，但不会替你生成属于你的判断。真正有价值的内容必须来自你的真实经历、选择和验证。

## 使用边界

欢迎个人和非商业场景学习、复制、修改，并据此搭建自己的 Founder OS。

- 私人自用时，不要求公开署名，也不要求公开你的修改或个人内容；
- 公开转载或公开发布改编版时，需要保留来源、标明修改并使用同一许可；
- 付费课程、商业咨询、企业交付、会员资料、商业软件、SaaS 和其他主要面向商业利益的使用，需要事先获得书面授权。

本仓库采用 [CC BY-NC-SA 4.0](LICENSE.md)。具体边界见 [NOTICE](NOTICE.md)。

## 内容索引

- [Founder OS 公开介绍](docs/introduction.md)
- [Founder OS 公开路由系统](docs/router-system.md)
- [快捷调用](docs/quick-call.md)
- [Founder OS Router Prompt](prompts/founder-os-router.md)
- [Decision Log 空白模板](templates/decision-log.md)
- [Experiment Review 空白模板](templates/experiment-review.md)
- [许可说明](LICENSE.md)
- [实际使用边界](NOTICE.md)
