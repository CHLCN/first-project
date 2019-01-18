# HTML学习笔记（1.17）

- ## 简单结构

  ```html
  <html>
      <body>
          The HTML content goes here.
      </body>
  </html>
  ```

  - 标题

  标题上下分别需要<head>和</head>

  ```html
  <html>
      <title>This is title!</title>
  </html>
  ```

  

  head与body为并列结构

  ```html
  <html>
      <head>
          <title>I am a title!</title>
      </head>
  
      <body>
          Some content.
      </body>
  </html>
  ```

  - 插入图片

  `<img src="图片地址">`

  效果：

  <img src="http://www.goupu.com.cn/file/upload/201808/26/131106361.jpg">

  -  列表
    - 有序列表

    ```html
    <ol>
        <li>This</li>
        <li>Is an</li>
        <li>Ordered list</li>
    </ol>
    ```

    - 无序列表

    ```html
    <ul>
        <li>This</li>
        <li>Is an</li>
        <li>Unordered list</li>
    </ul>
    ```

    > 有序列表使用<ol>展开列表，而无序列表使用<ul> 列表中每条均需用<li>和</li>开始和结束。

  - 插入超链接

  使用<a>来展开超链接，其中包括herf（超链接引用），超链接地址与描述内容。使用</a>结束。

  e.g

  `<a href="http://github.com">This is a link to Github!</a>`

  - 引入样式表

  将网页所在CSS文件夹下的 某css文件中的 样式定义 引用到该网页中

  `<link rel="stylesheet" href="style.css">`

  > 注意：需在<head>与</head>之间添加此句