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

https://blog.51cto.com/u_16099206/12996169
## 以后打开后
npm install -g hexo-cli && hexo -v  
//hexo init MyBlog  
cd MyBlog  
npm i  
npm install hexo-deployer-git --save  
git clone -b main https://github.com/anzhiyu-c/hexo-theme-anzhiyu.git themes/anzhiyu  
npm install hexo-renderer-pug hexo-renderer-stylus --save  
npm install hexo-generator-topindex --save
npm install hexo-generator-search --save

ssh-keygen -t rsa -C "mykey"
将/home/codespace/.ssh/id_rsa.pub 点击 复制到 ssh
//ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDIcSCUcJx5PU7jF1PffbLhIz5jHDyizpbGZeE3LxtDeHnnvOHmYTKIShgYuIRnwSHexu3iErhaYhX8GRKJU1+OszSFONlc8oICJYQLpw4C8GfFgvbXqh0rRopkmHSJoWq0qQNZvTrI+2rROSee0ifTUWMrMo0sPh6cASPUCj+0+tUO9SpdgjgpLMT5BiGTN11+1bu11oZ4Hp7/I3hhAYXq2jxEfTFHEdKjk8wxo/ZjtBQXOHQX5PGHmgSFJR6d3UwudLHGfr69zIYLtMmoo5b0eEW8MHjLA6jlKfRWj5sWk16aeYSc+aILNMLXZ9X1I17DKR5CtTbQHcX3N3XsoTPjzT7QIMF3oHJHdT9VZgHTiUuPB5cNFph9ryB+B944W3plNlJwdkP3ey6Zkz4bzQJdtOLUV/ChpXV7U7Z8EwiAl4QMwXqYl4Q6wC9ugbCKlolWhyW10osI7qS+JKJLiu1UKJVBE2ohXCBfKc3HIRoT5q9v206evC42MmA2VqEX8Rk= mykey

//本地预览  
hexo cl; hexo s  

//推送更新上线  
hexo cl; hexo g; hexo d  
  