# 个人主页

一个现代化、响应式的个人主页模板，使用纯HTML、CSS和JavaScript构建。

## 功能特点

- 🎨 现代化设计风格
- 📱 完全响应式布局
- ⚡ 流畅的动画效果
- 🚀 优化的性能
- 📧 联系表单
- 🎯 平滑滚动导航
- 💫 交互式元素

## 页面结构

### 1. 导航栏
- 固定在页面顶部
- 支持移动端汉堡菜单
- 平滑滚动到对应区域

### 2. 首页区域 (Hero Section)
- 个人介绍
- 职业描述
- 行动按钮
- 个人头像区域

### 3. 关于我
- 个人简介
- 统计数据展示
- 计数动画效果

### 4. 技能展示
- 分类展示技能
- 悬停交互效果
- 图标展示

### 5. 项目展示
- 项目卡片布局
- 技术标签
- 项目链接

### 6. 联系我
- 联系信息
- 联系表单
- 表单验证

### 7. 页脚
- 版权信息
- 社交媒体链接

## 自定义指南

### 修改个人信息

1. **基本信息**：编辑 `index.html` 中的以下内容
   - 姓名：修改 `<span class="highlight">张三</span>`
   - 职业：修改 `<p class="hero-subtitle">全栈开发工程师 & 技术爱好者</p>`
   - 个人描述：修改相应的段落内容

2. **联系信息**：在联系我区域修改
   - 邮箱地址
   - 电话号码
   - 所在位置

3. **社交媒体链接**：修改页脚的社交媒体链接

### 修改颜色主题

在 `style.css` 中修改以下CSS变量：

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #2c3e50;
    --accent-color: #ffd700;
    --background-color: #f8f9fa;
}
```

### 添加项目

在项目展示区域添加新的项目卡片：

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>项目名称</h3>
        <p>项目描述</p>
        <div class="project-tech">
            <span>技术1</span>
            <span>技术2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">
                <i class="fas fa-external-link-alt"></i>
                演示
            </a>
            <a href="#" class="project-link">
                <i class="fab fa-github"></i>
                代码
            </a>
        </div>
    </div>
</div>
```

### 修改技能

在技能区域添加或修改技能项：

```html
<div class="skill-item">
    <i class="fab fa-your-skill-icon"></i>
    <span>技能名称</span>
</div>
```

## 使用方法

1. 下载所有文件到本地目录
2. 根据上述指南自定义内容
3. 在浏览器中打开 `index.html` 预览
4. 部署到你的Web服务器

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

## 技术栈

- HTML5
- CSS3 (Flexbox, Grid, 动画)
- JavaScript (ES6+)
- Font Awesome 图标

## 性能优化

- CSS和JavaScript代码已优化
- 使用了防抖和节流技术
- 实现了懒加载
- 响应式图片处理

## 许可证

MIT License - 可自由使用和修改

## 联系方式

如有问题或建议，欢迎联系！

---

**祝你使用愉快！** 🎉