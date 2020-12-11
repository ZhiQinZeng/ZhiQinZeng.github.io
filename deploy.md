git add . 
git commit -m "博客"
git pull  https://github.com/ZhiQinZeng/ZhiQinZeng.github.io main --allow-unrelated-histories
git push  https://github.com/ZhiQinZeng/ZhiQinZeng.github.io main

#开启本地调试
hexo s
## 部署github
hexo clean
hexo d 
## 打开编辑器页面
hexo server -d 
http://localhost:4000/admin/

## 参考博客
https://blog.cofess.com/2017/11/01/hexo-blog-theme-pure-usage-description.html

## 自己博客地址
https://zhiqinzeng.github.io/