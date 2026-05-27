# Jinghao Static Website

这是一个静态英文官网，适合 Vercel 免费托管。

## 文件说明
- index.html：首页
- style.css：样式文件

## Vercel 上传方法（最简单）
1. 打开 https://vercel.com
2. 注册或登录账号
3. 点击 Add New Project
4. 选择上传项目文件夹，或先上传到 GitHub 再导入
5. 点击 Deploy
6. Vercel 会生成一个免费网址，比如：
   https://your-project.vercel.app

## 需要你替换的内容
在 index.html 里搜索并替换：
- Jinghao Packaging
- sales@jinghaopackaging.com
- +86-XXXXXXXXXXX
- Add Machine Photo Here

## 添加图片方法
1. 把机器图片放进网站文件夹，比如 machine.jpg
2. 在 index.html 中找到 Add Machine Photo Here 那一块
3. 替换成：
   <img src="machine.jpg" alt="Seed Packaging Machine" class="main-photo">

然后在 style.css 最后加：
.main-photo { width: 100%; height: 100%; object-fit: cover; border-radius: 24px; }
