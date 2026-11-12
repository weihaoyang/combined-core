# 三盘输入与联合导出 · combined core

本仓从 [知几排盘](https://github.com/weihaoyang/qimen-llm-chart) 提取 TypeScript 计算与测试。联合盘是不同输入和序列化的组合，不是新的独立古代术数。

```sh
npm install
npm run patch:3meta
npm test
npm run typecheck
```

运行前执行依赖补丁；共享时间、排盘模块一并保留，尚未发布 npm 包。入口为 `src/lib/combined`。

## 研究与案例

[研究论文、版本对照与证据边界](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)；独立测试见 `src/lib/combined`。古籍影像不随仓库提供，使用条件见[影像权利记录](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/sources/RIGHTS.md)。

## 授权

代码 [GPL-3.0-only](LICENSE)，依赖与移植代码许可证见 `LICENSES/`；来源及版本见[第三方声明](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/THIRD_PARTY_NOTICES.md)。
