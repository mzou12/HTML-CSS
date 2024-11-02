### HTML 标签

双标签

        <p> paragraphs</p>
        <h1> Heading </h1>
        <a href="#"> 超链接标签 </a>
        <script src="script.js"></script> 脚本


单标签

        <input type="text"> 输入
        <meta charset="UTF-8"> 元信息，此处为字体
        <br> 换行
        <hr> 分割线
        <link rel="stylesheet" href="styles.css"> 引入外部资源，此处引入css页面样式文件

单标签用在没有内容的元素，双标签用在有内容的元素

<hr>

### 文件结构

    <!DOCTYPE html>
    <html> <!-- 文件起始点-->
        <head> <!-- 不显示在页面主体，显示页面的元信息，样式和脚本等-->
            <meta charset="utf-8">
            <title>教程</title>


        </head>
        <body> <!-- 放置页面的内容-->
        
            <h1>我的第一个标题</h1>
            
            <p>我的第一个段落。</p>
        
        </body>
    </html> <!-- 文档结束点>