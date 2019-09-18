# 中文博客排版指南

## 标题

正确：（Markdown 语法）

```markdown
# 文章的标题

## 文章内容的大标题

### 文章内容的二级标题

#### 文章内容的三级标题
```

原则：

（1）文章内容的标题一般用 `##` 和 `###`。为保证层级的简单，请尽量避免出现 `####` 的标题。

（2）为保证标题的连贯性，`#` 的标题下不要直接出现 `###` 的标题。

## 图片


**1、图片大小**：

为方便网络传输，且保证清晰度，图片大小尽量控制在 **100 KB** 至 **500 KB** 之间。

如果图片过大，可以使用网址 <https://tinypng.com/> 进行压缩；如果图片不够清晰，请重新制图。

**2、图片格式**：

![](http://img.smyhvae.com/20190908_2238.png)

静态图片用 png、jpg格式；动态图用 gif 格式。gif 动图可以使用软件 [LICEcap](https://www.cockos.com/licecap/) 录制屏幕生成。

**3、图片文件名**：

图片的文件名使用**当前时间戳**，格式：`YYMMDD_HHMM`。格式举例：

```
20190902_1010.png

20180228_1505.jpg

20180616_1618.gif
```

**4、流程图制作工具**：

- 流程图、思维导图（在线）：<https://www.processon.com>

- 思维导图（在线）：<https://naotu.baidu.com>

- 思维导图（本地）：<https://www.xmind.cn>

- 列清单、思维导图（在线）：<https://mubu.com>


## 空格

### 中英文之间需要增加空格

正确：

```
任何可以使用 JavaScript 来编写的应用，最终都会由 JavaScript 编写。
```

错误：

```
任何可以使用JavaScript来编写的应用，最终都会由JavaScript编写。
```

### 中文和数字之间需要增加空格

正确：

```
一年有 12 个月。
```

错误：

```
一年有12个月。
```

### 数字和单位之间需要加空格

正确：

```
正确：一部容量为 16 GB 的智能手机
```

错误：

```
错误：一部容量为 16GB 的智能手机
```

### 完整的英文整句时标点与单词之间需要加空格

正确：

```
Stay hungry, stay foolish. That is Steve's famous quote.
```

错误：

```
Stay hungry,stay foolish.That is Steve's famous quote.
```

### 例外：度的标志、百分号不加空格

正确：

```
今天气温有 35° 的高温。

据统计，关注 GitHub 的读者中有 80% 是码农。
```

### 例外：全角标点与其他字符之间不加空格

正确：

```
全球最大的同性交友社区 GitHub，已被微软收购。
```

## 专有名词使用正确的大小写

正确：

```
想要学习 Web 前端，应该首先学习 HTML、CSS、JavaScript、jQuery、Ajax、Vue.js、React 等基础内容。

```

错误：

```
想要学习 web 前端，应该首先学习 html、css、Javascript、Jquery、ajax、vue.js、react 等基础内容。
```

正确：

```
GitHub、Android、iOS、iPhone 6s、iPhone SE、MacBook Pro
```

## 标点

### 关于全角和半角

简单来说，全角占两个字节，半角占一个字节。你可以理解成中文汉字和中文标点是全角，英文字母和英文标点是半角。体现在排版上的差异就是，全角字符屏幕打印宽度是两个，而半角字符屏幕打印宽度是一个，如中文逗号和英文逗号他们的显示分别是「，」和「,」。

更详细的介绍，可以查看维基百科的词条「[全角和半角](https://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)」

### 使用全角中文标点

中文排版中，所有的标点都应该使用全角中文标点。

示例：

```
大家好，我正在使用 GitHub。
```

### 遇到英文整句、特殊名词时使用半角标点

示例：

```
乔布斯说过：「Stay hungry, stay foolish.」

Facebook, Inc.
```

## 需要特别强调的词，建议用直角引号

示例：

```
互联网上充斥着大量的内容，「知识付费」成为下一个风口。我每天使用「得到」App，阅读一小时。
```

## 公众号 Markdown 编辑器推荐

- markdown在线转换工具：<http://blog.didispace.com/tools/online-markdown/>

- markdown在线转换工具2：<http://prod.zkqiang.cn/wxeditor/index.html>

可以针对外链，自动生成脚注。

- markdown在线转换工具3：<https://www.mdnice.com/>

可以针对外链，自动生成脚注。

- markdown在线转换工具4：<http://md.aclickall.com/>

**备注**：生成的脚注，效果如下：

![](http://img.smyhvae.com/20190915_1522.png)

## 参考链接

- [《中文技术文档的写作规范》](https://github.com/ruanyf/document-style-guide)

- [《写给大家看的中文排版指南》](https://zhuanlan.zhihu.com/p/20506092)

- [《中文文案排版指北》](https://github.com/sparanoid/chinese-copywriting-guidelines)

- [《中文排版指南》](https://github.com/ctf-wiki/ctf-wiki/wiki/%E4%B8%AD%E6%96%87%E6%8E%92%E7%89%88%E6%8C%87%E5%8D%97)

- [《README文档的规范写法》](https://github.com/AweiLoveAndroid/CommonDevKnowledge/blob/master/github_README/README%E6%96%87%E6%A1%A3%E7%9A%84%E8%A7%84%E8%8C%83%E5%86%99%E6%B3%95.md)

- [stormzhang | 每个人都需要的中文排版指南](https://mp.weixin.qq.com/s/k5DAmYtMrdSlK1jHsW-hrg)

- [《这是曹将公众号排版的所有秘密！》](https://mp.weixin.qq.com/s/DEUUcO4FhCiIYmh61wGXnw)


