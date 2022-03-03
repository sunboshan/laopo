# 5. javascript - 让网页活起来(WIP)

终于，我们学到了javascript。从这里我们才是开始真正的学习编程。之前的html和css都不是编程语言，而javascript才是一个编程语言。很多初学者会在简历里面写会的编程语言有html，这个是不对的。怎么区别一个语言是否是编程语言呢？很简单，你打1+1看它能否返回2。能返回的就是编程语言。

编程语言辣么多，你肯定听过C,C++,Java,Python等等，为啥要学这个javascript呢？这玩意和Java有关吗？javascript的黑历史我这就不在说了。总之，目前的情况是，我们要做的是网页，看网页就得要用浏览器，而javascript是目前唯一可以在浏览器里面运行的语言。所以就不得不学javascript了。

那么，javascript怎么玩呢？很简单，用你现在正在用的浏览器(chrome)，F12打开控制台。点击`Console`，打`1+1`然后回车，它会给你返回2。恭喜你，成功写了一个javascript语言！这个就是javascript的控制台，可以在这里尝试一下这个语言。

F12这个控制台更多是平时调试用的，我们学习js还是写到文件里面。我们还是打开一个html文件。

```html title="hello.html" line={3-5}
<html>
  <head>
    <script>
      console.log("hello world")   <-- 这里面放的内容就是javascript
    </script>
  </head>
  <body>
  </body>
</html>
```