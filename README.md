# Hobart SZE · 个人主页

这是我的个人主页仓库，部署在 GitHub Pages：

**https://hobartsze.github.io**

深色印刷编辑风的单页站：3D 地球仪（金色标记访客位置）、手势旋转、滚动金线。主页本身同时就是一套完整的 Python 教程——往下滚动进入学习路线，41 课全在里面。

## 内容：Python 自学教程

一套为零基础自学者设计的 Python 教程：**41 课、5 个阶段、123 道选择题 + 41 道动手编程题**，从第一行 `print` 一路学到 pandas 数据处理与网络爬虫。

- **打开就能学**：不用注册、不用装软件，浏览器打开即学；
- **当场判定**：选择题点完即判，动手题在浏览器里真跑 Python 当场判定；判定不苛刻——内容对、没语法错误就通过，写错了会直接指出最可能的原因（全角符号、缩进、漏冒号之类）；
- **每课配置**：讲解（含要点速记表）、代码演示（逐字打字＋逐行输出）、逐步执行演示、每道题下方都有 AI 讲解栏（填自己的 API Key 使用，Key 只存在本地浏览器）；
- **专业方向可切换**：例子默认按会计场景（账本、报表）编写，可在页面顶部切换成通用数据场景，代码与练习不变。

同一套教程另有独立仓库（含可下载的单文件版）：

- 教程仓库：https://github.com/HobartSZE/python-tutorial
- 教程在线版：https://hobartsze.github.io/python-tutorial/
- 下载版：仓库里的 `python-space.html`，双击即可打开，单文件、无需安装。

## 仓库结构

```
.
├── index.html          # 主页 + 教程（单文件，GitHub Pages 入口）
├── assets/
│   ├── three.min.js    # 地球仪（本地托管，不依赖外部 CDN）
│   └── lessons/        # 41 张课内截图（看图学）
└── textures/           # 地球仪贴图（昼图 / 法线 / 高光 / 云层）
```

## 反馈与交流

教程的问题与建议统一在教程仓库处理：

- 报 bug、提建议：[Issues](https://github.com/HobartSZE/python-tutorial/issues)
- 交流学习心得：[Discussions](https://github.com/HobartSZE/python-tutorial/discussions)
