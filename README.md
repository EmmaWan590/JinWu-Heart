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
| 0 | 手感期：《Python编程：从入门到实践》+ 自己的小脚本，练「读 → 处理 → 写」 | 进行中 |
| 0.5 | MIT Missing Semester —— **不按课时推进，当工具箱按需查阅**（被问题卡住才翻对应那一讲，并做课后练习） | 当字典用 |
| 1 | UCB CS61A —— 先只做 **Lab 1-2 + Homework 1-2** 试水，Project 1 (Hog) 暂缓 | 未开始 |
| 2 | UCB CS61B（数据结构与算法，Java） | 未开始 |
| 3 | CMU 15-213 CSAPP（计算机系统，C） | 未开始 |
| 4 | MIT 6.1810 + Stanford CS144（操作系统 / 计算机网络） | 未开始 |
| 5 | 方向专精（数据库 / AI / 图形学 三选一） | 未开始 |

**为什么这样改（2026-09-20 复盘）**

- 卡住我的**不是"课程太难"，而是课堂一开始就有大量陌生概念**：CS61A 第 4 讲就是 `Higher-Order Functions`，第 5 讲是 `Environments`，第一次讨论课就是 `Environment Diagrams` —— 这些词一个都不认识，后面自然全塌。解法不是重看视频，而是**先补名词、再上课**（见下方「概念卡」）。
- MIT Missing Semester 内容本身不难（csdiy 评级：难度 🌟🌟、预计 10 小时、先修要求「无」），但它教的是**工具**；工具只有在"我正好被这个问题卡住"时才学得进去。**今天学 git 就是最好的例子**：因为要上传脚本、真的踩了坑，几分钟就记住了 `add / commit / push`。
- 起步阶段真正该练的是**手感**：能不能不看资料写出一个 20–40 行、能跑、结果自己核对过的小脚本。这个"能"要重复 10 次，再上 CS61A。

数学并行补（每周 20 分钟 / 天，小剂量）：Khan Academy Algebra 1 → Algebra 2 →（后期）UCB CS70 / MIT 6.042J

## 学习原则（防遗忘的 6 条）

1. **70/30**：70% 时间写代码，30% 看课。只看不写等于没学。
2. **主动回忆**：每学完一节，合上资料默写 5 个要点 + 自出 3 道题。
3. **间隔重复**：Day 1 / 3 / 7 / 15 / 30 复习。卡片只记「概念 + 3 行代码」，不记语法。
4. **不重读**：同一份内容不许反复重读，改成「做题 → 卡住 → 查书 → 合书重做」。
5. **Lab 必须自己写**：卡住先读 handout，再自己 debug，最后才看答案；看完答案要重写一遍。
6. **卡点日志**：凡是「看了 3 遍还不懂」的点，写下来。这是理解的裂缝，不是笨。

## 概念卡（一遇到不认识的词，就停在这里记它）

**为什么需要它**：看课"看不懂"，绝大多数时候不是理解力问题，而是**课从第一分钟起就假设你认识一批名词**。不认识名词 → 后面全是噪音（就像没学过"导数"去听微积分）。所以顺序必须反过来：**先补名词，再上课。**

**规则**（就是原则 3 和原则 6 的落地）：

1. 一遇到不认识的词，**立刻停下来**记下它，别硬听下去。
2. 每个词只记三样：**一句话说明它是什么 + 3 行能跑的代码 + 一个我自己举的例子**。不背定义。
3. **先跑再看**：那 3 行代码一定亲手敲进 Python 跑一遍，看它输出什么。"先会用，后理解"是唯一有效的顺序。
4. 同一个词记到**第 3 次还不懂** → 它是**前置缺口**，不是笨：标上「待补」，退回去做更小的练习，**不许硬啃**（这就是原则 4「不重读」的用法）。

| 概念 | 一句话（我自己写的） | 3 行能跑的例子 | 第几次 / 日期 |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

**待补清单（先查这批词，再去看课）**

- **CS61A 前 5 讲会直接出现**：`expression` `value` `type` `operator` `name` `assignment` `function` `argument` `parameter` `return` `docstring` `doctest` `higher-order function` `lambda` `environment` `frame` `scope`
- **Missing Semester 第 1–2 讲会直接出现**：`shell` `prompt` `PATH` `executable` `flag / 参数` `标准输入输出` `重定向` `管道` `通配符` `退出码` `环境变量` `alias`

## 卡点日志（原则 6 的落地）

> 凡是「看了 3 遍还不懂」的点，写下来。这是理解的裂缝，不是笨。

| 日期 | 卡在哪（写下原话） | 归类：缺词汇 / 缺前置 / 缺手感 | 下一步 |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |

**归类的意义**：三类问题的解法完全不同，别用错药。

| 类型 | 症状 | 解法 |
|---|---|---|
| 缺词汇 | 名词没听过、英文吃力 | 记概念卡，几分钟能解决 |
| 缺前置 | 每个词都懂，连起来不懂 | **超纲**，标记「以后再回来」，往后退一步 |
| 缺手感 | 看懂了，自己一敲就空白 | **唯一解是写**，再看一百遍也没用 |

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

