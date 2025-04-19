# 项目展示网站

这是一个用于展示项目运行效果的静态网站。

## 目录结构

```
.
├── index.html      # 主页面
├── images/         # 图片和 GIF 存储目录
└── README.md       # 项目说明文档
```

## 使用说明

1. 将需要展示的图片和 GIF 文件放入 `images` 文件夹中
2. 在 `index.html` 中相应的位置添加图片引用：
   ```html
   <img src="images/your-image.png" alt="图片描述">
   ```
   或
   ```html
   <img src="images/your-animation.gif" alt="动画描述">
   ```

3. 修改 `index.html` 中的文字描述

## 部署到 GitHub Pages

1. 创建一个新的 GitHub 仓库
2. 将所有文件推送到仓库的 main 分支
3. 在仓库设置中启用 GitHub Pages，选择 main 分支作为源
4. 访问生成的 GitHub Pages URL 查看网站

## 自定义样式

您可以通过修改 `index.html` 文件中的 `<style>` 部分来自定义网站样式，包括：

- 颜色主题
- 字体大小
- 布局间距
- 响应式设计

## 注意事项

- 图片文件建议进行适当压缩，以提高加载速度
- GIF 动画文件不宜过大
- 建议使用相对路径引用图片 