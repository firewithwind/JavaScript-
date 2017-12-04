## String

### 创建

	new String(s)
	String(s)
	
### 属性

	constructor  //构造函数的引用
	length       //字符串长度
	prototype    //原型对象
	
### 方法

**样式相关**

- [anchor(html)](http://www.w3school.com.cn/jsref/jsref_anchor.asp)
	
	```
	创建html锚
	```
- big()

	```
	用大号字体显示
	```
- blink()

	```
	显示闪动字符串
	```
- blod()

	```
	使用粗体显示字符串
	```
- fixed()

	```
	以打字机文本显示字符串
	```
- fontcolor()

	```
	使用指定的颜色来显示字符串
	```
- fontsize()

	```
	使用指定的尺寸来显示字符串
	```
- italics()

	```
	使用斜体显示字符串
	```
- link()

	```
	将字符串显示为链接
	```	
- sub()

	```
	将字符串显示为下标	
	```
- sup()

	```
	将字符串显示为上标
	```
- small()

	```
	使用小字号来显示字符串
	```
- strike()

	```
	使用删除线来显示字符串
	```
	
**索引相关**
	
- charAt(index)

	```
	返回指定位置的字符
	```
- charCodeAt(index)

	```
	返回指定位置的字符的Unicode编码
	```
- indexOf()

	```
	检索字符串，返回找的的起始位置，没有找到返回-1
	```
- lastIndexOf()

	```
	从末尾开始检索字符串，返回找到的起始位置，没有找到返回-1
	```
- [slice()](http://www.w3school.com.cn/jsref/jsref_slice_string.asp)

	```
	提取字符串的片断，并在新的字符串中返回被提取的部分
	```

- [substr()](http://www.w3school.com.cn/jsref/jsref_substr.asp)【不建议】

	```
	从起始索引号提取字符串中指定数目的字符
	```
- [substring()](http://www.w3school.com.cn/jsref/jsref_substring.asp)

	```
	提取字符串中两个指定的索引号之间的字符
	```
- match()

	```
	接收一个正则表达式，对字符串进行判断，返回一个数组
	```
	具体用法见[正则表达式](https://github.com/firewithwind/JavaScript-/blob/master/%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F.md)
- replace()

	```
	执行替换操作
	```
	具体用法见[正则表达式](https://github.com/firewithwind/JavaScript-/blob/master/%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F.md)
- search()

	```
	执行查询操作
	```
	具体用法见[正则表达式](https://github.com/firewithwind/JavaScript-/blob/master/%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F.md)
	
**操作相关**	
	
- concat(str)

	```
	连接字符串
	```
- localeCompare()

	```
	用本地方法比较两个字符串
	```
- split()

	```
	将字符串按照参数划分为数组
	```
- toLowerCase()

	```
	将字符串转换为小写形式
	```
- toLocaleLowerCase()

	```
	将字符串用本地方法转换为小写形式
	```
- toUpperCase()

	```
	将字符串转换为大写形式
	```
- toLocaleUpperCase()

	```
	将字符串用本地方法转换为大写形式
	```
- toSource()

	```
	代表对象的源代码
	```
- toString()

	```
	返回字符串
	```
- valueOf()

	```
	返回该对象的原始值
	```