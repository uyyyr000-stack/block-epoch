# 方块纪元 · Block Epoch

一个在浏览器中运行的 Minecraft 风格方块世界游戏，使用 WebGL2 渲染。

## 在线游玩

[点击进入方块纪元](https://uyyyr000-stack.github.io/block-epoch/)

建议使用桌面浏览器，以及键盘和鼠标。浏览器和显卡需要支持 WebGL2。

## 本地运行

下载本仓库后，使用浏览器打开 `index.html`。也可以在项目目录启动静态服务器：

```bash
python -m http.server 8000
```

然后打开 http://localhost:8000 。

## 基本操作

- `W A S D`：移动
- 鼠标：调整视角
- `Space`：跳跃
- `Shift`：潜行
- `Ctrl`：疾跑
- `E`：打开背包
- `Q`：丢弃手持物品

更多功能和画面设置请查看游戏内菜单。

## 文件说明

- `index.html`：完整游戏程序，包含界面、JavaScript 和着色器代码。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

上传版本对应 2026 年 9 月 29 日保存的本地文件，游戏代码保持原样。页面使用 Google Fonts 加载字体。

本项目为 Minecraft 风格的独立网页作品，与 Mojang 或 Microsoft 无隶属或官方合作关系。
