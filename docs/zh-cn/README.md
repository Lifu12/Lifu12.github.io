# 搭建自己的博客

> 使用https://docsify.js.org/

## 入门

### 快速开始

建议`docsify-cli`全局安装，有助于在本地初始化和预览网站。

```bash
npm i docsify-cli -g
```

### [初始化](https://docsify.js.org/#/quickstart?id=initialize)

如果要在`./docs`子目录中编写文档，可以使用该`init`命令。

```bash
docsify init ./docs
```

### [写作内容](https://docsify.js.org/#/quickstart?id=writing-content)

在之后`init`完成后，你可以看到在文件列表`./docs`子目录。

- `index.html` 作为入口文件
- `README.md` 作为主页
- `.nojekyll` 防止 GitHub Pages 忽略以下划线开头的文件

您可以轻松地更新文档中的内容`./docs/README.md`，当然您也可以添加[更多页面](https://docsify.js.org/#/more-pages)。

### [预览您的网站](https://docsify.js.org/#/quickstart?id=preview-your-site)

运行本地服务器`docsify serve`。您可以在浏览器中预览您的网站`http://localhost:3000`。

```bash
docsify serve docs
```

## 编写更多的页面

如果你需要更多的页面，你可以简单地在你的 docsify 目录中创建更多的 Markdown 文件。如果您创建一个名为 的文件`guide.md`，则可以通过`/#/guide`

例如，目录结构如下：

```text
.
└── docs
    ├── README.md
    ├── guide.md
    └── zh-cn
        ├── README.md
        └── guide.md 
```

匹配路线

```text
docs/README.md        => http://domain.com
docs/guide.md         => http://domain.com/#/guide
docs/zh-cn/README.md  => http://domain.com/#/zh-cn/
docs/zh-cn/guide.md   => http://domain.com/#/zh-cn/guide
```



```java
public void test () {
    
}
```

