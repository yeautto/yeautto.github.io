# Jekyll Now

**Jekyll** 是一个静态站点生成器，非常适合GitHub托管的博客 ([Jekyll Repository](https://github.com/jekyll/jekyll))

**Jekyll Now** 通过消除大量的预先设置，使创建Jekyll博客变得更容易.

- 你不需要触摸命令行
- 您不需要安装/配置 ruby, rvm/rbenv, ruby-gems :relaxed:
- 您不需要安装运行时依赖项，如markdown processors, Pygments, 等
- 如果你在Windows上，这将使设置Jekyll更容易
- 这很容易尝试，如果您不喜欢，可以删除分叉存储库

## 快速入门

### 第1步 立即将Jekyll分给您的用户存储库

分叉此存储库，然后将存储库重命名为 yourgithubusername.github.io.

您的Jekyll博客通常会立即在 <https://yourgithubusername.github.io> (如果不是，您通常可以通过完成步骤2来强制它构建)

### 第2步 自定义并查看您的网站

通过编辑_config.yml文件 输入您的站点名称、描述、头像和许多其他选项。你也可以在这里轻松打开谷歌分析跟踪、Disqus评论和社交图标。

对 _config.yml (或存储库中的任何文件)进行更改将强制GitHub Pages使用jekyll重建您的网站. 几秒钟后，您的重建网站将在 <https://yourgithubusername.github.io> 
- 如果没有，按照GitHub的建议给它十分钟，它很快就会出现
> 有3种不同的方法可以更改你的博客的文件:

> 1. 在GitHub.com浏览器中编辑你的新 username.github.io 存储库中的_config.yml文件。
> 2. 在浏览器中使用第三方GitHub内容编辑器, 例如 [Prose by Development Seed](http://prose.io). 它经过了优化，可与Jekyll一起使用，使Markdown编辑、撰写草稿和上传图像变得非常简单。
> 3. 克隆您的存储库并在本地进行更新，然后将其推送到GitHub存储库。

### 第3步 发布您的第一篇博客文章

编辑`/_posts/2014-3-3-Hello-World.md`发布您的第一篇博客文章. 此 [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) 可能会派上用场.

> 您也可以在浏览器上的GitHub.com中添加其他帖子！ 只需点击`/_posts/`中的+图标即可创建新内容。 只需确保包括[front-matter](http://jekyllrb.com/docs/frontmatter/)块在每个新博客文章的顶部，并确保文章的文件名为以下格式：year-month-day-title.md

## 本地开发

1. 一举安装 Jekyll 和 plug-ins。 `gem install github-pages` 这反映了本地计算机上GitHub Pages使用的 plug-ins，包括 Jekyll、Sass等.
2. 克隆你的分叉 `git clone https://github.com/yourusername/yourusername.github.io.git`
3. 为网站服务并观察markup/sass更改 `jekyll serve`
4. 查看您的网站 http://127.0.0.1:4000/
5.提交任何更改并将所有内容推送到GitHub用户存储库的主分支. GitHub Pages 将重建并服务于您的网站.

## Moar!

我创建了一个更详细的演练, [**使用Jekyll和GitHub页面创建博客**](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/)在Smashing Magazine网站上. 如果你想了解更多关于杰基尔的详细情况和背景，请查看。 :metal:

它包括：

-设置Jekyll博客的更详细演练
-使用Jekyll时可能遇到的常见问题
-从Wordpress导入，使用您自己的域名，并在您喜爱的编辑器中写博客
-Jekyll中的主题，使用Liquid模板示例
-快速浏览Jekyll 2.0的新功能，包括Sass/Coffescript支持和收藏

## Jekyll Now 功能

✓ 使用命令行free _fork-first workflow, GitHub.com创建、自定义并发布到您的博客
✓ 全面响应和移动优化的基本主题 (**[Theme Demo](http://jekyllnow.com)**)  
✓ 使用Jekyll 2.0的Sass/Coffescript支持
✓ 免费托管GitHub Pages用户网站
✓ 降价博客
✓ 语法突出显示
✓ Disqus评论
✓ Google Analytics集成
✓ 页脚的SVG社交图标
✓ 3个http请求，包括您的头像 

✘ 无安装依赖项
✘ 无需建立本地开发
✘ 没有配置插件
✘ 不需要花时间在主题上
✘ 更多的时间来编写其他东西…等等✓!

## 其他可分叉主题

You can use the [Quick Start](https://github.com/barryclark/jekyll-now#quick-start) workflow with other themes that are set up to be forked too! Here are some of my favorites:

- [Hyde](https://github.com/poole/hyde) by MDO
- [Lanyon](https://github.com/poole/lanyon) by MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) by Tom Preston-Werner
- [Left](https://github.com/holman/left) by Zach Holman
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) by Michael Rose

## 贡献

- [Jekyll](https://github.com/jekyll/jekyll) - 感谢其创建者、贡献者和维护者.
- [SVG icons](https://github.com/neilorangepeel/Free-Social-Icons) - Thanks, Neil Orange Peel. They're beautiful.
- [Solarized Light Pygments](https://gist.github.com/edwardhotchkiss/2005058) - Thanks, Edward.
- [Joel Glovier](http://joelglovier.com/writing/) - Great Jekyll articles. I used Joel's feed.xml in this repository.
- [David Furnes](https://github.com/dfurnes), [Jon Uy](https://github.com/jonuy), [Luke Patton](https://github.com/lkpttn) - Thanks for the design/code reviews.
- [Bart Kiers](https://github.com/bkiers), [Florian Simon](https://github.com/vermluh), [Henry Stanley](https://github.com/henryaj), [Hun Jae Lee](https://github.com/hunjaelee), [Javier Cejudo](https://github.com/javiercejudo), [Peter Etelej](https://github.com/etelej), [Ben Abbott](https://github.com/jaminscript), [Ray Nicholus](https://github.com/rnicholus), [Erin Grand](https://github.com/eringrand), [Léo Colombaro](https://github.com/LeoColomb), [Dean Attali](https://github.com/daattali), [Clayton Errington](https://github.com/cjerrington), [Colton Fitzgerald](https://github.com/coltonfitzgerald), [Trace Mayer](https://github.com/sunnankar) - Thanks for your [fantastic contributions](https://github.com/barryclark/jekyll-now/commits/master) to the project!