# HTML5介绍

## 什么是HTML5

1.       万维网](http://baike.baidu.com/view/7833.htm)的核心语言、[标准通用标记语言](http://baike.baidu.com/view/5286041.htm)下的一个应用[超文本标记语言](http://baike.baidu.com/view/383720.htm)（[HTML](http://baike.baidu.com/view/692.htm)）的第五次重大修改
2.       支持Html5的浏览器包括[Firefox](http://baike.baidu.com/view/3279.htm)（火狐浏览器），[IE9](http://baike.baidu.com/view/2298486.htm)及其更高版本，[Chrome](http://baike.baidu.com/view/1835504.htm)（谷歌浏览器），[Safari](http://baike.baidu.com/view/110484.htm)，Opera等；国内的傲游浏览器（Maxthon），以及基于IE或[Chromium](http://baike.baidu.com/view/404073.htm)（Chrome的工程版或称实验版）所推出的[360浏览器](http://baike.baidu.com/view/1949679.htm)、[搜狗浏览器](http://baike.baidu.com/view/2083809.htm)、[QQ浏览器](http://baike.baidu.com/view/2610930.htm)、[猎豹浏览器](http://baike.baidu.com/view/8467425.htm)等国产浏览器同样具备支持HTML5的能力
3.       HTML5的设计目的是为了在移动设备上支持多媒体。新的语法特征被引进以支持这一点，如video、audio和canvas 标记。
4.       增加了新特性：语义特性，本地存储特性，设备兼容特性，连接特性，网页[多媒体](http://baike.baidu.com/view/3323.htm)特性，三维、图形及特效特性，性能与集成特性，CSS3特性
5.       相比之前的进步：取消了一些过时的[HTML4](http://baike.baidu.com/view/1187297.htm)标记，将内容和展示分离，一些全新的表单输入对象，全新的，更合理的Tag，本地数据库，Canvas 对象，浏览器中的真正程序，Html5取代Flash在移动设备的地位

```javascript
##1.HTML5优点：
a) 提高可用性和改进用户的友好体验；
b) 可以给站点带来更多的多媒体元素(视频和音频)；
c) 将被大量应用于移动应用程序和游戏；
d) 可移植性好。
e) 开发技术简单，研发周期短，用户接触成本低

##2. 缺点：
	该标准并未能很好的被Pc端浏览器所支持。因新标签的引入，各浏览器之间将缺少一种统一的数据描述格式，造成用户体验不佳。

##3. 未来趋势
a) 移动优先
b) 游戏开发者领衔“主演”
c) 响应式设计&自动变化的屏幕尺寸
d) 设备访问能力，对移动开发商来说，提高设备访问能力是HTML5最令人激动的革新，比如照相机，通讯录，日历，加速器等
e) 离线缓存，离线情况下，app也能照常运作
```

## HTML5的应用场景

```
1、HTML5的游戏开发，例如简单的微信小游戏，打飞机等，HTML5网页游戏
2、轻应用、Webapp
3、微站、微店等基于微信平台的开发，微信开放JSSDK让H5的开发人员可以调用底层功能，实现扫一扫，卡卷，微信支付等操作
4、HTML5教程移动营销
   游戏化、场景化、跨屏互动，HTML5技术完美的满足了各大广告商心里的梦想，从形式到功用、到传播，只要是你能想到的，没有它做不到的。
5、HTML5和原生App的嵌套使用
```

<img src="media/weizhan.png" />

## H5的app和原生app区别

```javascript
# 一、开发方面
//原生App
1. 每一种移动操作系统都需要独立的开发项目
2. 每种平台都需要独立的开发语言。Java(Android), Objective-C swift(iOS)以及Visual C++(Windows Mobile)等等
3. 需要使用各自的软件开发包，开发工具以及各自的控件

//移动Web App
1. 因为运行在移动设备的浏览器上，所以只需要一个开发项目
2. 这种应用可以使用HTML5,CSS3以及JavaScript以及服务器端语言来完成（PHP,Ruby on Rails,Python）

# 二、获取方法
//原生App
1. 直接下载到设备
2. 以独立的应用程序运行(并不需要浏览器)
3. 用户必须手动去下载并安装这些原生App
4. 有一些商店与卖场来帮助用户寻找你的App，目前app市场不计其数

//移动Web App
1. 从移动设备上的浏览器访问
2. 不需要安装额外的软件
3. 软件更新只需要服务器就够了
4. 因为现在没有什么商品或卖场提供这种App，所以如何搜索这些移动Web App相当不简单。

# 三、优势
//原生App
1. 比移动Web App运行快
2. 一些商店与卖场会帮助用户寻找原生App
3. 官方卖场的应用审核流程会保证让用户得到高质量以及安全的App
4. 官方会发布很多开发工具或者人工支持来帮助你的开发


//移动Web App
1. 跨平台开发
2. 用户不需要去卖场来下载安装App
3. 任何时候都可以发布App，因为根本不需要官方卖场的审核

# 四、缺陷
//原生App
1. 开发成本高，尤其是当需要多种移动设备来测试时
2. 因为是不同的开发语言，所以开发，维护成本也高
3. 因为用户使用的App版本不同，所以你维护起来很困难
4. 官方卖场审核流程复杂且慢，会严重影响你的发布进程

//移动Web App
1. 只能使用有限的移动硬件设备功能,无法使用很多移动硬件设备的独特功能,要同时支持多种移动设备的浏览器让开发维护的成本也不低（也要适配不同的浏览器）
2. 性能差，动画、DOM操作、页面切换时内存难管理
3. 要同时支持多种移动设备的浏览器让开发维护的成本也不低
4. 如果用户使用更多的新型浏览器，那问题就更不好处理了
5. 对于用户来说，这种App很难被用户发现
```

# HTML5新标签与特性

<img src="media/html.jpg" />

## 文档类型设定

```html
document
- HTML:        sublime 输入  html:4s
- XHTML:       sublime 输入  html:xt
- HTML5        sublime 输入  html:5       <!DOCTYPE html>
```

## 字符设定

```html
<meta http-equiv="charset" content="utf-8">：HTML与XHTML中建议这样去写
<meta charset="utf-8">：HTML5的标签中建议这样去写
```

## 常用新标签

 w3c  手册中文官网     :   http://w3school.com.cn/

- header：定义文档的页眉 头部

- nav：定义导航链接的部分

- footer：定义文档或节的页脚 底部

- article：定义文章。

- section：定义文档中的节（section、区段）

- aside：定义其所处内容之外的内容 侧边
![](media\h5fenkuai.png)

```javascript
<header> 语义 :定义页面的头部  页眉</header>
<nav>  语义 :定义导航栏 </nav> 
<footer> 语义: 定义 页面底部 页脚</footer>
<article> 语义:  定义文章</article>
<section> 语义： 定义区域</section>
<aside> 语义： 定义其所处内容之外的内容 侧边</aside>

//案例：
<header>头部</header>
<nav>导航</nav>
<main>
    <article>左边</article>
    <aside>
    	<header></header>
		<main></main>
		<footer></footer>
    </aside>
</main>
<footer>底部</footer>
```

- datalist   标签定义选项列表。请与 input 元素配合使用该元素


```html
<input type="text" list="star"/> <!--  input里面用 list -->
<datalist id="star">   <!-- datalist 里面用 id  来实现和 input 链接 -->  
    <option>刘德华</option>
    <option>刘若英</option>
    <option>刘晓庆</option>
    <option>郭富城</option>
    <option>张学友</option>
    <option>郭郭</option>
</datalist>

<!--type=url-->
网址：<input type="url" list="urls">
<datalist id="urls">
    <!--如果input输入框的type类型是url,那么value值必须添加http://-->
    <option value="http://www.baidu.com" label="百度"></option>
    <option value="http://www.sohu.com"></option>
    <option value="http://www.163.com"></option>
</datalist>
```
  ```html
<!-- fieldset 元素可将表单内的相关元素分组，打包      legend 搭配使用-->
<fieldset>
    <legend>用户登录</legend>  标题
    用户名: <input type="text"><br /><br />
    密　码: <input type="password">
</fieldset>
  ```

## HTML5移除的标签

```html
<acronym> 字体兼容
<applet> java组件
<basefont> 字体
<big>
<center>
<dir> 目录
<del>
<font>
<frame>
<frameset>
<noframes>
<strike>
```

## 新增的input type属性值：

| **类型**     | **使用示例**            | **含义**             |
| ------------ | ----------------------- | -------------------- |
| **email**    | <input type="email">    | 输入邮箱格式         |
| **tel**      | <input type="tel">      | 输入手机号码格式     |
| **url**      | <input type="url">      | 输入url格式          |
| **number**   | <input type="number">   | 输入数字格式         |
| **search**   | <input type="search">   | 搜索框（体现语义化） |
| **range**    | <input type="range">    | 自由拖动滑块         |
| **time**     | <input type="time">     | 小时分钟             |
| **date**     | <input type="date">     | 年月日               |
| **datetime** | <input type="datetime"> | 时间                 |
| **month**    | <input type="month">    | 月年                 |
| **week**     | <input type="week">     | 星期 年              |

```html
用户名：<input type="text" name="userName"> <br>
密码：<input type="password" name="userPwd"> <br>
<!--email提供了默认的电子邮箱的完整验证：要求必须包含@符号，同时必须包含服务器名称，如果不能满足验证，则会阻止当前的数据提交-->
邮箱：<input type="email"> <br>
<!--tel它并不是来实现验证。它的本质目的是为了能够在移动端打开数字键盘。意味着数字键盘限制了用户只能输入数字。  如何查看效果：qq发送文件>>手机端使用qq来接收>>使用手机浏览器查看-->
电话：<input type="tel"> <br>
<!--验证只能输入合法的网址：必须包含http://-->
网址：<input type="url"> <br>
<!--number：只能输入数字(包含小数点)，不能输入其它的字符
max:最大值
min:最小值
value:默认值-->
数量：<input type="number" value="60" max="100" min="0"> <br>
<!--search：可以提供更人性化的输入体验-->
请输入商品名称：<input type="search"> <br>
<!--range:范围-->
范围：<input type="range" max="100" min="0" value="50"> <br>
颜色：<input type="color"> <br>
<!--日期时间相关-->
<!--time:时间：时分秒-->
时间：<input type="time"> <br>
<!--date：日期：年月日-->
日期：<input type="date"> <br>
<!--datetime:大多数浏览器不能支持datetime.用于屏幕阅读器-->
日期时间：<input type="datetime"><br>
<!--datetime-local:日期和时间-->
日期时间：<input type="datetime-local" value="2017-06-30T00:00"> <br>
月份：<input type="month"> <br>
星期：<input type="week">
<!--提交-->
<input type="submit">
```

## 表单常用新属性

| **属性**         | **用法**                                       | **含义**                                                     |
| ---------------- | ---------------------------------------------- | ------------------------------------------------------------ |
| **placeholder**  | <input type="text" placeholder="请输入用户名"> | 占位符  当用户输入的时候 里面的文字消失  删除所有文字，自动返回 |
| **autofocus**    | <input type="text" autofocus>                  | 规定当页面加载时 input 元素应该自动获得焦点                  |
| **multiple**     | <input type="file" multiple>                   | 多文件上传                                                   |
| **autocomplete** | <input type="text" autocomplete="off">         | 规定表单是否应该启用自动完成功能  有2个值，一个是on 一个是off      on 代表记录已经输入的值  1.autocomplete 首先需要提交按钮 <br/>2.这个表单您必须给他名字 |
| **required**     | <input type="text" required>                   | 必填项  内容不能为空                                         |
| **accesskey**    | <input type="text" accesskey="s">              | 规定激活（使元素获得焦点）元素的快捷键   采用 alt + s的形式  |

```html
<form action="" id="myForm">
    <!--placeholder：提示文本，提示占位-->
    <!--autofocus:自动获取焦点-->
    <!--autocomplete:自动完成：on:打开  off:关闭
    1.必须成功提交过:提交过才会记录
    2.当前添加autocomplete的元素必须有name属性-->
    用户名：<input type="text" name="userName" placeholder="请输入用户名" autofocus autocomplete="on"> <br>
    <!--tel并不会实现验证，仅仅是在移动端能够弹出数字键盘-->
    <!--required:必须输入，如果没有输入则会阻止当前数据提交-->
    <!--pattern:正则表达式验证
    *:代表任意个
    ?:代表0个或1个
    +：代表1个或多个-->
    手机号：<input type="tel" name="userPhone" required pattern="^(\+86)?1\d{10}$"> <br>
    <!--multiple：可以选择多个文件-->
    文件：<input type="file" name="photo" multiple> <br>
    <!--email:有默认验证  在email中，multiple允许输入多个邮箱地址，以逗号分隔-->
    邮箱：<input type="email" name="email" multiple><br>
    
    <!--提交：-->
    <input type="submit"> <br>
</form>
<!--下面这个表单元素并没有包含在form中：默认情况下面表单元素的数据不会进行提交-->
<!--form:指定表单id,那么在将来指定id号的表单进行数据提交的时候，也会将当前表单元素的数据一起提交-->
地址：<input type="text" name="address" form="myForm">
```

## 表单新事件

oninput 用户输入内容时触发，可用于移动端输入字数统计

oninvalid 验证不通过时触发

```javascript
<form action="">
    用户名：<input type="text" name="userName" id="userName"><br>
    电话：<input type="tel" name="userPhone" id="userPhone" pattern="^1\d{10}$"> <br>
    <input type="submit">
</form>

<script>
    /*1.oninput:监听当前指定元素内容的改变：只要内容改变(添加内容，删除内容)，就会触发这个事件*/
    document.getElementById("userName").oninput=function(){
        console.log("oninput:"+this.value);
    }

    /*onkeyup:键盘弹起的时候触发：每一个键的弹起都会触发一次*/
    document.getElementById("userName").onkeyup=function(){
        console.log("onkeyup:"+this.value);
    }

    /*oninvalid:当验证不通过时触发*/
    document.getElementById("userPhone").oninvalid=function(){
        /*设置默认的提示信息*/
        this.setCustomValidity("请输入合法的11位手机号");
   }
</script>
```

## 综合案例

```html
<form action="">
  <fieldset>
    <legend>学生档案</legend>
    <label for="userName">姓名:</label>
    <input type="text" name="userName" id="userName" placeholder="请输入用户名"> <br>
    <label for="userPhone">手机号码:</label>
    <input type="tel" name="userPhone" id="userPhone" pattern="^1\d{10}$"><br>
    <label for="email">邮箱地址:</label>
    <input type="email" required name="email" id="email"><br>
    <label for="collage">所属学院:</label>
    <input type="text" name="collage" id="collage" list="cList" placeholder="请选择"><br>
    <datalist id="cList">
      <option value="前端与移动开发学院"></option>
      <option value="java学院"></option>
      <option value="c++学院"></option>
    </datalist><br>
    <label for="score">入学成绩:</label>
    <input type="number" max="100" min="0" value="0" id="score"><br>
    <label for="inTime">入学日期:</label>
    <input type="date" id="inTime" name="inTime"><br>
    <label for="leaveTime">毕业日期:</label>
    <input type="date" id="leaveTime" name="leaveTime"><br>
    <input type="submit">
  </fieldset>
</form>
```

## 度量和进度条

```html
<!--max:最大值
value:当前进度值-->
<progress max="100" value="100"></progress>

<!--度量器：衡量当前进度值-->
<!--high:规定的较高的值
low:规定的较低的值
max:最大值
min:最小值
value:当前度量值-->
<meter max="100" min="0" high="80" low="40" value="30"></meter>
<meter max="100" min="0" high="80" low="40" value="60"></meter>
<meter max="100" min="0" high="80" low="40" value="100" name="level"></meter>
```

## 多媒体标签

- embed：标签定义嵌入的内容
- audio：播放音频
- video：播放视频

### 多媒体 embed（会使用）

​	embed可以用来插入各种多媒体，格式可以是 Midi、Wav、AIFF、AU、MP3等等。url为音频或视频文件及其路径，可以是相对路径或绝对路径。

​	embed本质是通过本机安装的音频视频播放软件来播放的，要求必须已经安装了这些软件兼容性-。 

```html
<embed src="http://player.youku.com/player.php/sid/XMTI4MzM2MDIwOA==/v.swf" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>
```

 <img src="media/embed.png" />

### 多媒体 audio

​	HTML5通过<audio>标签来解决音频播放的问题。

​	使用相当简单，如下图所示

![1498468026526](media/1498468026526.png) 

```javascript
//并且可以通过附加属性可以更友好控制音频的播放，如：
autoplay 自动播放
controls 是否显不默认播放控件
loop 循环播放    如果这个属性不写 默认播放一次        loop  或者  loop = “loop”    表示无限循环

//由于版权等原因，不同的浏览器可支持播放的格式是不一样的，如下图供参考
```

![1498468041058](media/1498468041058.png) 

```javascript
//多浏览器支持的方案，如下图:
<source> 标签允许您规定可替换的视频/音频文件供浏览器根据它对媒体类型或者编解码器的支持进行选择
```

![1498468052965](media/1498468052965.png) 

### 多媒体 video

​	HTML5通过<audio>标签来解决音频播放的问题。

​	同音频播放一样，<video>使用也相当简单，如下图

![1498468072194](media/1498468072194.png) 

```javascript
//同样，通过附加属性可以更友好的控制视频的播放
autoplay 自动播放
controls 是否显示默认播放控件
loop 循环播放
width 设置播放窗口宽度
height 设置播放窗口的高度
```

​	由于版权等原因，不同的浏览器可支持播放的格式是不一样的，如下图供参考

![1498468086199](media/1498468086199.png) 

​	**多浏览器支持的方案，如下图**

![1498468097509](media/1498468097509.png)

## DOM元素扩展

### 获取元素：

```javascript
a)  document.getElementsByClassName('class') 通过类名获取元素，以类数组形式存在。
b)  document.querySelector('selector')通过CSS选择器获取元素，符合匹配条件的第1个元素。
c)  document.querySelectorAll('selector')通过CSS选择器获取元素，以类数组形式存在。
```

### 类名操作：

```javascript
a)  Node.classList.add('class') 添加class
b)  Node.classList.remove('class') 移除class
c)  Node.classList.toggle('class') 切换class，有则移除，无则添加
d)  Node.classList.contains('class')检测是否存在class
```

```javascript
//案例
<style>
    .red{
        color:red
    }
    .green{
        color: green;
    }
    .blue{
        color: blue;
    }
    .underline{
        text-decoration: underline;
    }
</style>

<ul>
    <li class="red">前端与移动开发</li>
    <li class="blue">java</li>
    <li>javascript</li>
    <li class="red">c++</li>
</ul>
<input type="button" value="为第一个li元素添加样式" id="add">
<input type="button" value="为第二个li元素移除样式" id="remove">
<input type="button" value="为第三个li元素切换样式" id="toggle">
<input type="button" value="判断第四个li元素是否包含某个样式" id="contain">


<script>
    window.onload=function(){
        /*add:为元素添加指定名称的样式.一次只能添加一个样式*/
        document.querySelector("#add").onclick=function(){
            /*classList:当前元素的所有样式列表-数组*/
            document.querySelector("li").classList.add("red");
            document.querySelector("li").classList.add("underline");
            //document.querySelector("li").className="red underline"
            /*获取样式*/
            var result=document.querySelector("li").classList.item(2);
            console.log(result);
        }

        /*remove:为元素移除指定名称的样式(不是移除class属性)，一次也只能移除一个*/
        document.querySelector("#remove").onclick=function(){
            document.querySelector(".blue").classList.remove("blue");
        }

        /*toggle：切换元素的样式：如果元素之前没有指定名称的样式则添加。如果有则移除*/
        document.querySelector("#toggle").onclick=function(){
            document.querySelectorAll("li")[2].classList.toggle("green");
        }

        /*contains:判断元素是否包含指定名称的样式，返回true/false*/
        document.querySelector("#contain").onclick=function(){
            var isContain=document.querySelectorAll("li")[3].classList.contains("red");
            console.log(isContain);
        }
    }
</script>
```

### 自定义属性：

```javascript
a) 在HTML5中我们可以自定义属性，其格式如下data-*=""，例如：data-info="我是自定义属性"，通过Node.dataset['info'] 我们便可以获取到自定义的属性值。
b) 当我们如下格式设置时，则需要以驼峰格式才能正确获取：data-my-name="haha"，获取Node.dataset['myName']

<p data-school-name="无锡极客营">极客学院</p>
```

### 小案例：tab标签页

![](media\cli002.png)

```html
<style>
    *{
        padding: 0;
        margin: 0;
    }
    .tabs{
        width: 500px;
        border: 1px solid #ccc;
        box-sizing: border-box;
        margin:0 auto;
    }
    .tabs > div{
        width: 100%;
    }
    .tabs > div > a {
        width:25%;
        height: 50px;
        display: block;
        line-height: 50px;
        text-align: center;
        float: left;
        background-color: #ceffbb;
        border-right: 2px solid #fff;
        box-sizing: border-box;
        text-decoration: none;
    }
    .tabs > div > a.active{
        background-color: #ffcea1;
    }
    .tabs > div > a:last-child{
        border-right:none;
    }
    .tabs > section{
        width:100%;
        display: none;
        padding: 20px;
        clear: both;
    }
    .tabs > section > ol{
        padding-left:30px;
    }
    .tabs > section > ol > li{
        line-height: 40px;
    }
</style>

<div class="tabs">
    <div>
        <a href="javascript:;" data-target="local">国内新闻</a>
        <a href="javascript:;" data-target="global">国际新闻</a>
        <a href="javascript:;" data-target="sports">体育新闻</a>
        <a href="javascript:;" data-target="funny">娱乐新闻</a>
    </div>
    
       <section class="cont active" id="local">
        <ol>
            <li>习近平向2名晋升为上将军官颁发命令状</li>
            <li>郭声琨了解指导公安消防部队抗洪工作</li>
            <li>媒体：曾任职中办的这位官员仕途有变</li>
            <li>广西警方端掉地下兵工厂缴获大批炮弹</li>
            <li>她完美诠释奇葩考题夺金牌</li>
            <li>中国奥运选手在里约多次遭抢劫</li>
        </ol>
    </section>

    <section class="cont active" id="global">
        <ol>
            <li>河南再次发生矿难，死伤人数超过100</li>
            <li>禽流感次发生蔓延，温家宝指示</li>
            <li>南方大旱，农作物减产绝收面积上亩</li>
            <li>猪流感在广减产绝收发</li>
            <li>禽流感在全国多作物减产绝收面积上亩</li>
            <li>猪流感在广东群体性暴发</li>
        </ol>
    </section>

    <section class="cont" id="sports">
        <ol>
            <li>河南再次发生矿难，死伤人数超过10</li>
            <li>禽流感在全国多处农作物农延，温家宝指示</li>
            <li>南方大旱，农作物减产绝收面积上亩</li>
            <li>猪流感在广东群体性暴发</li>
            <li>禽流感在全农作物继续蔓延，温家宝指示</li>
            <li>南方大农作物减产绝收面积上亩</li>
            <li>猪流感在广东群体性暴发</li>
        </ol>

    </section>

    <section class="cont" id="funny">
        <ol>
            <li>福建发生血腥命案:两女遭割喉 1男孩被砍数刀</li>
            <li>四川原副省长李成云被查 5年前曾违纪又复出</li>
            <li>胡歌反对粉丝探班：以前请吃饭现在会黑脸</li>
            <li>曝郑爽爸爸歌厅撩妹 与女子勾肩搭背显亲密</li>
            <li>宜宾公安副局长无证驾驶出车祸 弃车离开现场</li>
            <li>国子监大街门匾现错字 已悬挂近10年(图)</li>
            <li>猪流感在广东群体性暴发</li>
       </ol>
    </section>
</div>
```

```javascript
<script>
    /*1.获取到所有a标签*/
    /*2.为a标签添加点击事件*/
    /*3.当点击某个a标签的时候，获取到当前a标签的target属性值，让对应名称的section面板显示*/
    /*4.让上一个被点击的超链接的样式清除，同时让对应名称的面板隐藏*/
    (function(index){
        var allA=document.querySelectorAll('a');
        /*循环添加事件*/
        for(var i=0;i<allA.length;i++){
            /*初始化面板的显示*/
            if(i==index){//说明这就是默认需要展示的面板
                allA[i].classList.add('active');
                var firstTarget=allA[i].dataset['target'];
                document.querySelector("#"+firstTarget).style.display="block";
            }
            allA[i].onclick=function(){
                /*先找到上一个被点击的a标签*/
                var lastA=document.querySelector('.active');
                lastA.classList.remove('active');
                var lastTarget=lastA.dataset['target'];
                /*让其隐藏*/
                document.querySelector("#"+lastTarget).style.display="none";

                /*1.添加active样式*/
                this.classList.add('active');
                /*2.获取target属性值*/
                var target=this.dataset['target'];
                /*3.让对应名称的面板显示*/
                document.querySelector("#"+target).style.display="block";
            }
        }
    })(3);
</script>
```

# HTML接口

## 网络状态

```css
// online网络连接事件
window.addEventListener("online",function() {
    alert("网络连接已建立");
});

// offline网络连接事件
window.addEventListener("offline",function() {
    alert("网络连接已断开");
});
```

## 全屏接口

```css
<body>
<div>
    <img src="../images/l1.jpg" alt="">
    <input type="button" id="full" value="全屏">
    <input type="button" id="cancelFull" value="退出全屏">
    <input type="button" id="isFull" value="是否全屏">
</div>
<script>
    /*全屏操作的主要方法和属性
    * 1.requestFullScreen():开启全屏显示
    *   不同浏览器需要添加不同的前缀
    *   chrome:webkit   firefox:moz   ie:ms   opera:o
    * 2.cancelFullScreen():退出全屏显示:也添加前缀，在不同的浏览器下.退出全屏只能使用document来实现
    * 3.fullScreenElement:是否是全屏状态，也只能使用document进行判断*/

    window.onload=function(){
        var div=document.querySelector("div");
        /*添加三个按钮的点击事件*/
        /*全屏操作*/
        document.querySelector("#full").onclick=function(){
            /*div.requestFullScreen();*/
            /*div.webkitRequestFullScreen();*/
            /*div.mozRequestFullScreen();*/
            /*使用能力测试添加不同浏览器下的前缀*/
            if(div.requestFullScreen){
                div.requestFullScreen();
            }
            else if(div.webkitRequestFullScreen){
                div.webkitRequestFullScreen();
            }
            else if(div.mozRequestFullScreen){
                div.mozRequestFullScreen();
            }
            else if(div.msRequestFullScreen){
                div.msRequestFullScreen();
            }
        }

        /*退出全屏*/
        document.querySelector("#cancelFull").onclick=function(){
            if(document.cancelFullScreen){
                document.cancelFullScreen();
            }
            else if(document.webkitCancelFullScreen){
                document.webkitCancelFullScreen();
            }
            else if(document.mozCancelFullScreen){
                document.mozCancelFullScreen();
            }
            else if(document.msCancelFullScreen){
                document.msCancelFullScreen();
            }
        }

        /*判断是否是全屏状态*/
        document.querySelector("#isFull").onclick=function(){
            /*两个细节：使用document判断  能力测试*/
            if(document.fullscreenElement || document.webkitFullscreenElement || document.mozFullScreenElement || document.msFullscreenElement){
                alert(true);
            }
            else{
                alert(false);
            }
        }
    }
</script>
</body>

# 注意：iphone下的Safari下并不支持该接口
```

## FileReader接口

```css
<body>
<!--展示图片：-->
<!--src:指定路径(资源定位--url):src请求的是外部文件，一般来说是服务器资源。意味着它需要向服务器发送请求，它占用服务器资源-->
<!--<img src="../images/l1.jpg" alt="">-->

<!--需求：即时预览：
即时：当用户选择完图片之后就立刻进行预览的处理 >>onchange
预览：通过文件读取对象的readAsDataURL()完成-->
<form action="">
    文件： <input type="file" name="myFile" id="myFile" onchange="getFileContent();"> <br>
    <div></div>
    <input type="submit">
</form>
<img src="" alt="">
<script>
    /*FileReader:读取文件内容
    * 1.readAsText():读取文本文件(可以使用Txt打开的文件)，返回文本字符串，默认编码是UTF-8
    * 2.readAsBinaryString():读取任意类型的文件。返回二进制字符串。这个方法不是用来读取文件展示给用户看，而是存储文件。例如：读取文件的内容，获取二进制数据，传递给后台，后台接收了数据之后，再将数据存储
    * 3.readAsDataURL():读取指定的Blob(二进制)中的内容。
    * abort():中断读取*/
    function getFileContent(){
       /*1.创建文件读取对象*/
        var reader=new FileReader();
        /*2.读取文件，获取DataURL
        * 2.1.说明没有任何的返回值:void：但是读取完文件之后，它会将读取的结果存储在文件读取对象的result中
        * 2.2.需要传递一个参数 binary large object:文件(图片或者其它可以嵌入到文档的类型)
        * 2.3:文件存储在file表单元素的files属性中，它是一个数组*/
        var file=document.querySelector("#myFile").files;
        reader.readAsDataURL(file[0]);
        /*获取数据*/
        /*FileReader提供一个完整的事件模型，用来捕获读取文件时的状态
        * onabort:读取文件中断时触发
        * onerror:读取错误时触发
        * onload:文件读取成功完成时触发
        * onloadend:读取完成时触发，无论成功还是失败
        * onloadstart:开始读取时触发
        * onprogress:读取文件过程中持续触发*/
        reader.onload=function(){
            //console.log(reader.result);
            /*展示*/
            document.querySelector("img").src=reader.result;
        }

        reader.onprogress=function(e){
            var percent= e.loaded/ e.total*100+"%";
            console.log(percent);
        }
    }
</script>
</body>
```

## 拖拽接口

```javascript
<style>
    *{
        margin: 0;
        padding: 0;
    }
    .div1{
        width: 200px;
        height: 200px;
        border: 1px solid red;
        position: relative;
        margin-left:20px;
        float: left;
     }
    .div2{
        width: 200px;
        height: 200px;
        border: 1px solid blue;
        position: relative;
        margin-left:20px;
        float: left;
    }
    .div3{
        width: 200px;
        height: 200px;
        border: 1px solid green;
        position: relative;
        margin-left:20px;
        float: left;
    }
    p{
        background-color: orange;
        margin-top: 5px;
    }
</style>

    
<div class="div1" id="div1">
    <!--在h5中，如果想拖拽元素，就必须为元素添加draggable="true". 图片和超链接默认就可以拖拽-->
    <p id="pe" draggable="true">试着把我拖过去</p>
    <p id="pe1" draggable="true">试着也把我拖过去</p>
</div>
<div class="div2" id="div2"></div>

<script>
    /*学习拖拽，主要就是学习拖拽事件*/
    var p=document.querySelector("#pe");
    var div2=document.querySelector("#div2");
    var div1=document.querySelector("#div1");
    /*应用于被拖拽元素的事件
    *ondrag         应用于拖拽元素，整个拖拽过程都会调用--持续
     ondragstart    应用于拖拽元素，当拖拽开始时调用
     ondragend      应用于拖拽元素，当拖拽结束时调用*/
    p.ondragstart=function(){
        console.log("ondragstart");
    }
    p.ondragend=function(){
        console.log("ondragend");
    }
    p.ondrag=function(){
        //console.log("ondrag");
    }

    /*应用于目标元素的事件
    *ondragenter    当被鼠标拖动的对象进入其容器范围内时触发此事件
     ondragover     当某被拖动的对象在另一对象容器范围内拖动时触发此事件
     ondrop         在一个拖动过程中，释放鼠标键时触发此事件
     ondragleave    当被鼠标拖动的对象离开其容器范围内时触发此事件*/
    div2.ondragenter=function(){
        console.log("ondragenter");
    }
    div2.ondragover=function(e){
        //console.log("ondragover");
        /*如果想触发ondrop事件，那么就必须在这个位置阻止浏览器的默认行为*/
        e.preventDefault();
    }
    /*浏览器默认会阻止ondrop事件：我们必须在ondragover中阻止浏览器的默认行为*/
    div2.ondrop=function(){
        console.log("ondrop");
        /*添加被拖拽的元素到当前目标元素*/
        div2.appendChild(p);
    }
    div2.ondragleave=function(){
        console.log("目标元素：ondragleave");
    }

    div1.ondragover=function(e){
        //console.log("ondragover");
        /*如果想触发ondrop事件，那么就必须在这个位置阻止浏览器的默认行为*/
        e.preventDefault();
    }
    div1.ondrop=function(){
        console.log("ondrop");
        /*添加被拖拽的元素到当前目标元素*/
        div1.appendChild(p);
    }
</script>

//注意：该接口不兼容移动端
```

```javascript
## 拖拽接口-通用的拖拽事件
<style>
*{
    margin: 0;
    padding: 0;
}
.div1{
    width: 200px;
    height: 200px;
    border: 1px solid red;
    position: relative;
    margin-left:20px;
    float: left;
}
.div2{
    width: 200px;
    height: 200px;
    border: 1px solid blue;
    position: relative;
    margin-left:20px;
    float: left;
}
.div3{
    width: 200px;
    height: 200px;
    border: 1px solid green;
    position: relative;
    margin-left:20px;
    float: left;
}
p{
    background-color: orange;
    margin-top: 5px;
}
</style>
    
    
<body>
<div class="div1" id="div1">
    <!--在h5中，如果想拖拽元素，就必须为元素添加draggable="true". 图片和超链接默认就可以拖拽-->
    <p id="pe" draggable="true">试着把我拖过去</p>
    <p id="pe1" draggable="true">试着也把我拖过去</p>
</div>
<div class="div2" id="div2"></div>
<script>
    /*学习拖拽，主要就是学习拖拽事件*/
    var obj=null;//当前被拖拽的地元素

    /*应用于被拖拽元素的事件
    *ondrag         应用于拖拽元素，整个拖拽过程都会调用--持续
     ondragstart    应用于拖拽元素，当拖拽开始时调用
     ondragend    应用于拖拽元素，当拖拽结束时调用*/
    document.ondragstart=function(e){
        /*通过事件捕获来获取当前被拖拽的子元素*/
        e.target.style.opacity=0.5;
        e.target.parentNode.style.borderWidth="5px";
        obj= e.target;
        /*dataTransfer对象提供了对于预定义的剪贴板格式的访问，以便在拖曳操作中使用。
		通俗的讲就是在拖曳操作的过程中，我们可以用过dataTransfer对象来传输数据，以便在拖曳操作结束的时
		候对数据进行其他的操作。
        * setData(format,data):
        * format:定义数据的格式，实际为数据的类型，text/html   text/uri-list
        * Data:数据:一般来说是字符串值*/
        e.dataTransfer.setData("text/html", e.target.id);
    }
    document.ondragend=function(e){
        e.target.style.opacity=1;
        e.target.parentNode.style.borderWidth="1px";
    }
    document.ondrag=function(e){
    }

    /*应用于目标元素的事件
    *ondragenter    当被鼠标拖动的对象进入其容器范围内时触发此事件
     ondragover     当某被拖动的对象在另一对象容器范围内拖动时触发此事件
     ondrop         在一个拖动过程中，释放鼠标键时触发此事件
     ondragleave    当被鼠标拖动的对象离开其容器范围内时触发此事件*/
    document.ondragenter=function(e){
        console.log(e.target);
    }
    document.ondragover=function(e){
        /*如果想触发ondrop事件，那么就必须在这个位置阻止浏览器的默认行为*/
        e.preventDefault();
    }
    /*浏览器默认会阻止ondrop事件：我们必须在ondragover中阻止浏览器的默认行为*/
    document.ondrop=function(e){
        /*添加元素*/
        //e.target.appendChild(obj);
        /*通过e.dataTransfer.setData获取剪切板存储的数据，只能在drop事件中获取*/
        var id=e.dataTransfer.getData("text/html");
        /*console.log("id="+id);*/
        e.target.appendChild(document.getElementById(id));
    }
    document.ondragleave=function(e){
    }
</script>
</body>

#注意：如果移动端要拖拽，得另外通过touches计算距离处理
https://blog.csdn.net/qq_31201781/article/details/80815730
```

## 数据存储

### sessionStorage

```css
<body>
<pre>
    sessionStorage的使用：存储数据到本地。存储的容量5mb左右。
        1.这个数据本质是存储在当前页面的内存中-意味着其它页面和浏览器无法获取数据
        2.它的生命周期为关闭当前页面，关闭页面，数据会自动清除
    setItem(key,value):存储数据，以键值对的方式存储
    getItem(key):获取数据，通过指定名称的key获取对应的value值
    removeItem(key):删除数据，通过指定名称key删除对应的值
    clear():清空所有存储的内容
</pre><br>
<input type="text" id="userName"><br>
<input type="button" value="设置数据" id="setData">
<input type="button" value="获取数据" id="getData">
<input type="button" value="删除数据" id="removeData">
<script>
    /*存储数据*/
    document.querySelector("#setData").onclick=function(){
        /*获取用户名*/
        var name=document.querySelector("#userName").value;
        /*存储数据*/
        window.sessionStorage.setItem("userName",name);
    }
    /*获取数据*/
    document.querySelector("#getData").onclick=function(){
        /*如果找不到对应名称的key,那么就会获取null*/
        var name=window.sessionStorage.getItem("userName");
        alert(name);
    }
    /*删除数据*/
    document.querySelector("#removeData").onclick=function(){
        /*在删除的时候如果key值错误，不会报错，但是也不会删除数据*/
        window.sessionStorage.removeItem("userName1");
    }
</script>
</body>
```

### localStorage

```css
<body>
<pre>
    localStorage的使用：
       1.存储的内容大概20mb
       2.不同浏览器不能共享数据。但是在同一个浏览器的不同窗口中可以共享数据
       3.永久生效，它的数据是存储在硬盘上，并不会随着页面或者浏览器的关闭而清除.如果想清除，必须手动清除
    setItem(key,value):存储数据，以键值对的方式存储
    getItem(key):获取数据，通过指定名称的key获取对应的value值
    removeItem(key):删除数据，通过指定名称key删除对应的值
    clear():清空所有存储的内容
</pre>
<br>
<input type="text" id="userName"><br>
<input type="button" value="设置数据" id="setData">
<input type="button" value="获取数据" id="getData">
<input type="button" value="删除数据" id="removeData">

<script>
    document.querySelector("#setData").onclick=function(){
        var name=document.querySelector("#userName").value;
        /*使用localStorage存储数据*/
        window.localStorage.setItem("userName",name);
    }
    /*获取数据*/
    document.querySelector("#getData").onclick=function(){
        var name=window.localStorage.getItem("userName");
        alert(name);
    }
    /*清除数据*/
    document.querySelector("#removeData").onclick=function(){
        window.localStorage.removeItem("userName");
    }
</script>
</body>
```

### 记住用户名

```css
<style>
div{
    width: 300px;
    height: 200px;
    border: 1px solid #ccc;
    margin:0 auto;
    padding-left:80px;
    padding-top:30px;
}
label{
    height: 30px;
    line-height:30px;
}
input[type="submit"]{
    width:230px;
    height: 30px;
    line-height:30px;
    text-align: center;
    margin-top:10px;
}
</style>


<div>
    <label for="userName">昵称：</label>
    <input type="text" name="userName" id="userName"> <br>
    <label for="userPwd">密码：</label>
    <input type="password" name="userPwd" id="userPwd"> <br>
    <label for="isRemenber">是否记住用户名:</label>
    <input type="checkbox" id="isRemenber"><br>
    <input type="submit" value="提交" id="submit">
</div>
<script>
    window.onload=function(){

        /*页面打开，判断是否存储过用户名---*/
        var uName=window.localStorage.getItem('userName');
        if(uName != null){//说明之前存储过值，说明用户希望记住用户名
            document.getElementById('userName').value=uName;
            document.getElementById('userPwd').focus();
        }
        else{
            document.getElementById('userName').focus();
        }

        /*点击登录时存储数据*/
        document.getElementById("submit").onclick=function(){
            var name=document.getElementById('userName').value;
            /*判断用户是否选择记住用户名*/
            var isRemenber=document.getElementById('isRemenber');
            if(isRemenber.checked==true){
                /*存储数据到localstorage*/
                window.localStorage.setItem('userName',name);
            }
            else{
                window.localStorage.removeItem('userName');
            }
        }
    }
</script>
```

## 应用缓存

1.    概念：使用 HTML5，通过创建 cache manifest 文件，可以轻松地创建 web 应用的离线版本


2. 优势：

   a)    可配置需要缓存的资源

   b)    网络无连接应用仍可用

   c)    本地读取缓存资源，提升访问速度，增强用户体验

   d)    减少请求，缓解服务器负担



