# 中国科技网站

这是一个使用Hugo框架创建的静态网站，主要用于分享科技资讯和技术内容。

## 特点

- 使用Hugo静态网站生成器
- 自定义主题
- 快速加载
- 部署在Cloudflare Pages上
- 使用Cloudflare CDN加速

## 本地开发

1. 克隆仓库：
   ```
   git clone https://github.com/你的用户名/Chinatech_hugo.git
   cd Chinatech_hugo
   ```

2. 启动本地服务器：
   ```
   hugo server -D
   ```

3. 在浏览器中访问 `http://localhost:1313` 预览网站

## 部署

本网站使用Cloudflare Pages自动部署。每次推送到主分支后，Cloudflare Pages会自动构建和部署网站。
