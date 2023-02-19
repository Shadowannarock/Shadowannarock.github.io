# London_Web
This Website was initaled 5 years ago,When studying in college.:(<br>

#关于大小写和空格的提示
你会注意到，在这篇文章中，我们要求你完全用小写字母命名文件夹和文件，没有空格。这是因为：

1.许多计算机，特别是网络服务器，是区分大小写的。因此，假如你把一张图片放在你的网站上 test-site/MyImage.jpg，然后在一个不同的文件中，你试图以 test-site/myimage.jpg 来调用该图片，它可能无法工作。
2.浏览器、网络服务器和编程语言对空格的处理并不一致。例如，如果你在文件名中使用空格，一些系统可能将其视为两个文件名。一些服务器会用“%20”（URL 中空格的字符代码）替换文件名中的区域，导致所有链接被破坏。最好用连字符而不是下划线来分隔单词。对比 my-file.html 与 my_file.html。

简言之，文件名中应使用连字符。谷歌搜索引擎把连字符当作单词的分隔符，但不会识别下划线。基于此，最好在一开始就养成习惯，文件夹和文件名使用小写，用短横线来分隔。这可以避免许多问题。

//From :https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/Dealing_with_files
