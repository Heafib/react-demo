# REACT－入门第一坑
-
#### 根据[@eisneim](https://github.com/eisneim)的教程学习react，视频虽然是老版本的，但是不碍事，新版本与原教程有以下几点不同：
1. 新版本react被拆分为react和react-dom,安装时只需多加几个字母	`npm install -g react react-dom`	

2. JSXTransformer.js和React-tools新版本不再可用！

3. 老版本写JSX的时候在script的标签里text的值为JSX	`<script type="text/jsx">...<／script>`  
   新版本script里type值改为babel	
   `<script type="text/babel">...<／script>` 

4. 渲染方法由`React.render()`改为`ReactDOM.render()`

5. 新版本`this.***['']`直接获取dom对象,不再使用	`this.***[''].getDOMNode`,
	`React.findDOMNode.	(this.***)`不可用！！

6. `React.unmountComponentAtNode()`不再可建议使用,使用	`ReactDOM.unmountComponentAtNode()`代替

7. `this.getDOMNode()`不再可用,使用`ReactDOM.findDOMNode(this)`代替获取真实DOM

8. minxin未来版本将会移除，不再推荐使用。

-
#### 说说自己的悲催经历吧，头一天还在努力的装开发环境，第二天准备好要开发了，然后。。。
 ![更新了。。。](http://7xsugp.com2.z0.glb.clouddn.com/0001.jpeg) 
#### 它尼玛竟然更新了，我的内心时崩溃的。。。	  好吧。只能继续更新了，第三天，总算开始学习了。。。
![第一次](http://7xsugp.com2.z0.glb.clouddn.com/0002.jpeg)
#### 第一次构建的项目，不许说我渣，，，暂时就这么多了，有个伟大的梦想，边学习边翻译官方文档，只是梦想。。。
