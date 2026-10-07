<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme-assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="readme-assets/header-light.svg">
  <img alt="毕业设计人因仿真资料 · ✦ EricMingle69" src="readme-assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="PERSONAL-NOTICE.md">✦ EricMingle69</a>
</p>

# 毕业设计人因仿真资料

## 项目定位

人因仿真毕业设计的脚本、方法说明、参数表与历史结果导航，内容集中在 `01仿真数据/`。

## 阅读入口

| 入口 | 内容 |
| --- | --- |
| [文件结构说明](01仿真数据/文件结构.md) | 旧顶层名为“仿真3.0”，实际路径以仓库为准 |
| [仿真方法](01仿真数据/1仿真总结/仿真方法/) | 方法与流程文档 |
| [数据加载](01仿真数据/数据加载.py) | 研究脚本入口 |
| [正交设计](01仿真数据/正交设计.py) | 研究脚本入口 |
| [综合计算](01仿真数据/综合计算.py) | 研究脚本入口 |
| [历史结果](01仿真数据/结果/) | 保存的计算产出 |
| [仿真总结](01仿真数据/1仿真总结/) | 研究说明与历史产出 |

## 从哪里开始

1. 从文件结构与仿真方法了解研究组成，再阅读三个 Python 入口。
2. 复现前明确 Python/库版本、执行顺序、参数来源和模型假设。
3. 参数目录与历史结果可用于定位材料，不能仅凭文件名推断数据有效性。

## 使用边界

- 仓库是研究资料归档，尚无依赖清单或统一启动指南。
- 人体测量与其他参数表的来源、作者、适用范围和分享权限未明确。
- 仿真结果未经独立复核，不能直接用于人体安全决策。

## 来源与原有许可

保留研究参与者、数据作者及引用材料的原有归属。原仓库未提供 LICENSE/NOTICE，代码、参数和研究资料的授权需要分别确认。

---

文档维护：**✦ EricMingle69** · [Ming-Sir-69](https://github.com/Ming-Sir-69)  
[个人标识、许可与权限说明](PERSONAL-NOTICE.md) · 明暗页眉随 GitHub 主题自动切换。