```css
<!--html文件
  应用缓存开启后，即使没有网络，一样可以通过指定网址访问页面
-->
<!DOCTYPE html>
<!--manifest="应用程序缓存清单文件的路径  建议文件的扩展名是appcache,这个文件的本质就是一个文本文件"-->
<html lang="en" manifest="demo.appcache">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        img{
            width: 300px;
            display: block;
        }
    </style>
</head>
<body>
<img src="../images/l1.jpg" alt="">
<img src="../images/l2.jpg" alt="">
<img src="../images/l3.jpg" alt="">
<img src="../images/l4.jpg" alt="">
</body>
</html>
```

***demo.appcache***

```css
CACHE MANIFEST
#上面一句代码必须是当前文档的第一句
#后面写注释

#需要缓存的文件清单列表
CACHE:
#下面就是需要缓存的清单列表
../images/l1.jpg
../images/l2.jpg
# *:代表所有文件

#配置每一次都需要重新从服务器获取的文件清单列表
NETWORK:
../images/l3.jpg

#配置如果文件无法通过网络获取该文件则使用指定的文件进行替代
FALLBACK:
../images/l4.jpg ../images/banner_1.jpg
# /:代表所有文件
```

## 地理定位(需要在手机端浏览器)

```javascript
<body>
<div id="demo" class="de"></div>
<script>
    var x=document.getElementById("demo");
    function getLocation()
    {
        /*能力测试*/
        if (navigator.geolocation)
        {
            /*1.获取地理信息成功之后的回调
            * 2.获取地理信息失败之后的回调
            * 3.调整获取当前地理信息的方式*/
            //navigator.geolocation.getCurrentPosition(success,error,option);
            /*option:可以设置获取数据的方式
            * enableHighAccuracy:true/false:是否使用高精度
            * timeout:设置超时时间，单位ms
            * maximumAge:可以设置浏览器重新获取地理信息的时间间隔，单位是ms*/
            navigator.geolocation.getCurrentPosition(showPosition,showError,{
                /*enableHighAccuracy:true,
                timeout:3000*/
            });
        }
        else{
            x.innerHTML="Geolocation is not supported by this browser.";
        }
    }
    /*成功获取定位之后的回调*/
    /*如果获取地理信息成功，会将获取到的地理信息传递给成功之后的回调*/
    // position.coords.latitude 纬度
    // position.coords.longitude 经度
    // position.coords.accuracy 精度
    // position.coords.altitude 海拔高度
    function showPosition(position)
    {
        x.innerHTML="Latitude: " + position.coords.latitude +
                "<br />Longitude: " + position.coords.longitude;
    }
    /*获取定位失败之后的回调*/
    function showError(error)
    {
        switch(error.code)
        {
            case error.PERMISSION_DENIED:
                x.innerHTML="User denied the request for Geolocation."
                break;
            case error.POSITION_UNAVAILABLE:
                x.innerHTML="Location information is unavailable."
                break;
            case error.TIMEOUT:
                x.innerHTML="The request to get user location timed out."
                break;
            case error.UNKNOWN_ERROR:
                x.innerHTML="An unknown error occurred."
                break;
        }
    }
    getLocation();
</script>

</body>


# 注意点：iOS10.0之后需要https协议才能使用h5的地理定位功能。
 解决方案：可以使用百度的地理定位功能
 参考：https://www.cnblogs.com/AlanYT/p/6970777.html
```

