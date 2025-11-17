# MyBlog

## Hexo环境配置
hexo 是一个快速、简洁，而且功能强大的静态博客框架。我们可以使用 Markdown 编写博客文章，然后 hexo 帮我们把 Markdown 文件渲染成静态 HTML 页面。因此 hexo 非常适合用来搭建技术类博客，以及项目文档和个人网站。  
node -v  
npm -v  
npm config set registry https://registry.npmmirror.com  
npm install -g hexo-cli  
hexo init MyBlog 初始化 MyBlog 文件夹（自定义）  
### 新建文章
新建博文命令：hexo new 这是一篇新的博文  
新建标签页命令：hexo new page 新建的标签页  
 
### 命令
hexo clean && hexo generate  
//hexo clean && hexo generate && hexo deploy  
--hexo clean：清除缓存，简写 hexo -c  
--hexo generate：生成渲染，简写 hexo -g  
--hexo deploy：部署到 GitHub Pages，简写 hexo -d  
--hexo server：启动本地预览，简写 hexo -s  

## 打开后
//user.name=yangshiwang  
//user.email=2479770116@qq.com  
//git config -l
//user.name=abandon1234
//user.email=99237906+abandon1234@users.noreply.github.com
//git config --global user.name "你的用户名"
//git config --global user.email "你的邮箱"
//ssh-keygen -t rsa -C
// /home/codespace/workspaces/MyBlogGenerate/.ssh/id_rsa
npm install -g hexo-cli && hexo -v