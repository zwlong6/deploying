# Deploying 项目

这是一个简单的部署页面项目，可以轻松部署到Vercel等平台。

## 项目特点

- 🎨 现代化的渐变背景设计
- 📱 完全响应式，支持移动端
- ⚡ 纯静态HTML，加载速度快
- 🚀 零配置部署到Vercel

## 部署到Vercel

### 方法1：通过Vercel Dashboard（推荐）

1. 访问 [vercel.com](https://vercel.com) 并登录
2. 点击 "New Project"
3. 导入您的GitHub仓库
4. 选择项目根目录
5. 点击 "Deploy"

### 方法2：通过Vercel CLI

```bash
# 安装Vercel CLI
npm i -g vercel

# 在项目目录下运行
vercel

# 按照提示完成部署
```

### 方法3：通过GitHub集成

1. 将代码推送到GitHub
2. 在Vercel中连接GitHub账户
3. 选择仓库并自动部署

## 项目结构

```
deploying/
├── index.html          # 主页面文件
├── vercel.json         # Vercel配置文件
├── README.md           # 项目说明
└── LICENSE             # 许可证文件
```

## 自定义配置

### 修改页面内容

编辑 `index.html` 文件中的：
- 标题文本
- 头像图片链接
- 颜色主题
- 动画效果

### Vercel配置

`vercel.json` 文件包含：
- 构建配置
- 路由规则
- 缓存策略

## 注意事项

- 确保所有图片资源使用HTTPS链接
- 如果需要使用XLSX功能，请确保相关库已正确引入
- 部署后可能需要几分钟才能生效

## 许可证

详见 [LICENSE](LICENSE) 文件
