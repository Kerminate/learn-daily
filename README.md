# learn-daily

## 坑点
- 使用vue的ui框架时，比如element,iview等，需要给组件绑定原生事件，可以在事件后加.native。例如element的input组件绑定键盘事件可以这么写@keyup.enter.native="add" 详见[vue的官方教程](https://cn.vuejs.org/v2/guide/components.html#%E7%BB%99%E7%BB%84%E4%BB%B6%E7%BB%91%E5%AE%9A%E5%8E%9F%E7%94%9F%E4%BA%8B%E4%BB%B6)

## 面试题
- 不用循环生成100长度都为1的数组,详见[es6](http://es6.ruanyifeng.com/#docs/array#Array-from)

```
Array.from({length: 1}, () => 1)
Array.from({length: 1}).map(() => 1)
```
