## 简介
> 这是一份文档博客搭建工具指南，同时也是一个docsify博客网站最完整的架子，建议直接Clone到本地自己修改定制。

​		有人可能会问，网上这么多文档里面都已经很详细了，别人已经做出模板了，你为什么还要花时间再写一遍，而不直接使用别人的呢？每个人有每个人的风格，照着别人的配置改改，这也是可以用的。

​		但是，别人的不一定是最好的，重复造轮子就是为了更好用，取其精华，去其糟粕。这和学知识一样，别人脚踏实地踩着坑过来了，学到了，沉淀了，但是你看看别人的总结就会了吗？按照自己的方式，注入自己的思考，说不定你总结的会更好。

## 如何使用

- clone本仓库到本地[github地址](https://github.com/pycrab/docsifyGuide)，打开docs文件夹
  - 修改index.html中的仓库为你的github仓库
  - 修改/docs/cover.md封面
  - 修改/docs/index.md主页
  - 修改/docs/sidebar.md侧边栏导航
  - 修改/docs/navbar.md顶部菜单（如果需要）
  
- 全局安装docsify脚手架

  `npm i docsify-cli -g`，首先保证已安装npm包管理工具

- 本地预览
  - docs文件夹下执行`docsify serve docs`
  - 或者执行全局命令`npm run doc`，该配置在package.json的scripts中

