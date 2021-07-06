<blockquote><p align="center"><b>
  Synced with <a href="https://github.com/crystal-lang/crystal-book">English Repo</a> on July 6, 2021.
</b></p></blockquote>
 
<br>

<h1 align="center"><img src="https://github.com/crystal-zh-cn/crystal-book/blob/master/resources/logo-no-edge.png?raw=true" height="24"/> Crystal 编程语言</h1>

这是一份适用于 Crystal 编程语言的官方参考文档。

Crystal 编程语言被我们赋予了以下使命：
- 拥有和 Ruby 相似的语法（但是并不以兼容 Ruby 为目的）
- 拥有静态类型检查能力，但是您无需手动声明变量和参数的数据类型
- 能够在 Crystal 中通过创建绑定（Bindings）来调用 C 语言代码
- 拥有编译时的代码评估和代码生成能力，以减少不必要的重复代码
- 能编译成为高效的原生代码（Native Code）

**此外，如需查看 Crystal 官方标准库文档请前往 [API Docs (English)](https://crystal-lang.org/api)**

## 为该文档做贡献

你想和我们一起构建这份文档吗？

如果你发现了任何的问题、错误、过时内容、需要补充的内容，都可以通过提交PR的方式进行添加或删改！我们非常欢迎！

同时也非常感谢您为 Crystal 中文社区做出的一份贡献！

> 因英文版出现错误导致的中文版错误请前往 **[English Repo](https://github.com/crystal-lang/crystal-book)** 并提交英文PR。

### 如何在本地搭建并测试

**获取仓库：**

```console
$ git clone https://github.com/crystal-zh-cn/crystal-book
$ cd crystal-book
```

**本地预览：**

```console
$ make serve
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  Documentation built in 3.02 seconds
INFO    -  Serving on http://127.0.0.1:8000
...
```

然后您就可以通过 http://127.0.0.1:8000 进行本地预览访问啦！

**本地构建：**

构建文档网页至 `site` 文件夹。

```console
$ make build
```

请注意：通过本地打开网页文件的方式可能无法保证全部功能正常工作。

### 添加一个页面

如需添加页面，请在对应位置创建一个 Markdown 文档，然后将它的路径添加至 `SUMMARY.md` 文件以加入导航菜单。
