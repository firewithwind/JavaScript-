## Window

**JavaScript全局对象**

	可以通过window属性来查看Window对象本身,Window作为全局对象,是函数调用默认的this值
	Window对象的方法可以直接调用
	
### 属性

- window

	```
	对自身的引用
	```
- self

	```
	等同于window
	```
- document

	```
	对Document对象的只读引用
	```
	[查看Document对象]()
- history

	```
	对History对象的只读引用
	```
	[查看History对象]()
- location

	```
	对Location对象的只读引用
	```
	[查看Location对象]()
- navigator

	```
	对Navigator对象的只读引用
	```
	[查看Navigator对象]()
- screen

	```
	对Screen对象的只读引用
	```
	[查看Screen对象]()
- closed

	```
	返回值：Boolean
	浏览器是否被关闭
	```
- defaultstatus

	```
	设置或返回窗口状态栏中的默认文本
	```
- length

	```
	设置或返回窗口中的框架数量
	```
- name

	```
	设置或返回窗口的名称
	```
- opener

	```
	返回对创建此窗口的窗口的引用
	```
- parent

	```
	返回父窗口
	```
- top

	```
	返回最顶层的先辈窗口
	```
- status

	```
	设置窗口状态栏的文本
	```
- pageXOffset

	```
	设置或返回当前页面相对于窗口显示区左上角的 X 位置
	```
- pageYOffset

	```
	设置或返回当前页面相对于窗口显示区左上角的 Y 位置
	```
- innerHeight

	```
	返回窗口的文档显示区的高度
	```
- innerWidth

	```
	返回窗口的文档显示区的高度
	```
- outerHeight

	```
	返回窗口的外部高度
	```
- outerWidth

	```
	返回窗口的外部高度
	```
- screenLeft
- screenRight
- screenX
- screenY

	```
	这四个属性不同的浏览器的兼容性不同
	```
**补充**

- caches
	
### 方法

- alert()
- confirm()
- prompt()
- print()
- setTimeout()
- clearTimeout()
- setInterval()
- clearInterval()
- open()
- close()
- blur()
- focus()
- moveBy()
- moveTo()
- createPopup()
- resizeBy()
- resizeTo()
- scrollBy()
- scrollTo()

**补充**

- atob()

	```
	解码一个已经被base-64编码过的数据
	```
- btoa()

	```
	ascii字符串或二进制数据转换成一个base64编码过的字符串,该方法不能直接作用于Unicode字符串
	```
- requestAnimationFrame()

	```
	方法告诉浏览器您希望执行动画并请求浏览器调用指定的函数在下一次重绘之前更新动画。
	该方法使用一个回调函数作为参数，这个回调函数会在浏览器重绘之前调用。
	```
- cancelAnimationFrame（）

	```
	取消一个先前通过调用window.requestAnimationFrame()方法添加到计划中的动画帧请求.
	```





