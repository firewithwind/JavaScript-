## 浏览器和屏幕

### Navigator对象

#### - 属性

- appName

- appCodeName

	```
	返回浏览器代码名
	```
- appVersion
- userAgent
- platform
- online

	```
	表示浏览器当前是否连接网络
	```
- geolocation

	```
	用于确定用户地理位置
	```
- appMinorVersion

	```
	返回浏览器的次级版本
	```
- doNotTrack
- language

	```
	返回浏览器的语言
	```
- languages

	```
	返回一个数组
	```
- hardwareConcurrency
- 其他
	
#### - 方法

- javaEnabled()

	```
	当浏览器支持java小程序时返回true
	```
- cookieEnable()

	```
	如果浏览器可以保存永久cookie，返回true
	```
	
### Screen对象

#### - 属性

- availHeight

	```
	返回显示屏幕的高度 (除 Windows 任务栏之外)
	```
- availWidth

	```
	返回显示屏幕的宽度 (除 Windows 任务栏之外)
	```
- bufferDepth

	```
	设置或返回调色板的比特深度
	```
- colorDepth

	```
	返回目标设备或缓冲器上的调色板的比特深度
	```
- deviceXDPI

	```
	返回显示屏幕的每英寸水平点数
	```
- deviceYDPI

	```
	返回显示屏幕的每英寸垂直点数
	```
- fontSmoothingEnabled

	```
	返回用户是否在显示控制面板中启用了字体平滑
	```
- height

	```
	返回显示屏幕的高度
	```
- logicalXDPI

	```
	返回显示屏幕每英寸的水平方向的常规点数
	```
- logicalYDPI

	```
	返回显示屏幕每英寸的垂直方向的常规点数
	```
- pixelDepth

	```
	返回显示屏幕的颜色分辨率（比特每像素）
	```
- updateInterval

	```
	设置或返回屏幕的刷新率
	```
- width