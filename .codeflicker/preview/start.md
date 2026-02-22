# 金融从业者工作场景分析 启动指南

## 项目概述
这是一个纯前端静态HTML项目，用于展示金融从业者工作场景分析与可视化，使用D3.js进行网络图可视化。

## . - 静态Web页面

### 快速启动

```bash
cd /Users/shenlang/Documents/Codeflicker/CF0201_financial
python3 -m http.server 8000
```

**启动后访问**：http://localhost:8000

### 注意事项
- 如果端口8000被占用，先执行 `lsof -ti:8000 | xargs kill -9` 释放端口
- 或使用其他端口：`python3 -m http.server 8080`

```yaml
subProjectPath: .
command: python3 -m http.server 8000
cwd: .
port: 8000
previewUrl: http://localhost:8000
description: 金融从业者工作场景分析与可视化静态页面
```