## HTML5视频播放器

```javascript
##1.css样式
body {
    padding: 0;
    margin: 0;
    font-family: 'microsoft yahei', 'Helvetica', simhei, simsun, sans-serif;
    background-color: #F7F7F7;
}

a {
    text-decoration: none;
}
.playerTitle{
    width:100%;
    margin: 0 auto;
    line-height:100px;
    font-size: 40px;
    text-align: center;
}
.player{
    width: 720px;
    height: 360px;
    margin: 0 auto;
    background: url("../images/loading.gif") center no-repeat;
    background-size: cover;
    position: relative;
}
video{
    height:100%;
    margin: 0 auto;
    display: none;
}
.controls {
    width: 720px;
    height: 40px;
    position: absolute;
    left: 0px;
    bottom: -40px;
    background-color: #000;
}
.controls > .switch{
    width: 20px;
    height: 20px;
    display: block;
    font-size: 20px;
    color: #fff;
    position: absolute;
    left: 10px;
    top: 10px;
}
.controls > .expand{
    width: 20px;
    height: 20px;
    display: block;
    font-size: 20px;
    color: #fff;
    position: absolute;
    right: 10px;
    top: 10px;
}
.controls > .progress{
    width: 430px;
    height: 10px;
    position: absolute;
    left:40px;
    bottom:15px;
    background-color: #555;
}
.controls > .progress > .bar{
    width:100%;
    height:100%;
    border-radius: 3px;
    cursor: pointer;
    position: absolute;
    left: 0;
    top: 0;
    opacity: 0;
    z-index: 999;
}

.controls > .progress > .elapse{
    width:0%;
    height:100%;
    background-color: #fff;
    border-radius: 3px;
    position: absolute;
    left: 0;
    top: 0;
    z-index: 3;
}
.controls > .time{
    height: 20px;
    position: absolute;
    left:490px;
    top: 10px;
    color: #fff;
    font-size: 14px;
}

##2.html页面
<link rel="stylesheet" href="../css/font-awesome.css">
<link rel="stylesheet" href="../css/css.css">

<h3 class="playerTitle">视频播放器</h3>
<div class="player">
    <video src="../mp4/chrome.mp4"></video>
    <div class="controls">
        <a href="javascript:;" class="switch fa fa-play"></a>
        <a href="javascript:;" class="expand fa fa-expand"></a>
        <div class="progress">
            <!--bar是透明的，主要作用用来控制拖动-->
            <div class="bar"></div>
		   <!--elapse主要用来显示已经播放的进度-->
            <div class="elapse"></div>
        </div>
        <div class="time">
            <span class="currentTime">00:00:00</span>
            \
            <span class="totalTime">00:00:00</span>
        </div>
    </div>
</div>
<script src="../js/jquery.min.js"></script>

##3.js
<script>
    /*通过jq来实现功能*/
    $(function(){
        /*1.获取播放器*/
        var video=$("video")[0];

        /*2.实现播放与暂停*/
        $(".switch").click(function(){
            /*实现播放与暂停的切换：如果是暂停>>播放  ，如果是播放 >> 暂停*/
            if(video.paused){
                video.play();
                /*移除暂停样式，添加播放样式*/
            }
            else{
                video.pause();
                /*移除播放样式，添加暂停样式*/
            }
            /*设置标签的样式  fa-pause:暂停   fa-play：播放*/
            $(this).toggleClass("fa-play fa-pause");
        });

        /*3.实现全屏操作*/
        $(".expand").click(function(){
            /*全屏>>不同浏览器需要添加不同的前缀>>能力测试*/
            if(video.requestFullScreen){
                video.requestFullScreen();
            }
            else if(video.webkitRequestFullScreen){
                video.webkitRequestFullScreen();
            }
            else if(video.mozRequestFullScreen){
                video.mozRequestFullScreen();
            }
            else if(video.msRequestFullScreen){
                video.msRequestFullScreen();
            }
        });

        /*4.实现播放业务逻辑：当视频文件可以播放时触发下面的事件*/
        video.oncanplay=function(){
            setTimeout(function(){
                /*1.将视频文件设置为显示*/
                video.style.display="block";
                /*2.获取当前视频文件的总时长(以秒做为单位，同时获取了小数值)，计算出时分秒*/
                var total=video.duration; //01:01:40   00:00:36
                /*3.计算时分少  60*60=3600*/
                var result=getResult(total)
                /*4.将计算结果展示在指定的dom元素中*/
                $(".totalTime").html(result);
            },2000);
        }

        /*通过总时长计算出时分秒*/
        function getResult(time){
            var hour=Math.floor(time/3600);
            /*补0操作*/
            hour=hour<10?"0"+hour:hour;
            var minute=Math.floor(time%3600/60);
            minute=minute<10?"0"+minute:minute;
            var second=Math.floor(time%60);
            second=second<10?"0"+second:second;
            /*返回结果*/
            return hour+":"+minute+":"+second;
        }

        /*5.实现播放过程中的业务逻辑，当视频播放时会触发ontimeupdate事件
        * 如果修改currentTime值也会触发这个事件，说白了，只要currenTime值变化，就会触发这个事件*/
        video.ontimeupdate=function(){
            /*1.获取当前的播放时间*/
            var current=video.currentTime;
            /*2.计算出时分秒*/
            var result=getResult(current);
            /*3.将结果展示在指定的dom元素中*/
            $(".currentTime").html(result);
            /*4.设置当前播放进度条样式  0.12>>0.12*100=12+%>12%*/
            var percent=current/video.duration*100+"%";
            $(".elapse").css("width",percent);
        }

        /*6.实现视频的跳播*/
        $(".bar").click(function(e){
            /*1.获取当前鼠标相对于父元素的left值--偏移值*/
            var offset= e.offsetX;
            /*2.计算偏移值相对总父元素总宽度的比例*/
            var percent=offset/$(this).width();
            /*3.计算这个位置对应的视频进度值*/
            var current=percent*video.duration;
            /*4.设置当前视频的currentTime*/
            video.currentTime=current;
        });

        /*7.播放完毕之后，重置播放器的状态*/
        video.onended=function(){
            video.currentTime=0;
            $(".switch").removeClass("fa-pause").addClass("fa-play");
        }
    });
</script>


#注意点：这边不要直接在webstorm中打开网页。否则不能拖动
```

