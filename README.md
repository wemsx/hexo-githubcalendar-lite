# hexo-github-calendar-lite(修改版)

### 原教程：
链接：https://zfe.space/post/hexo-githubcalendar.html

### 一键部署：

```
npm i hexo-githubcalendar-lite --save
```

### 网站根目录_config配置项(不是主题的)：
例如volantis配置为
```yml
# Ice Kano Plus_in
# Hexo Github Canlendar
# Author: Ice Kano
# Modify: Lete乐特, wemsx

# Modify Note by wemsx: 已由Serverless部署改为直接使用JS请求数据

# Volantis
githubcalendar:
  enable: true
  enable_page: /
  user: wemsx
  layout:
    type: class
    name: l_main
    index: 0
  githubcalendar_html: '<div class="post post-v3 white-box reveal shadow" style="width:100%;height:auto;padding:10px;"><div id="github_loading" style="width:10%;height:100%;margin:0 auto;display: block"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"  viewBox="0 0 50 50" style="enable-background:new 0 0 50 50" xml:space="preserve"><path fill="#d0d0d0" d="M25.251,6.461c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615V6.461z" transform="rotate(275.098 25 25)"><animateTransform attributeType="xml" attributeName="transform" type="rotate" from="0 25 25" to="360 25 25" dur="0.6s" repeatCount="indefinite"></animateTransform></path></svg></div><div id="github_container"></div></div>'
  pc_minheight: 280px
  mobile_minheight: 0px
  color: "['#ebedf0', '#fdcdec', '#fc9bd9', '#fa6ac5', '#f838b2', '#f5089f', '#c4067e', '#92055e', '#540336', '#48022f', '#30021f']"
  calendar_js: https://unpkg.com/hexo-github-calendar-lite@latest/hexo_githubcalendar.js
  plus_style: ""
```
更多主题配置请参考issuse页：https://github.com/Zfour/hexo-github-calendar/issues

## ！我更改了部分程序，现在已经改为直接请求，不再需要部署Serverless函数。


### 执行：

```
hexo clean & hexo g & hexo s
```

### 效果：

![image](https://user-images.githubusercontent.com/19563906/110137138-76ee4980-7e0b-11eb-881c-72b86271cd4f.png)





