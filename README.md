# Shinji

我现在主要在学全栈开发、AI Agent 和开源协作。

这个主页放我真正做过、能继续维护的项目和贡献。项目不一定都很大，但我希望每个东西都有清楚的用途，也能经得起一点点实际验证。

## 最近在做

- 做一个本地优先的多 Agent 编程协作工具，重点练 `Issue -> 分析仓库 -> 改代码 -> 跑测试 -> review diff` 这条闭环
- 继续给大型开源项目提 PR，优先做能复现、能测试、能解释清楚的小修复
- 把自己的项目 README、测试和发布流程整理得更像真实项目，而不是只放一份代码

## 开源贡献

已有 5 个公开开源 PR 合并，包括：

- [OpenHands #17469](https://github.com/OpenHands/OpenHands/pull/17469)：修复 token 数量紧凑显示在四舍五入后跨单位时显示成 `1000.0k` 的边界问题
- [typescript-eslint #12845](https://github.com/typescript-eslint/typescript-eslint/pull/12845)：修复 `unbound-method` 对 `Intl.Collator.compare` 的误报，按 ECMA-402 规范补回归用例
- [vitest #11187](https://github.com/vitest-dev/vitest/pull/11187)：修正用户可见错误消息和注释里的拼写问题
- [prettier #20003](https://github.com/prettier/prettier/pull/20003)：修正文档/注释拼写

我更看重的是能把问题说清楚：哪里错、怎么复现、为什么这样改、用什么测试证明没有退步。

## 公开项目

### [code-agent-collab](https://github.com/shinji00222/code-agent-collab)

本地优先的多 Agent 编程协作原型。现在主要围绕代码协作闭环做：上下文选择、草稿应用、审批基线、测试和回滚。

### [campus-opportunity-watcher](https://github.com/shinji00222/campus-opportunity-watcher)

校园机会提醒工具，用来整理竞赛、实习和出国相关信息。支持配置不同学校，重点是信息抓取、去重、筛选和提醒。

### [black-persian-cat](https://github.com/shinji00222/black-persian-cat)

Windows 桌面小猫程序。练 Python 桌面应用、打包、Release 和本地安装体验。

### [dsh-windows-computer-use](https://github.com/shinji00222/dsh-windows-computer-use)

Windows 电脑控制插件，让 DSH 读取窗口和控件、执行操作并确认结果。目前是预览版。

## 私有项目经历

### 幼儿园 OA 系统

这是一个已经部署上线的公立幼儿园 OA 项目，已接入企业微信，相关备案也已完成。源码、学校信息和具体部署细节不公开。

我在这个项目里做了登录和权限、审批流、文件中心、考勤等功能，也负责前后端和数据库联调、部署后的检查与维护。

真实学校、人员、账号、服务器、数据库、日志和配置都不会公开。

## 正在补的能力

- C++、Python、TypeScript，以及 PyTorch 和机器学习基础
- 前端、Node.js、MySQL
- Git/GitHub、CI、测试和项目整理
- AI Agent、多 Agent 协作、MCP 和本地工具集成

## 联系

可以通过 [GitHub](https://github.com/shinji00222) 看我的公开项目。