## H5兼容处理（理解）

​	在不支持HTML5新标签的浏览器里，会将这些新的标签解析成行内元素(inline)对待，所以我们只需要将其转换成块元素(block)即可使用，但是在IE9版本以下，并不能正常解析这些新标签，但是却可以识别通过document.createElement('tagName')创建的自定义标签。

```javascript
//1. IE9会将这些新的标签解析成行内元素(inline)对待，所以我们只需要将其转换成块元素(block)即可使用
article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,video{display:inline-block;*display:inline;*zoom:1}audio:not([controls]){display:none;height:0}[hidden]{display:none}html{font-size:100%;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}html,button,input,select,textarea{font-family:sans-serif}body{margin:0}a:focus{outline:thin dotted}a:active,a:hover{outline:0}h1{font-size:2em;margin:.67em 0}h2{font-size:1.5em;margin:.83em 0}h3{font-size:1.17em;margin:1em 0}h4{font-size:1em;margin:1.33em 0}h5{font-size:.83em;margin:1.67em 0}h6{font-size:.67em;margin:2.33em 0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:700}blockquote{margin:1em 40px}dfn{font-style:italic}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}mark{background:#ff0;color:#000}p,pre{margin:1em 0}code,kbd,pre,samp{font-family:monospace,serif;_font-family:'courier new',monospace;font-size:1em}pre{white-space:pre;white-space:pre-wrap;word-wrap:break-word}q{quotes:none}q:before,q:after{content:'';content:none}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-.5em}sub{bottom:-.25em}dl,menu,ol,ul{margin:1em 0}dd{margin:0 0 0 40px}menu,ol,ul{padding:0 0 0 40px}nav ul,nav ol{list-style:none;list-style-image:none}img{border:0;-ms-interpolation-mode:bicubic}svg:not(:root){overflow:hidden}figure{margin:0}form{margin:0}fieldset{border:1px solid silver;margin:0 2px;padding:.35em .625em .75em}legend{border:0;padding:0;white-space:normal;*margin-left:-7px}button,input,select,textarea{font-size:100%;margin:0;vertical-align:baseline;*vertical-align:middle}button,input{line-height:normal}button,select{text-transform:none}button,html input[type=button],input[type=reset],input[type=submit]{-webkit-appearance:button;cursor:pointer;*overflow:visible}button[disabled],html input[disabled]{cursor:default}input[type=checkbox],input[type=radio]{box-sizing:border-box;padding:0;*height:13px;*width:13px}input[type=search]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration{-webkit-appearance:none}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}textarea{overflow:auto;vertical-align:top}table{border-collapse:collapse;border-spacing:0}html{overflow:hidden}a{text-decoration:none}img{display:block}ul,li{list-style:none;margin:0;padding:0}

//2.IE8之下不支持这些标签
第一种方式：通过document.createElement("header");创建这些标签
第二种方式：通过<script src="js/html5shiv.min.js"></script>引入第三方插件
```

