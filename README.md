
## debug
- 在浏览器内，F12打开控制台，切换到 Sources Tab内  
  Pause/Resume script execution：暂停/恢复脚本执行（程序执行到下一断点停止）。F8
  Step over next function call：执行到下一步的函数调用（跳到下一行）。F10  
  Step into next function call：进入当前函数。F11  
  Step out of current function：跳出当前执行函数。shift +F11  

- console.trace,打印函数调用顺序  

- console.table,以表格的形式打印数组  

- debug的时候,浏览器会一步一步的执行代码，我偏向于使用谷歌浏览器调试代码，如果想知道某个变量的值，可以选中这个变量，在谷歌浏览器上会提示这个变量的值  

- shift+F11快捷键，跳出方法，这个快捷键比较常用，比如某个函数我比较熟悉了，但是debug的时候，程序又执行进入了这个函数中，这时候就可以按 `shift + F11 `跳出这个函数  

### 参考文档
我学习debug,学习的是这两片文章
- [最全面的JavaScript调试技巧总结](http://www.codeceo.com/article/javascript-debug-skills.html)
- [JavaScript Debugging Tips and Tricks](http://www.zsoltnagy.eu/javascript-debugging-tips-and-tricks/)


## 源码阅读技巧
- 先从最早提交的代码看起，可以根据releases查看最早的提交版本
  - clone源码
  - 在github上查看最早的release，获取commitId（例如谷歌搜索 vue releases）
  - 复制一份源码
  - `git reset --hard commitId`,将源码reset至最早的relase
  - debug源码，不清楚的地方做demo
  - 源码写一遍

### 进度记录
预计需要2小时
- 18.1.5，整理js debug 1个小时
  1小时，完成