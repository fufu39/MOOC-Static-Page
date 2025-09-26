# **中国大学MOOC静态页面复刻**

> 项目完成时间：2024.5
> 

中国大学MOOC静态页面复刻是一个基于原版中国大学MOOC网站的静态页面重现项目。

项目采用HTML、CSS和少量JS构建，集成了iconfont图标库，旨在通过精确还原MOOC网站的视觉效果和布局结构，展示前端静态页面开发的基本技能。

## **✨ 主要功能**

- **完整的首页布局**
  - 顶部导航栏与搜索功能
  - 轮播Banner展示
  - 课程分类与推荐
  - 名师讲堂展示
  - 学习故事与用户评价

  
  
- **用户中心页面**
  - 用户信息展示
  - 课程学习进度
  - 学习记录统计

- **响应式设计**
  - 适配不同屏幕尺寸
  - 保持关键内容可见性

## 🛠️ 技术栈

- **HTML5**：语义化标签结构
- **CSS3**：
  - Flexbox布局
  - Grid网格布局
  - 过渡动画效果
  - 伪类与伪元素
- **iconfont**：图标字体
- **静态资源优化**：图片格式选择与压缩

## 📁 项目结构

```
MOOC静态页面复刻/
├── css/                # 样式文件
│   ├── base.css        # 基础样式重置
│   ├── common.css      # 公共样式
│   ├── index.css       # 主页样式
│   ├── index_banner.css # 首页Banner样式
│   ├── index_content.css # 首页内容区样式
│   └── user.css        # 用户中心样式
├── html/               # HTML页面
│   └── user.html       # 用户中心页面
├── iconfont/           # 图标字体
│   ├── iconfont.css    # 图标样式
│   ├── iconfont.ttf    # 字体文件
│   ├── iconfont.woff   # 字体文件
│   └── iconfont.woff2  # 字体文件
├── images/             # 界面图标与小型图片
├── uploads/            # 内容图片资源
├── favicon.ico         # 网站图标
├── index.html          # 首页
└── README.md           # 项目说明
```

## 🚀 快速开始

1. **克隆项目**
   ```bash
   git clone https://github.com/fufu39/MOOC-Static-Page.git
   ```

2. **本地运行**
   - 直接在浏览器中打开index.html
   - 或使用VSCode的Live Server插件启动



---

**本项目仅供学习交流使用，请勿用于商业目的。**