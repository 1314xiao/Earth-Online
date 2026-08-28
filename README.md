Earth Online - 游戏启动界面

一个基于纯前端技术构建的科幻风格游戏启动页面，具有沉浸式的太空主题视觉体验。

📖 项目简介

Earth Online 是一个仿游戏启动器的 HTML 页面，模拟了大型多人在线游戏的登录界面。页面包含动态星空背景、自转地球动画、服务器状态显示以及完整的 HUD 界面元素，为用户提供沉浸式的游戏启动体验。

✨ 功能特性

- 🎮 游戏启动界面 - 点击任意位置触发加载动画并跳转至游戏主页面
- 🌍 动态地球 - 采用 CSS 动画实现地球自转效果，营造太空氛围
- ⭐ 动态星空 - 多层粒子系统模拟星空闪烁效果
- 🎯 HUD 界面 - 包含设置、声音、档案、任务等功能图标
- 📡 服务器状态 - 实时显示服务器连接状态与地区信息
- 📱 响应式设计 - 完美适配移动端与桌面端
- 🔄 加载过渡 - 平滑的加载动画与页面切换效果
- ♿ 无障碍支持 - 支持键盘操作与屏幕阅读器

🛠️ 技术栈

- HTML5 - 语义化标签结构
- CSS3 - 动画、渐变、滤镜、Flexbox/Grid 布局
- JavaScript - 事件处理、DOM 操作、定时器
- SVG - 自定义矢量图标

📂 项目结构

earth-online/
├── index.html          # 主启动页面
├── a.html              # 游戏主页面（示例跳转目标）
├── README.md           # 项目说明文档
└── LICENSE             # 开源许可证

🚀 快速开始

在线预览

直接打开 
"index.html" 文件即可在浏览器中预览效果。

本地开发

1. 克隆仓库：

git clone https://github.com/yourusername/earth-online.git

2. 进入项目目录：

cd earth-online

3. 使用 Live Server 或其他 HTTP 服务器运行：

# 使用 Python
python -m http.server 8080

# 或使用 Node.js
npx serve .

4. 在浏览器中访问 
"http://localhost:8080"

🎨 自定义配置

修改跳转目标

在 
"index.html" 中找到以下代码，修改跳转路径：

window.location.href = './a.html'; // 改为你的目标页面

更换地球图片

找到 
".earth-img" 的 
"background" 属性，替换图片 URL：

background: url('你的图片链接') repeat-x center;

调整服务器信息

修改服务器卡片中的文本内容：

<span>亚洲 · 中国服 · 重庆1区</span>

📱 兼容性

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- iOS Safari 12+
- Android Chrome 60+

🤝 贡献指南

欢迎提交 Issue 和 Pull Request 来改进项目！

1. Fork 本仓库
2. 创建你的特性分支 (
"git checkout -b feature/AmazingFeature")
3. 提交你的改动 (
"git commit -m 'Add some AmazingFeature'")
4. 推送到分支 (
"git push origin feature/AmazingFeature")
5. 开启一个 Pull Request

📄 开源协议

本项目基于 MIT 协议开源，详见 "LICENSE" (LICENSE) 文件。

🙏 致谢

- 背景图片来源于 Unsplash
- 灵感来自各类科幻游戏启动界面

Earth Online - 探索未知，开启你的星际之旅 🚀
本地开发

1. 克隆仓库：
