# 京东自动任务常见问题

待完善...
欢迎一起完善文档...

### 如何获取Cookie
- [电脑浏览器获取京东cookie教程](https://github.com/leecobaby/shortcuts/blob/master/DOC/GetJdCookie1.md)
- [手机stream app获取京东cookie教程](https://github.com/leecobaby/shortcuts/blob/master/DOC/GetJdCookie2.md)
> 上面显示不了图片的，可以查看下面链接
> - [电脑浏览器获取京东cookie教程](https://gitee.com/leecobaby/shortcuts/blob/master/DOC/GetJdCookie1.md)
> - [手机stream app获取京东cookie教程](https://gitee.com/leecobaby/shortcuts/blob/master/DOC/GetJdCookie2.md)

### 为什么会弹出权限通知
- 这是快捷指令的权限规则，第一次使用需要确认快捷指令整个流程内的权限确认，如果不确认可能无法正常使用
- 每次更新或安装都需要重新再给一遍权限
- 部分快捷指令里面包含很多访问链接，需要为这些链接都给一遍权限，所以考虑到方便使用作者不会频繁更新

### 为什么只做了几个任务
- 初代版本功能不会太健全，会尽力更新

### 为什么有些任务没只做了几个
- 采用了云端数据来做任务，云端数据具有滞后性、机械性，推荐当看到云端数据库版本发生变更是，在运行一遍指令来补全任务
- 没人的任务数据可能不一样的，但云端任务数据照顾不了那么多人，火爆异常，不用太刻意理会
- 随着版本的迭代此问题将会得到解决

### 为什么获取不到词典建"data"的值
- 通常这个原因是因为Cookie设置错误，输入了无效的Cookie
- 请认真按教程引导来获取Cookie，获取到的Cookie确保开头不带`Cookie:`，以及其他无关内容，只保留本体内容
- 如果发生此错误，请再次设置Cookie，它将覆盖原来的Cookie

###  登录授权显示无法运行run inline script
- 部分第一次下载 Scriptable 的同学，都没打开 app 给访问网路访问通知的权限，就直接运行快将指令的确会出错，快捷指令里会调用这个APP的指令组件需要一些权限才能正常使用

### 授权哪里显示弹出错误
- 第一次下载 Scriptable 的同学，需要重装快捷指令，快捷指令才能正确识别第三方组件
