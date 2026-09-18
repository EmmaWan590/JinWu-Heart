# JinWu-Heart · CS 自学学习仓库

这是我初入 GitHub 创建的第一个仓库。在这里，我将记录我的学习过程。

参考路线：[CS 自学指南（csdiy.wiki）](https://csdiy.wiki/)

## 目标

- 用 2–3 年时间扎实走完 CS 核心课程（不速成、不让课程在收藏夹里吃灰）
- 每门课一个文件夹，存放：我写的代码、Lab/Project 实现、踩坑笔记
- 每周写一篇学习日志（见文章末尾的表格）

## 学习路线（主线）

| 阶段 | 课程 | 状态 |
|---|---|---|
| 0 | MIT Missing Semester（工具链：Shell / Git / 调试） | 进行中 |
| 1 | UCB CS61A（编程入门，Python） | 未开始 |
| 2 | UCB CS61B（数据结构与算法，Java） | 未开始 |
| 3 | CMU 15-213 CSAPP（计算机系统，C） | 未开始 |
| 4 | MIT 6.1810 + Stanford CS144（操作系统 / 计算机网络） | 未开始 |
| 5 | 方向专精（数据库 / AI / 图形学 三选一） | 未开始 |

数学并行补（每周 20 分钟 / 天，小剂量）：Khan Academy Algebra 1 → Algebra 2 →（后期）UCB CS70 / MIT 6.042J

## 学习原则（防遗忘的 6 条）

1. **70/30**：70% 时间写代码，30% 看课。只看不写等于没学。
2. **主动回忆**：每学完一节，合上资料默写 5 个要点 + 自出 3 道题。
3. **间隔重复**：Day 1 / 3 / 7 / 15 / 30 复习。卡片只记「概念 + 3 行代码」，不记语法。
4. **不重读**：同一份内容不许反复重读，改成「做题 → 卡住 → 查书 → 合书重做」。
5. **Lab 必须自己写**：卡住先读 handout，再自己 debug，最后才看答案；看完答案要重写一遍。
6. **卡点日志**：凡是「看了 3 遍还不懂」的点，写下来。这是理解的裂缝，不是笨。

## 环境信息

| 项目 | 值 |
|---|---|
| 系统 | Windows |
| 编辑器 | VS Code（`E:\Microsoft VS Code`） |
| Git | 2.55.0（`E:\Git`） |
| Python | 3.14.0（`C:\Users\lenovo\AppData\Local\Programs\Python\Python314`） |
| Python 启动器 | Python install manager 26.3（命令 `py`） |
| 本仓库位置 | `E:\Project_学习仓库` |

## 常用命令

```powershell
# 看当前改动状态（最常用，建议每条 git 命令前后各跑一次）
git status

# 提交一次存档
git add .
git commit -m "说明这次改了什么"

# 查看历史（一行一条）
git log --oneline

# Python 环境
py --version
py list
py -m pip install <包名>
```

## 学习日志

| 日期 | 学了什么 | 产出了什么 | 卡在哪 | 下一步 |
|---|---|---|---|---|
| 2026-09-18 | 清理 C 盘（3.1GB→28.6GB）、装 Git、修好 `py` 命令、初始化本仓库 | 本仓库第一次提交 | 无 | 开始 MIT Missing Semester 视频 |

