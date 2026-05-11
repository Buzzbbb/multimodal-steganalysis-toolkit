# 多模态隐写分析检测工具箱

`multimodal-steganalysis-toolkit` 是一个信息隐藏与网络空间安全方向的可运行开源项目，包含核心算法代码、命令行入口、实验配置、示例脚本和 smoke tests。

## Overview

本项目聚焦信息隐藏的检测与取证，提供图像、音频、文本等多模态隐写分析工具。系统包含特征提取、传统机器学习分类器、深度检测模型、交叉验证、误报漏报分析和结果可视化等模块，可用于判断样本是否存在隐藏信息或水印痕迹。项目强调防御侧研究价值，支持构建自定义数据集和统一评测报告，便于开展隐写分析、内容安全检测和多媒体取证实验，并沉淀基线结果、模型配置和样例数据说明材料。

## Features

- 统一的数据加载、实验配置和结果保存流程
- 面向信息隐藏/数字水印/隐写分析任务的模块化设计
- 支持实验指标输出、样例结果归档和后续算法扩展
- 适合课程实验、毕业设计、论文复现实验和课题组日常开发

## Quick Start

```bash
python examples/demo.py
python -m unittest discover -s tests
open docs/visual_report.html
python -m multimodal_steganalysis_toolkit.cli --message "demo payload" --report docs/cli_report.md
```

## Keywords

steganalysis · forensics · multimodal · detection

## Authors

- 负责人：林裕斌
- 参与人：曾科、田承金
- 指导教师：吕善翔
- 单位：暨南大学网络空间安全学院

## License

本项目采用 MIT License 开源。Copyright (c) 2026 Lin Yubin, Zeng Ke, Tian Chengjin, Shanxiang Lv, Jinan University.
