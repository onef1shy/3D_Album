# 3D Album 🎞️

基于原生JavaScript和CSS3实现的3D旋转相册，无需任何外部依赖。

## 📝 项目说明

这是一个轻量级的3D相册实现，主要特点：
- 纯原生JS实现，无需引入第三方库
- 基于CSS3 3D变换，性能优异
- 简单易用，容易定制

## 📂 文件结构
```
3D_Album/
├── css/
│   └── index.css     # 样式文件
├── js/
│   └── index.js      # 交互逻辑
├── images/           # 图片目录
└── index.html        # 主页面
```

## 💻 技术实现

### 核心技术
- CSS3 transform-style: preserve-3d
- perspective 景深控制
- 事件监听实现拖拽
- webkit-box-reflect 倒影

## 🚀 使用方法

### 快速开始

1. 克隆仓库：
```bash
git clone https://github.com/onef1shy/3D_Album.git
```

2. 修改图片：
   - 将你的照片放入`images`文件夹
   - 在`index.html`中更新图片路径
   - 建议使用相同尺寸的图片（推荐：159px × 240px）

3. 运行：
   - 直接在浏览器中打开`index.html`
   - 或部署到任意Web服务器

### 自定义样式

在`css/index.css`中你可以修改以下属性：

```css
#wrap {
    width: 159px;          /* 相册容器宽度 */
    margin: 150px auto;    /* 位置调整 */
}

#wrap img {
    height: 240px;         /* 图片高度 */
    width: 159px;         /* 图片宽度 */
    border-radius: 10px;  /* 圆角大小 */
}
```

## 📄 许可证

MIT License © [onefishy](https://github.com/onef1shy)

## 🔗 相关链接

- [在线演示](https://onef1shy.github.io/3D_Album)
- [项目介绍](https://onef1shy.github.io/2024/01/24/3D_Album/)

## ⭐ 支持项目

如果这个项目对你有帮助，欢迎给个Star！ 