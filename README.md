# All-Subject English Enlightenment 导航页面

一个现代化的导航页面项目，为用户提供便捷的网站导航和资源访问服务。

## 项目特点

- 🎨 多主题切换：支持高对比度、柔和、夜间、系统和渐变等多种主题模式
- 🔍 智能搜索：实时搜索功能，快速定位所需资源
- 📱 响应式设计：完美适配各种设备屏幕尺寸
- 🔐 管理员入口：提供管理员登录功能，方便内容管理
- 🎯 分类展示：资源按照不同类别清晰展示
  - ⭐ 常用网站
  - 📚 学习资源
  - 🛠 开发工具
  - 🎨 设计资源
  - 🔧 在线工具

## 技术栈

- HTML5
- CSS3 (响应式设计、Flex布局、Grid布局)
- JavaScript (ES6+)
- SVG 图标
- LocalStorage (主题持久化)

## 快速开始

1. 克隆项目到本地：
```bash
git clone https://github.com/TerryZT/Navigation-Web.git
cd Navigation-Web
```

2. 使用本地服务器运行项目：

可以使用任意一个静态文件服务器，例如：
- Python: `python -m http.server 8000`
- Node.js: `npx serve`
- VS Code: 使用 Live Server 插件

3. 在浏览器中访问：
```
http://localhost:8000
```

## Vercel 部署

1. 安装 Vercel CLI:
```bash
npm install -g vercel
```

2. 部署项目:
```bash
vercel
```

3. 设置环境变量:
```bash
vercel env add MONGODB_URI production
```

## MongoDB 配置

项目使用 MongoDB 作为数据库后端，需要配置以下环境变量:

- `MONGODB_URI`: MongoDB 连接字符串

本地开发时，可以在 `.env` 文件中添加:
```
MONGODB_URI=mongodb://localhost:27017/navigation
```

生产环境请使用 Vercel 的环境变量配置功能添加 `MONGODB_URI`。

## 使用说明

### 主题切换
- 点击顶部的主题按钮切换不同的显示主题
- 主题设置会自动保存到本地

### 搜索功能
- 在搜索框输入关键词可以实时搜索网站
- 支持按标题、描述和关键词搜索

### 管理入口
- 点击顶部的"管理入口"按钮进入管理界面
- 需要管理员账号密码才能登录

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进项目。

## 许可证

本项目采用 MIT 许可证，详见 LICENSE 文件。

## 作者

由 Terry 开发和维护

## 联系方式

- GitHub: [Terry的GitHub主页](https://github.com/TerryZT)