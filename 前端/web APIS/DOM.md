//**处理html的接口**

 ### 1. **DOM树**
就是！加enter，出来那些，html，head，title

* 文档：一个页面就一个document
* 元素：标签element
* 节点：node 所有内容都是，注释，标签，文本

### 1. *获取元素*
getElementById（）//里面id,，返回的是元素对象
```html
<div id="time">2022-1-15</div>
<scrict>
var timer = document.getElementById('time')
console.log(timer);
console.dir(timer)//注意，没用过这个dir,会得到一堆属性方法。dir是目录的意思

//根据标签名获取
getElementsByTagName()//返回带有指定标签名对象的集合
</scrict>

```


