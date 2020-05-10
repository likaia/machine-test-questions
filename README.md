## JQuery结点操作
![41953714c2da32f9579d8e29bf4bb797.png](https://user-gold-cdn.xitu.io/2020/5/11/171ffab4f3812f10?w=906&h=292&f=png&s=35628)
如上图所示，获取图中的品牌、价格、尺寸、显卡的内容。

### 题目要求
* 使用JQuey实现
* 将获取到的数据放进一个JSON数组中
* JSON数据格式如下：
```javascript
[
    {
      "title":"品牌",
      "data":["惠普","联想","戴尔","...其他内容省略"]
    },
    {
      "title":"价格",
      "data":["....其他内容省略"]
    },
    {
      ...其他内容省略
    }
]
```

### 代码位置
用vscode打开当前目录下的**JQuery-project-test**项目，上述题目对应的代码位置在这个文件夹中，项目目录如下：

* **plugins/jquery/jquery.min.js** JQuery库
* **assets/js/index.js** 你需要在这个js文件里实现上述题目
* **assets/css/index.css** 效果图DOM结构对应的样式文件
* **index.html** 效果图DOM结构 

## JSON数据处理
![](https://user-gold-cdn.xitu.io/2020/5/11/171ffac09c87c102?w=1652&h=528&f=png&s=80416)
观察上图中两侧JSON数据的规律，用JavaScript将左侧的JSON数据转化为右侧的JSON数据。

### 题目要求
* 使用**JavaScript**实现
* 根据规律写一个函数，将图中**test.json**中的JSON数据转化为右侧**final.json**中的JSON格式的数据。

### 代码位置
用vscode打开当前目录下**JavaScript-test**项目，上述题目对应的代码位置在这个文件夹中，项目目录如下：
* **config/test.json** 图中左侧JSON数据的结构
* **config/finel.json** 图中右侧JSON数据的结构
* **solve.js** 你需要在这个js文件里实现上述题目