```html
<!--[if lt IE 9]>
　　 <script src="js/respond.js"></script>
 　　<script src="js/html5shiv.min.js"></script>
<![endif]—>

//respond.js  目的是为了解决 ie低版本的CSS3媒体查询  media query
```

```html
//条件注释 了解
<!--[if !IE]><!--> 除IE外都可识别 <!--<![endif]-->
<!--[if IE]> 所有的IE可识别 <![endif]-->
<!--[if IE 6]> 仅IE6可识别 <![endif]-->
<!--[if lte IE 6]> IE6以及IE6以下版本可识别 <![endif]-->
<!--[if gte IE 6]> IE6以及IE6以上版本可识别 <![endif]-->
<!--[if IE 7]> 仅IE7可识别 <![endif]-->
<!--[if lt IE 7]> IE7以下版本可识别 <![endif]-->
<!--[if gt IE 7]> IE7以上版本可识别 <![endif]-->
<!--[if IE 8]> 仅IE8可识别 <![endif]-->
<!--[if IE 9]> 仅IE9可识别 <![endif]-->
```



<img src="media/html1.jpg" />

## 移动设备调试

### 模拟调试

​	现代主流浏览器均支持移动开发模拟调试，通常按F12可以调起，其使用也比较简单，可以帮我们方便快捷定位问题。

