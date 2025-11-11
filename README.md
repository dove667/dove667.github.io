# 张思华的个人网站 | Zhang Sihua's Personal Website

欢迎来到我的个人网站！这是一个现代化、科技感十足的静态网站，展示了我作为人工智能专业学生的学习历程和项目经验。

## 🌟 网站特色

- **现代化设计**：采用渐变色和流畅动画，打造科技感十足的视觉体验
- **响应式布局**：完美适配桌面端、平板和移动设备
- **丰富内容**：包含个人简介、技能展示、项目案例、教育经历和联系方式
- **交互动效**：打字特效、滚动动画、悬停效果等多种交互元素
- **AI主题**：专为人工智能专业量身定制的设计元素

## 📂 文件结构

```
dove667.github.io/
├── index.html      # 网站主页面
├── styles.css      # 样式文件
├── script.js       # JavaScript交互脚本
├── .gitignore      # Git忽略文件
└── README.md       # 项目说明文档
```

## 🎨 网站板块

1. **首页 (Home)** - 欢迎页面与打字动效
2. **关于我 (About)** - 个人介绍和研究兴趣
3. **技能专长 (Skills)** - 编程语言、AI框架和工具展示
4. **项目展示 (Projects)** - 6个AI相关项目案例
5. **教育经历 (Education)** - 学习经历和荣誉时间线
6. **联系方式 (Contact)** - 联系信息和消息表单

## 🚀 部署说明

### GitHub Pages部署

1. 确保代码已推送到GitHub仓库
2. 进入仓库的 `Settings` → `Pages`
3. 在 `Source` 中选择分支（如 `main` 或 `master`）
4. 点击 `Save`
5. 等待几分钟后，网站将在 `https://dove667.github.io` 上线

### 本地预览

使用任何静态文件服务器即可预览：

```bash
# 使用Python
python -m http.server 8000

# 使用Node.js
npx http-server

# 使用PHP
php -S localhost:8000
```

然后在浏览器中访问 `http://localhost:8000`

## 🛠️ 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和动画
  - Grid & Flexbox布局
  - CSS渐变和过渡效果
  - 响应式媒体查询
- **JavaScript** - 原生JS交互
  - 打字动画
  - 滚动监听
  - 表单处理
  - 交互观察器（Intersection Observer）
- **Font Awesome** - 图标库（通过CDN引入）

## 🎯 主要特性

- ✅ 零依赖（除Font Awesome CDN外）
- ✅ 无需构建工具
- ✅ SEO友好的元标签
- ✅ 流畅的动画效果
- ✅ 优雅的深色主题
- ✅ 移动端优先设计
- ✅ 快速加载速度

## 📝 自定义说明

如需自定义网站内容，请修改以下文件：

1. **个人信息**：编辑 `index.html` 中的文本内容
2. **颜色主题**：修改 `styles.css` 中的 `:root` CSS变量
3. **动画效果**：调整 `script.js` 中的JavaScript代码

### 颜色变量

```css
:root {
    --primary-color: #6366f1;      /* 主色调 */
    --secondary-color: #8b5cf6;    /* 次要色 */
    --accent-color: #ec4899;       /* 强调色 */
    --dark-bg: #0f172a;            /* 深色背景 */
    --text-primary: #f1f5f9;       /* 主要文本 */
}
```

## 📧 联系方式

- 邮箱：zhangsihua@example.com
- GitHub：[github.com/dove667](https://github.com/dove667)
- 微信：zhangsihua_ai

## 📄 许可证

© 2024 张思华. All rights reserved.

---

⭐ 如果你喜欢这个项目，欢迎给个Star！
