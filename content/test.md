> Pug（原名Jade）是一种基于模板引擎的高性能、简洁易读的HTML模板语言。

# 序
大家在开发中肯定会遇到这种代码。让我们来讨论一下，阅读这样的代码时，你会有什么第一印象？它和普通的HTML5有何不同之处？
```css

html(lang="en")
  head
  body
    h1 Pug - node template engine
    #container.col
      p You are amazing

```
```html
<html lang="en">
  <head>
  </head>
  <body>
    <h1>Pug - node template engine</h1>
    <div id="container" class="col">
      <p>You are amazing</p>
    </div>
  </body>
</html>
```
# 特性