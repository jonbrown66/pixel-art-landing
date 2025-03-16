

展示页：https://v0-react-landing-page-black.vercel.app/

### 像素风格着陆页 (Pixel Art Landing Page)

一个使用React、Next.js和Tailwind CSS构建的像素风格响应式着陆页，具有动态主题切换、像素动画效果和现代UI设计。

## 📋 功能特点

- ✨ 像素艺术风格设计
- 🌓 亮色/暗色主题切换
- 🎭 多种像素动画效果
- 📱 完全响应式设计
- 🧩 模块化组件结构
- 🚀 基于Next.js App Router
- 🎨 使用Tailwind CSS进行样式设计
- 🔍 SEO友好


## 🛠️ 技术栈

- **框架**: [Next.js](https://nextjs.org/)
- **UI库**: [React](https://reactjs.org/)
- **样式**: [Tailwind CSS](https://tailwindcss.com/)
- **组件库**: [shadcn/ui](https://ui.shadcn.com/)
- **图标**: [Lucide React](https://lucide.dev/)
- **主题**: [next-themes](https://github.com/pacocoursey/next-themes)


## 🚀 快速开始

### 前提条件

- Node.js 18.0.0或更高版本
- npm或yarn或pnpm


### 安装

1. 克隆仓库


```shellscript
git clone https://github.com/yourusername/pixel-art-landing-page.git
cd pixel-art-landing-page
```

2. 安装依赖


```shellscript
npm install
# 或
yarn install
# 或
pnpm install
```

3. 启动开发服务器


```shellscript
npm run dev
# 或
yarn dev
# 或
pnpm dev
```

4. 打开浏览器访问 [http://localhost:3000](http://localhost:3000)


## 📁 项目结构

```plaintext
pixel-art-landing-page/
├── app/                    # Next.js App Router目录
│   ├── layout.tsx          # 根布局组件
│   ├── page.tsx            # 主页面组件
│   └── globals.css         # 全局样式
├── components/             # React组件
│   ├── about-section.tsx   # 关于我们部分
│   ├── footer.tsx          # 页脚组件
│   ├── hero-section.tsx    # 英雄部分
│   ├── navigation.tsx      # 导航栏
│   ├── pixel-floating.tsx  # 浮动像素动画
│   ├── pixel-landing-page.tsx # 主着陆页组件
│   ├── pixel-particles.tsx # 像素粒子动画
│   ├── pixel-rain.tsx      # 像素雨动画
│   ├── pricing-section.tsx # 价格部分
│   ├── scroll-animations.tsx # 滚动动画
│   ├── showcase-section.tsx # 作品展示部分
│   ├── theme-provider.tsx  # 主题提供者
│   ├── theme-toggle.tsx    # 主题切换按钮
│   └── ui/                 # shadcn/ui组件
├── public/                 # 静态资源
├── tailwind.config.ts      # Tailwind配置
└── next.config.mjs         # Next.js配置
```

## 🎨 自定义

### 颜色主题

你可以在`tailwind.config.ts`和`app/globals.css`中修改颜色主题：

```css
/* 在globals.css中 */
@layer base {
  :root {
    /* 亮色主题变量 */
    --background: 0 0% 100%;
    --foreground: 222.2 84% 4.9%;
    /* 其他变量... */
  }

  .dark {
    /* 暗色主题变量 */
    --background: 220 10% 10%;
    --foreground: 210 40% 98%;
    /* 其他变量... */
  }
}
```

### 动画效果

你可以在`app/globals.css`中修改动画效果：

```css
/* 浮动动画 */
@keyframes float {
  /* 自定义关键帧... */
}

/* 雨滴动画 */
@keyframes raindrop {
  /* 自定义关键帧... */
}
```

### 内容

修改各个部分组件中的内容以适应你的需求：

- `hero-section.tsx` - 更新主标题、副标题和按钮
- `about-section.tsx` - 更新关于我们的内容
- `pricing-section.tsx` - 更新价格方案
- `showcase-section.tsx` - 更新作品展示
- `footer.tsx` - 更新联系信息和链接


## 🔧 高级配置

### 添加新的动画效果

1. 在`app/globals.css`中定义新的动画关键帧
2. 创建一个新的动画组件
3. 在`pixel-landing-page.tsx`中导入并使用该组件


### 添加新的部分

1. 创建一个新的部分组件
2. 在`pixel-landing-page.tsx`中导入并添加该组件
3. 在`navigation.tsx`中添加对应的导航链接


## 📄 许可证

该项目采用MIT许可证 - 详情请参阅[LICENSE](LICENSE)文件。
