## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/BadyLing/qiniuQ.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/BadyLing/qiniuQ.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### 记录七牛上传---小问题

七牛上传分为两种：一种是SDK上传，一种是上传base64编码图片

SDK上传https://developer.qiniu.com/kodo/sdk/1283/javascript
base64上传https://developer.qiniu.com/kodo/kb/1326/how-to-upload-photos-to-seven-niuyun-base64-code
其中base64上传的地址需要https://upload-z1.qiniup.com/putb64/-1加上后缀（putb64）和（-1）→【文件大小】
SDK上传直接https://upload-z1.qiniup.com即可，这个地址指的是华北地区上传
