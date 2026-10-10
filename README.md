<div align="center">


<img src="assets/banner.svg" alt="计算机视觉 · 深度学习 · 桌面应用" width="100%">

# 你好，我是 Echo 👋

用 Python 把模型跑成能用的桌面程序<br>
关注 **目标检测** 与 **PyTorch** 工程实践，也写 C++ / C# 练手

[![GitHub](https://img.shields.io/badge/GitHub-cni30-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/cni30)
[![CSDN](https://img.shields.io/badge/CSDN-%E9%A3%8E%E3%81%AE%E8%A1%97%E9%81%93-FC5531?style=flat-square&logo=csdn&logoColor=white)](https://blog.csdn.net/m0_61713426)
[![Blog](https://img.shields.io/badge/Blog-cni30.github.io-2F80ED?style=flat-square&logo=hexo&logoColor=white)](https://cni30.github.io/)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-ultralytics-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![Qt / PySide6](https://img.shields.io/badge/Qt%20%2F%20PySide6-41CD52?style=flat-square&logo=qt&logoColor=white)

</div>

---

## 关于我

- 主要用 **Python** 做计算机视觉方向的开发：从数据标注、PyTorch 训练与指标对比，到用 **PySide6（Qt 6）** 把模型包成一个能直接运行的桌面程序。
- 最近在推进 **[植物病害检测系统](https://github.com/cni30/plant-disease-detection)** —— 把 YOLO 检测器装进 Qt 界面的毕业设计项目；三次训练的曲线、混淆矩阵与完整文档都在仓库里。
- 平时也写 **C++ / C#** 练手：算法复习、课设小项目都放在 GitHub 上。
- 学习笔记主要写在 [CSDN](https://blog.csdn.net/m0_61713426)：PyTorch 系列、算法刷题（代码随想录）、问题记录；2022–2023 年还搭过一个 Hexo 博客记录 Linux 与算法题解。

### 近期关注

- **目标检测**：YOLO 系列的结构与优化手段 —— R-ELAN 残差结构、Mosaic / MixUp 数据增强、知识蒸馏与轻量骨干。
- **PyTorch 工程实践**：训练流程、指标复现、TensorBoard 曲线分析。
- **算法与数据结构**：持续刷题，把模板与题解整理成笔记。

## 技术栈

按实际用过的项目归类，不标熟练度。

| 方向            | 用到的技术                                                   |
| --------------- | ------------------------------------------------------------ |
| 语言            | `Python`（主力）、`C++`、`C#`、`JavaScript`、`HTML / CSS`    |
| 深度学习 / 视觉 | PyTorch、ultralytics（YOLOv5nu / YOLOv8n / YOLO11n）、OpenCV、NumPy、pandas、Pillow |
| 桌面界面        | PySide6（Qt 6）、QtFusion、Qt Designer                       |
| 数据与存储      | SQLite                                                       |
| 工具链          | Git、Linux、CMake、Conda、TensorBoard                        |

## 代表项目

### [plant-disease-detection](https://github.com/cni30/plant-disease-detection) · 植物病害检测系统（桌面端）

`Python` `PySide6` `ultralytics` `Grad-CAM` `MIT` · 原创

用 YOLO 目标检测做的植物叶片病害识别桌面应用，覆盖 **29 个病害 / 叶片类别**（苹果、番茄、马铃薯、葡萄、玉米等）。

- **四种输入方式**：单张图片、整个图片文件夹、视频文件、摄像头实时画面；结果以标注框、结果表格、按类别计数三种形式呈现。
- **Grad-CAM 注意力热力图**：与检测结果并排显示，能直接看出模型把注意力放在了叶片的哪个位置。
- **三种检测器横向对比**：YOLOv5nu / YOLOv8n / YOLO11n 各训练 120 epochs @ 640 px —— YOLO11n 精确率最高（0.733），YOLOv8n 的 mAP@50 最高（0.626）；三个 run 的真实 `results.csv`、训练曲线与混淆矩阵都保留在仓库里。
- **可换模型、可导出**：模型无需重启即可热切换；单张存 PNG、序列存 AVI、表格存 CSV。
- **文档完整**：中文 / English / Deutsch 三语 README，写明验证环境、局限性与第三方许可（ultralytics 为 AGPL-3.0）。

> 仓库不附带训练权重与数据集，clone 后需要自备 checkpoint，README 里写了两种获取方式。

### [cni30.github.io](https://github.com/cni30/cni30.github.io) · Hexo 个人博客

`Hexo` `HTML` `CSS` · 原创 · [线上地址](https://cni30.github.io/)

Hexo 博客的源码与构建产物。2022–2023 年间写了 12 篇笔记：Linux 基础与 vim 使用（7 篇）、算法模板与题解（4 篇）、测试记录（1 篇）。站点另有 Vercel / Netlify 镜像。

### [C.NET](https://github.com/cni30/C.NET) · 俄罗斯方块

`C#` · 原创

用 C# 实现的俄罗斯方块（`俄罗斯方块.sln`），逐行注释；仓库 README 里写明这是 C# 期末课设。

### [C](https://github.com/cni30/C) · 算法复习

`C++` `CMake` · 原创

一个用 CMake 组织的 C++ 算法练习工程，仓库描述只有一句话：「放一些算法，方便复习」。

**其他仓库**：[firework_to_2023](https://github.com/cni30/firework_to_2023)（JavaScript 写的 2023 新年烟花动画）、[Deep-Learning](https://github.com/cni30/Deep-Learning)（早期的深度学习练习代码）。

## GitHub 数据

<div align="center">


![Followers](https://img.shields.io/github/followers/cni30?style=flat-square&label=Followers&color=2F80ED)
![Last commit](https://img.shields.io/github/last-commit/cni30/plant-disease-detection?style=flat-square&label=Last%20commit&color=22B573)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=cni30&layout=compact&langs_count=8&hide_border=true&theme=github_dark">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cni30&layout=compact&langs_count=8&hide_border=true&theme=graywhite" width="420" alt="最常用语言：Python 91.01%、HTML 7.14%、CSS 0.70%、JavaScript 0.50%、C# 0.41%、C++ 0.12%、C 0.10%、CMake 0.04%">
</picture>


<sub>语言统计来自第三方卡片 github-readme-stats，仅作参考。</sub>

</div>

## 联系

| 入口                                                 | 用途                             |
| ---------------------------------------------------- | -------------------------------- |
| [GitHub · @cni30](https://github.com/cni30)          | 项目问题欢迎直接开 Issue         |
| [CSDN · 风の街道](https://blog.csdn.net/m0_61713426) | PyTorch 笔记、算法刷题、问题记录 |
| [博客 · cni30.github.io](https://cni30.github.io/)   | 2022–2023 年的 Linux 与算法记录  |

---

<div align="center">
<sub>若途遇激励就洒下热血，若身无祥云就心如玄铁。</sub>
</div>

