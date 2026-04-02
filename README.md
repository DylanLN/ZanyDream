[👉 在线体验地址（GitHub Pages）](https://dylanln.github.io/ZanyDream/)

# 癫梦 - 让AI断片，让灵感撒野

![](https://github.com/DylanLN/ZanyDream/blob/main/images/image1.png)

![](https://github.com/DylanLN/ZanyDream/blob/main/images/image2.png)

https://dylanln.github.io/ZanyDream/

## 项目简介

癫梦是一个用于生成 AI 绘画/视频提示词的网页工具，支持词库自定义、镜头分段、修饰词选择等功能，适合灵感创作和分镜头描述。

## 主要功能
- 支持图片/视频两种模式，自动切换参数
- 词库支持 CSV 文件自定义（Excel 可编辑）
- 支持修饰词、主体、动作、场景等多类别词汇
- 镜头可分段、排序、添加/删除
- 一键生成提示词，支持复制
- 响应式设计，手机端体验良好

## 使用方法

### 方式一：直接本地打开
1. 将本项目所有文件（index.html、vocab.csv 等）放在同一目录
2. 用浏览器打开 index.html
3. 注意：部分功能（如复制、读取 CSV）在 file:// 协议下可能受限，推荐使用本地服务器

### 方式二：本地服务器（推荐）
1. 在本项目目录下打开终端
2. 启动本地服务器，例如：
   - Python 3：`python3 -m http.server 8000`
   - Node.js：`npx serve .`
3. 用浏览器访问 http://localhost:8000/index.html

## 词库自定义
- 词库文件为 vocab.csv，支持用 Excel 编辑后另存为 UTF-8 CSV
- 词库字段：类别、类型（mod/word）、词汇

## 移动端适配
- 页面已适配手机屏幕，按钮、输入框、选词区等会自动调整大小和布局

## 常见问题
- 复制按钮、CSV 加载等功能在 file:// 协议下部分浏览器可能受限，建议用本地服务器方式访问
- 如遇样式错乱、功能异常，建议清理浏览器缓存后重试

## 其他示例

![](https://github.com/DylanLN/ZanyDream/blob/main/images/image3.png)

---

如有建议或问题，欢迎反馈。
