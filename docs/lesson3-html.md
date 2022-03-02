# 3. html - 网页的骨和肉

前面说过，html就是网页的骨和肉。

```html title="hello.html"
<html>
  <body>         <-- 骨
    hello world  <-- 肉
  </body>
</html>
```

html是一个标记语言，通过各种各样的标签(_tag_)来把网页画出来。

标签就是由尖括号组成的，通常是成对出现。标签之间可以放入内容。一个网页就是由很多的标签组成，各个标签就成了网页的**骨架**。

光有标签不行，里面还得有内容。这个内容即组成了网页的**血肉**。

html最新的版本是5。html5里面的标签有几十种，不需要记住，会一些常用的即可。以后看到不认识的标签上网查一下是干嘛的就行了，就像查字典一样。

下面列出了一些常用的html标签，可以自己改改试试效果哟~

```jsx live
<html>
  <body>
    <h1>hello</h1>
    <p>这是一个段落标签</p>
    <div>
       <p>想把好几个标签放在一起，可以用这个div标签</p>
       <a href="https://google.com">Google</a>
    </div>
  </body>
</html>
```

### 作业

用html写一个电影介绍页面。

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="homework" label="作业" default>

```html title="movie.html"
<html>
  <body>
    作业写在这里
  </body>
</html>
```

  </TabItem>
  <TabItem value="answer" label="参考答案">

```html title="movie.html" live
<html>
  <body>
    <h1>Cracks (2009)</h1>
    <p>Drama Thriller</p>
    <h2>Storyline</h2>
    <p>At an elite girls boarding school, the award winning diving team is considered the premier group of girls in the school. When a new girl from Spain, Fiamma, comes to the school and joins the team, the rest of the squad is jealous of her relationship with the coach and force her off the team and out of the school by bullying her. When the girl is forced to rejoin the group, they decide to let her into their social circle and begin to be as fascinated with her as their coach is. But things take a turn when the coach lets her fascination lead her too far...</p>
    <a href="https://www.imdb.com/title/tt1183665">IMDB: Cracks(2009)</a>
  </body>
</html>
```

  </TabItem>
</Tabs>

### 参考资料
- [html5 tags](https://www.w3schools.com/TAGs/)