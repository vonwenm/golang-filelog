# golang-filelog
这是一个用来替代log/syslog用的log库

我们有时候出于某种目地可能需要把程序在syslog和文件log中间切换

这个库提供了与syslog完全一样的API，并定义了接口。

方便程序中直接在syslog与文件log中间切换