# Python 环境（项目 venv：装包、跑脚本都用它；绝对路径在任何终端都不会错）
E:\Project_学习仓库\.venv\Scripts\python.exe --version
E:\Project_学习仓库\.venv\Scripts\python.exe -m pip list
E:\Project_学习仓库\.venv\Scripts\python.exe -m pip install <包名>
E:\Project_学习仓库\.venv\Scripts\python.exe -m pip freeze > requirements.txt

# 全局：这台电脑装了哪些 Python
py --version
py -0p
```

**两条纪律（都是踩过坑换来的）**：

1. **提交前必须 `git status`**：`git commit` 提交的是**整个暂存区**，不只是你刚 `git add` 的那一个文件。
2. **推送后向服务器核实**：`git ls-remote origin refs/heads/main`，与本地哈希对一下——本地说"推了"不算，服务器说了才算。

## 环境自检（开完终端先花 3 秒）

| 检查什么 | 命令 | 期望结果 |
|---|---|---|
| 我在仓库里吗 | `git status` | 显示 `On branch main`；若报 `not a git repository`，说明走错文件夹了 |
| venv 激活了吗 | `$env:VIRTUAL_ENV` | 有值；提示符开头也会显示 `(.venv)` |
| `python` 指向谁 | `(Get-Command python).Source` | 指向 `.venv\Scripts\python.exe`；若指向 `WindowsApps\python.exe` 就是**没激活** |

没激活时手动激活：

```powershell
& 'E:\Project_学习仓库\.venv\Scripts\Activate.ps1'   # 前面的 & 不能省
deactivate                                            # 退出
```

> `git` 命令**不依赖** venv（`git.exe` 全局可用）；但 `pip` / `python` **依赖**它。
> 拿不准就用上面那条绝对路径写法，任何终端都不会错。

## 每日工作流（改代码 → 存档 → 上传）

```powershell
git status                        # 1 开工前：先看状态
#   ……改代码、运行、验证……
git status                        # 2 收工前：我改了哪些
git add .                         # 3 暂存（只想存一个文件就写文件名，可按 Tab 补全）
git status                        # 4 ★最关键：确认暂存区里只有要提交的东西
git commit -m "这次改了什么"       # 5 存档（-m 不能省）
git push                          # 6 上传（首次会弹 GitHub 登录，登一次永久记住）
git status -sb                    # 7 确认同步：## main...origin/main（没有 ahead/behind 就成了）
```

## 出问题时先跑这 5 条

```powershell
git status            # 我在什么状态
git diff              # 我改了什么（还没暂存的）
git diff --cached     # 我准备提交什么（已暂存的）
git log --oneline -5  # 最近发生了什么
git reflog            # 所有 HEAD 移动记录 = 误操作的时光机
```

## PowerShell 小坑（Windows 专属）

| 现象 | 正确做法 |
|---|---|
| 命令还在跑，又敲了下一条 | **等提示符 `>` 回来再敲**；要中断按 `Ctrl+C` |
| 从网上抄的命令里有 `&&` | PowerShell 5.1 不支持，改用 `;` 或分两次敲 |
| `git commit` 忘了 `-m` | 会掉进一个不认识的界面：按 `Esc`，输入 `:wq`，回车 |
| 把 git 的中文输出**管道**交给 PowerShell 命令（如 `Select-String`） | 会变乱码（编码不匹配），直接看输出就行 |
| 中文文件名手打容易错 | 按 `Tab` 自动补全，或 `git add .` 后用 `git status` 确认 |

## 换电脑后恢复环境

```powershell
git clone https://github.com/EmmaWan590/JinWu-Heart.git
cd JinWu-Heart
py -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

## 学习日志

| 日期 | 学了什么 | 产出了什么 | 卡在哪 | 下一步 |
|---|---|---|---|---|
| 2026-09-18 | 清理 C 盘（3.1GB→28.6GB）、装 Git、修好 `py` 命令、初始化本仓库 | 本仓库第一次提交 | 无 | 开始 MIT Missing Semester 视频 |
| 2026-09-20 | 打通 VS Code 运行环境（选解释器、运行键）；装 python-docx / openpyxl / pandas 并用 requirements.txt 锁定；学会 git「暂存区 → 提交 → 推送」完整流程 | 《自动化办公_脚本.py》跑通：读 xlsx（header=1）→ 按店铺区汇总，11 行 × 6 列，并上传 GitHub | ①文件缺 `.py` 后缀导致没有运行键 ②忘按 Ctrl+S（编辑器 ≠ 磁盘）③路径把盘符/目录/文件名串在一起 ④全角半角括号导致 KeyError ⑤VS Code 与磁盘文件冲突 ⑥PowerShell 把 git 的中文输出变乱码 | 框架第 6 层：把汇总结果写进 CSV |

