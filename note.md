
Jekyll的运行流程：
a. 配置：Jekyll首先读取_config.yml文件中的配置信息。
b. 读取文件：Jekyll会读取项目目录中的所有文件，特别是Markdown和HTML文件。
c. 处理特殊文件夹：Jekyll会特别处理以下文件夹：
_layouts：存放页面模板
_includes：存放可重用的页面片段
_posts：存放博客文章
_data：存放网站数据文件
_sass：存放Sass样式文件
d. 转换：Jekyll将Markdown文件转换为HTML，处理Liquid模板语言。
e. 生成静态文件：Jekyll将处理后的文件生成到_site文件夹中。
f. 提供服务：如果运行jekyll serve，Jekyll会启动一个本地服务器，让你可以预览网站。