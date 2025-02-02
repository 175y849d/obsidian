[[2025-02-01]]

##### 我在做我的todo-list项目时,deepseek给我了个简略的index.html页面代码,如下:


```
	    <!DOCTYPE html>  
		<html>  
		<head>  
		  <meta charset="UTF-8">  
		  <title>Todo List</title>  
		  <link rel="stylesheet" href="style.css">  
		</head>  
		<body>  
		  <div class="container">  
		    <h1>Todo List</h1>  
		    <div class="input-section">  
		        <input type="text" id="taskInput" placeholder="输入新任务...">  
		        <button id="addBtn">添加</button>  
		    </div>  
		    <ul id="taskList"></ul>  
		    <div class="stats">总任务数: <span id="total">0</span></div>  
		  </div>  
		  <script src="app.js"></script>  
		</body>  
		</html>
```

### 页面图片如下:
![[Pasted image 20250201153241.png]]


### 我的第一反应是通过获取用户输入到输入框的数据,将其输出到该页面上。
#### 这样做首先得要有个添加按钮,用于交互,前面AI已经给出按钮的代码了,按照逻辑应该是用户按这个按钮,那么在网页上就添加一行数据
~~~
