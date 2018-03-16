<p align="right"><a title="New «NexT» 6.0.0 version [Reloaded]" href="https://github.com/theme-next/hexo-theme-next">NexT v6.0.0 here :triangular_flag_on_post:</a></p>

<h1 align="center">NexT</h1>

<p align="center">NexT 是一个高质量并且优雅的<a href="http://hexo.io">Hexo</a> 主题。这是精心制作做出来的 hexo 主题。</p>


## 实时预览 Live Preview


* :heart_decoration: Muse 方案: [LEAFERx](https://leaferx.online) | [XiaMo](https://notes.wanghao.work) | [OAwan](https://oawan.me)
* :six_pointed_star: Mist 方案: [Jeff](https://blog.zzbd.org) | [uchuhimo](http://uchuhimo.me) | [xirong](http://www.ixirong.com)
* :pisces: Pisces 方案: [Vi](http://notes.iissnan.com) | [Acris](https://acris.me) | [Rainy](https://rainylog.com)
* :gemini: Gemini 方案: [Ivan.Nginx](https://almostover.ru) | [Alynx](http://sh.alynx.xyz) | [Raincal](https://raincal.top)


## 安装 Installation

**1.** 在终端切换到**hexo 根**目录. 在hexo目录下一定有 `node_modules`, `source`, `themes` 和其他文件夹:
   ```sh
   $ cd hexo
   $ ls
   _config.yml  node_modules  package.json  public  scaffolds  source  themes
   ```

**2.** 从 github 上获取主题:


### 克隆仓库

   ```sh
   $ git clone git@github.com/lk361115629/hexo-theme-next themes/next
   ```

**3.** 在 **hexo 根目录下** 的配置文件`_config.yml`里设置主题:

    theme: next

## 特色 Features

### 支持多国语言, 包括:
:cn: 简体中文 & 繁体中文<br>
:us: 英语<br>
:ru: 俄语<br>
:fr: 法语<br>
:de: 德语<br>
:jp: 日语<br>
:indonesia: 印度尼西亚语<br>
:portugal: 葡萄牙语 (巴西)<br>
:kr: 朝鲜语<br>
:it: 意大利语<br>
:netherlands: 荷兰语

默认语言是英语。

```yml
language: en
# language: zh-Hans
# language: zh-hk
# language: zh-tw
# language: ru
# language: fr-FR
# language: de
# language: ja
# language: id
# language: pt
# language: pt-BR
# language: ko
# language: it
# language: nl-NL
```

在站点配置文件`_config.yml`中可以将语言切换成中文

```yml
language: zh-Hans
```

### 评论支持 Comment support

NexT 已经原生支持 `多说` and `Disqus` 评论系统。

添加以下代码到你的主题配置文件 `_config.yml`:

```yml
duoshuo:
  enable: true
  shortname: your-duoshuo-shortname
```

或者

```yml
disqus_shortname: your-disqus-shortname
```

### 标签页 Tags page

> 添加一个标签页面，里面包含您网站中的所有标签。

- 创建一个名为 `tags` 页面

        hexo new page "tags"

- 编辑标签页, 设置页面类型为`tags`.

        title: All tags
        date: 2014-12-22 12:39:04
        type: "tags"

- 添加 `tags` 到主题配置文件 `_config.yml` 里:

        menu:
          home: /
          archives: /archives
          tags: /tags

### 分类页 Categories page

> 添加一个分类页面，里面包含您网站中的所有分类。

- 创建一个名为 `categories` 页面

        hexo new page "categories"

- 编辑分类页, 设置页面类型为 `categories`.

        title: All categories
        date: 2014-12-22 12:39:04
        type: "categories"

- 添加 `categories` 到主题配置文件 `_config.yml` 里:

        menu:
          home: /
          archives: /archives
          categories: /categories

### 社交媒体 Social Media

NexT 可以自动添加链接到您的社交媒体帐户里:

```yml
social:
  GitHub: your-github-url
  Twitter: your-twitter-url
  Weibo: your-weibo-url
  DouBan: your-douban-url
  ZhiHu: your-zhihu-url
```