### 真机调试

​	模拟调试可以满足大部分的开发调试任务，但是由于移动设备种类繁多，环境也十分复杂，模拟调试容易出现差错，所以真机调试变的非常必要。

​	有两种方法可以实现真机调试：

​	1、 将做好的网页上传至服务器或者本地搭建服务器，然后移动设备通过网络来访问。（重点）

​		注意关闭windows防火墙。需要确保手机和电脑在同一个wifi下面。

​	2、上面调试方案的缺点是只能通过手机查看页面，并不能支持样式的修改

​		借助第三方的调试工具，如weinre、debuggap、ghostlab(比较)等

​		真机调试必须保证移动设备同服务器间的网络是相通的。

```
Ghostlab的使用：
a．安装，因为需要收费，试用期过了之后可以卸载重装
b．点击+号，添加项目，点击启动图标，打开扫描页面,用手机扫一扫，就可以在手机端查看网页了
c．点击ghostlib中对应设备的Inspect this client，支持联机调试
```

### 手机共屏

​	安装itools，找到工具箱-->苹果录屏大师-->打开

​	在手机端打开 苹果镜像 -->选择对应的设备共屏

​	注意点：手机和电脑的共屏是通过网络连接完成的，所以需要确保手机和电脑在同一网段下，确保电脑的防火墙关闭。