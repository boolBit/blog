
之前在csdn，博客园上写博客，想着一方面总结学过的知识，另一方面可以提高自己的写作总结能力。很多知识点理解运用并不难，但是把逻辑清楚的讲解给别人听，还是需要一定的技巧和经验。[Hexo](https://hexo.io/zh-cn/)是一款开源的Node.js静态博客框架，支持markdown语法，主题很丰富。之前在阿里云上搭过，可惜写了几篇没有坚持下来。痛下心痛决定结合github pages重新开始...

----------


###  配置环境
 * git & github （将页面推送到github pages，公司，家中分布式开发。。）
 * nodejs (用于安装HEXO)
 * markdown编辑器 （使用[sublimes3](http://www.sublimetext.com/3) + [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing)+[OmniMarkupPreviewer](https://github.com/timonwong/OmniMarkupPreviewer)）
 
###  hexo安装

```
$ npm install -g hexo-cli
$ hexo init <folder>
$ cd <folder>
$ npm install
```
安装完成后目录如下：
> .
> ├── _config.yml
> ├── package.json
> ├── scaffolds
> ├── source
> |   ├── _drafts
> |   └── _posts
> └── themes



