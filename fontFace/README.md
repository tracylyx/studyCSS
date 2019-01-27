#### @font-face
可用来自定义字体，将自己自定义的字体嵌入到Web页面中，用来修饰文本。
自定义字体有收费的和开源的。使用的时候要注意版权问题哦。

#### 语法规则
```css
@font-face {
	font-family: <font name>;
	src: <url(字体被放置的路径，可以是相对的也可以是绝对的) fotmat('truetype')>;
	font-weight: <weight>; 可选
	font-style: <style> 可选
}
```

#### 4总字体，EOT WOFF TTF SVG
1. truetype .ttf格式。是windows和iOS最常见的字体，是一种RAW格式。
2. opentype .otf格式。被认为是一种原始的字体格式，内置在truetype的基础之上。
3. web open font format .woff 格式。是web字体的最佳格式，它是一个开放的truetype／opentype的压缩版本。
4. embedded open type .eot格式。是IE专用字体
5. svg .svg格式。是基于SVG字体渲染的一种格式

在@font-face中至少要有.woff .eot这两种格式的字体，才能够满足更多的浏览器版本的支持。

#### 字体下载地址
http://www.googlefonts.cn/english