# 十天总结
思考：这10天我有没有一点进步？
目标：要把UOLab的网页界面做出来（文字的需求，编程图形化的界面）
技术：HTML、CSS、JavaScript、Bootstrap，分别能做什么？ 我们学单一技术不行，要学N种技术，整合使用，才能做出项目。
工具：Chrome（调试JS）、HBuider9（Mac用户，下载HBuilderX）
自己每天投入学习技术和做东西的时间，几个小时？进步情况如何？
哪些东西不懂？问老师；哪些不熟练？在家里多动手做。
能够对企业做法有所了解、岗位、行业、职业发展等等、大学规划有所启发。
后期学习建议
定目标，做规划，行动
前端技术未涉及的
JSON **
Layui **
ECharts **
jQuery **
WebStorm **
Vue.js **
Node.js
LESS
SASS
Flex布局
HTML5
CSS3
后端：前后端分离微服务架构开发 按发过去的路线图和清单来学习即可。需要提前学。
走安全方向的 学习安全相关知识，很多，需要提前学。

# Lesson10—周四（7.22）
## 排错  
1）打开Chrome的控制台console，看里面有没有自己代码报错(点一点，动一动网页)  
2）如果有报错，根据错误提示，排错   
3）如果没有报错，还是代码有问题，一行一行检查代码  
## 导出Excel和ECharts怎么弄  
导出需要Java后端支持；需要专门学习ECharts的使用
# Lesson9—周三（7.21）
## 任务：按需求，完成原型的开发（复制 粘贴）
## 学会知识点
1. HTML表单（文本框、下拉列表、单选按钮、按钮  
2. HTML表格  
3. HTML图片  
4. HTML超链接  
5. CSS的选择器（id、class）  
6. 什么是真正学会？    
会用、会做。学过了，知道了，但用不起来，算是没学！  
# Lesson8—周二（7.20）
## 工作任务：开发《UOLab联合开放实验室管理体系》项目原型（界面）
1. 提供美工做的模板  
2. 学会如何在模板基础上改，把项目功能放在模板上
3. 大二第2学期，做Java Web项目；一定会用到这次学的技术  
大三第1学期，做SSM框架的项目；也会用到这次学的技术  
做Java研发工程师、Web前端开发工程师的话，一定会用  
# Lesson7—周一（7.19）
##  前天问题总结：
### 一、技术问题
1. 计算利息的时候，得到的是小数，位数很多

计算机算的时候时用的2进制；我们填的是10进制
在二进制转向十进制的时候会产生误差（百度解决）
2. 写完代码以后，点一下按钮没有反应
1）打开Chrome的控制台console，看看里面有无红色的报错，根据提示，排错
2）如果console里没有报错，只能一行行检查
3. 如果不输入也能算会输出NAN 使用JS表单验证
 ### 二、其他问题：

1. 坚决不要排斥这个专业！

1）耐心认真的一行一行查代码
2）找人带
3）学编程时，视频不能为主导，尤其是没有开发经验的人
4）保持自信，坚持到底  
2. 建议：下学期除了考试，一定要学习项目技术和项目的开发上
3. 如何排错  
1）排错没有捷径，没有秘籍
2）要看错误提示，根据提示改代码
3）看到提示不会改错，找人帮忙
## 表单验证
在公司开发中要使用正则表达式、JS函数、DOM  
在存款计算器中，用到了：onfoucus（获得焦点）  
document.getElementById("对于id的名称").value="";表示为释放空间	  
document.getElementById("对于id的名称").style="color：black";表示对于样式的改变  
定义正则表达式：   
var regExp =/^[0-9]{2,6}$/;//（定义^开头$结尾）  
[0-9]表示是数字{2， 6}表示最小为两位最大为六位{}表示数字的位数  
regExp.test(abc)表示两者进行匹配比较  

# Lesson6—周六（7.17）
## 昨天总结
1. 我的图片GitHub不显示  
 图片没上传，路径不对，GitHub较慢
2. GitHub访问较慢如何解决  
 解决方法在群里
 ## 一.JavaScript重要性  
 1. 对于Java研发工程师是必须的，要熟练开发
 2. 对于Web前端开发工程师，JavaScript必须要深入、精通。这个岗位使用 开发语言就是JavaScript  
 3. 对于大数据工程、爬虫工程师等：JavaScript也是需要掌握。
## 二.JavaScript语言与c语言有关系？
1. 没有关系，两种独立的语言
2. 有相似语法，不代表有关系
## 三.不同的编程语言应用场景
1. c语言  
（强调算法、数据结构） 面向过程的。主要用于：智能硬件设备上的软件开发（嵌入式）、操作系统底层开发、 算法等。安卓手机的底层就是C开发的、Windows的底层也用C开发。偏底层应用。
2. c++语言  
    面向对象的。主要用于：图形界面软件开发（美图秀秀、PS、酷狗音乐等）、通信 软件（QQ、钉钉）、游戏、控制软件（带有图形界面的控制软件）、STM32开发（嵌入式）
3. Java语言  
 不太强调算法、数据结构，Java的数据结构是现成的。 面向对象的。主要用于：基于B/S结构的大型管理信息系统开发（12306、教务系统、四六报名系统等）、 大数据开发（Hadoop）、安卓手机应用开发、智能电子设备软件开发（数字电视机顶盒）
4. python语言  
   python2和python3。胶水语言，什么都能干，全能型选手。主要用于： 信息安全编程、爬虫、大数据分析、AI等。
5. JavaScript语言   
JavaScript语言 面向对象的。脚本语言，运行在浏览器上。主要：网页上的动态效果、网页和用户的交互等
## 四.JavaScript是什么？  
脚本语言，运行在浏览器中，也就是运行在客户机中。各种浏览器都能执行JS， 但是不同的浏览器对JS的支撑程度不尽相同。进行浏览器的兼容性测试。 JavaScript不是W3C的标准，由欧洲计算机制造商协会。 HTML、CSS、JS都是由浏览器执行的。

## 六. 上网的过程
1. B/S结构：Browser/Server 浏览器/服务器，如教务系统  
2. C/S结构：Client/Server 客户机/服务器 ，如qq  
3. 单机软件：如：Word，在自己电脑上安，只能自己用。
4. 上网过程分析 以12306为例  
输入网址，敲下回车：浏览器向12306的服务器发出请求
响应：服务器收到浏览器请求后，服务器会把保存在服务器上的网页源码， 发回给浏览器。
浏览器在收到源码后，对源码执行，产生最终的显示效果。 
## 七.JavaScript学习重要提醒  
JS调试比较麻烦：JS程序的调试要利用Chrome或Firefox的控制台
写JS程序一定要细心，一旦写错排错真的比较难（针对初学者）
## 八.JavaScript学习重点（公司开发重点）
1. 语法（if、for、运算符等等）  
2. 函数  
3. 事件  
4. 正则表达式与表单验证  
5. DOM  
## 九.JS输出（作用：便于调试JS代码）
1. alert()  
2. console.log()  
补充：JS代码放在什么地方？ 网页内部；单独的.js文件中  
## 十. JS语法
1. JS是弱类型语言（没有类型）
2. JS中变量定义可以用var也可不用
3.  JS语言大小写敏感（严格区分大小写）
4. 语句结尾分号可以写，也可不写
5. JS函数用function，函数名程序员自定、函数的形参由程序员自定，JS中 的函数没有返回类型6. （因为JS是弱类型语言）
6. 编程时候，不要上来就写代码，先整理思路，确定实现步骤；
把实现步骤，写成代码
## 十一、排错（大学学习中最麻烦的地方、开发中最重要的地方）
写代码容易，排错费劲
仔细分析自己的代码，看哪里写错了，这个过程可能较长，但我们要经历！ 经历了，涨经验了，下次同样的错就容易排除了。
排错能力是大学生一定解决的！如何提升该能力？多写代码，多出错，累经验。 排错需要经验。公司招聘：要求有项目开发经验了。
大家不要放弃！缺乏经验，没人指导。借助过来人或能行的人的力量，帮自己提升。
# Lesson5—周五（7.16）

## 昨天问题总结
1. 我在原来的网页上加入Bootstrap样式以后，对不齐了。
如果要使用Bootstrap样式，建议所有的地方都用Bootstrap样式。
   Bootstrap追求的是自适应，不太讲究美观
2. 网页上传到github后，图片不显示
   在网页代码里，src后带有目录，比如：<img src="images/weixin.png">;
   但是在github上没有建images目录，而是把图片直接上传了，因此图片不能显示
   理解了，再去做。解决方案：在github上建目录，把图片上传到目录里。
3. 图片路径也对，但图片不显示
   原来图片路径不对，但改了后又上传了，刷新网页，没变化。github滞后导致，
   过一阵再刷新。
4.  公司工作需要的必须的专业技能到底有哪些
   建议：
      1. 知道读大学（本科，硕士，博士）目的何在？
   
       工作！目的：积累找到工作的资本，技术+能力；文凭
    2. 在这个暑假就要明确未来做什么岗位？
       不同的岗位学习不同的技术。
       Java研发工程师、C/C++开发工程师、Web前端开发工程师、
       信息安全工程师、嵌入式开发工程师、UI设计工程师、
       实施工程师、售前工程师、需求分工程师
    3. 误区：编程语言学好了，就能找工作了！错！
           应当下大功夫学的是：围绕语言的一系列技术
    4. zhaopin.com:招聘的岗位要什么技术，我就学什么！
## 一. Bootstrap表格
class="table table-bordered text-center table-striped"

table-striped添加斑马线形式的条纹

二、任务：个人存款计算软件界面
三、任务：个人社保计算软件界面
为JS提供帮助,为后面去实现代码的操作

编程技术学习方法：
1、敢于面对问题。先思考，再百度，问同学和老师
2、要灵活！不能死板，不要照搬，抄写
3、不看书，不看老师代码，不看视频，自己写出代码
4、先理解，弄懂，再写；
5、专注并且敏锐
6、不要过度依赖网络视频，参考！

# Lesson4—周四（7.15）

## 上一天技术总结
1. CSS选择器  

     （标记、id、class）

2. CSS代码放置位置

3. 边框样式

4. 工作后 网页是在美工（UI）的基础上开发后端程序

5. 怎么样把自己做的网页给其他人看（公网访问）
   开发网页
   购买云主机Linux系统（阿里云主机），获得一个IP地址。
   把做好的网页远程上传到主机（此时就可以通过IP来访问了） 
   百度搜索域名注册，注册一个域名：域名在工信部通管局备案 取得备案号：把自己的域名和IP做绑定，通过主机完成：部分网站需要在公安局备案 此时，网站就可以通过域名来访问。
## 一.CSS显示
1. display：none 隐藏后，释放区域。
2. visibility：hidden 隐藏后，区域不释放
## 二.CSS浮动
1. 美工精通
2. 主要用于网页布局（CSS + DIV）

## 三.Bootstrap技术
###   1.介绍
Twitter公司发明的技术
用Bootstrap做的网页，能狗自动适应屏幕大小（自适应，响应式）
移动优先（Bootstrap伴随着智能手机而来）
Bootstrap技术是基于：HTML、CSS、JavaScript
Bootstrap本质：写好的CSS样式库（拿来就用）
Bootstrap不是编程语言，是一种技术。
### 2. Bootstrap如何使用
第1种 把Bootstrap文件从官网下载下来，复制到自己的项目里
第2种 直接使用CDN（内容分发网络，其实就是放在公网上的文件） 如果使用CDN方式，电脑必须联网。
### 3. 如何学Bootstrap
看官方文档。
### 4.Bootstrap工作原理是啥？
网格系统（屏幕分成12列，使用者可以按自己需要组合列）
使用Bootstrap后，CSS样式就不用我们自己写了；直接用即可
## 四. 如何在GitHub上搭建静态网站
注册GitHub账号
创建一个项目
把写好的网页上传到项目里
在设置中找到pages，点击main，点save	
# Lesson3—周三（7.14）
## 一. CSS是什么
层叠式样式表，简称为样式。(Cascading Style Sheets)（W3C制定）
最新版css3
## 二.CSS选择器（*****）
标记选择器
id选择器
class选择器
## 三.CSS放置的位置
页内样式：放在head之间，用style标记
行内样式：放在标记的style属性里，行内样式优先级最高
外部样式：放在独立的.css文件中，在网页上用link标记引入
## 四.开发常用样式
1. 背景颜色  
    background-color
2. 文本样式  
   color\text-align\text-decoration
3. 字体样式  
    font-family\font-size
   网页是默认是16px；工程上一般是12px或者14px；
4. 链接样式  
	细线表格border-collapse：collapse（折叠）
5. 表格样式
	边框变红 border:1px solid red
## 五.CSS盒子模型 
美工必须精通
开发工程师理解并会用
重要：外边距margin、内边距padding;（内外边距有参考对象 是相对的）
## 六.登录网页
用到了盒子模型（内部外部边距等）
HTML表单元素（用户名，密码，登录按钮）
# Lesson2—周二(7.13)
## 总结
1. HTML只能做网页结构，大小写不区分，由浏览器执行
2. 开发重点：表单、表格、超链接、图片、列表、iframe
3. 学到什么程度就达标了？能把第2"写"出来
4. 对开发人员的用途：做项目的界面
## 、一.html表格
```html
<table></table>表格标记
<tr></tr>表格行、
<td></td>表格列
在<table>里放<tr>,在<tr>里放<td>！！！
<td colspan="x"></td> 合并x列
```

## 二.html超链接
1. 可以是到自己的网站,也可以到外部网站
  
2. 语法
```html
<a href="链接"></a>
```
## 三.html 图片
```html
	<img src="" width="" heigth="">
```
## 四.html 列表
```html
	有序列表<ol></ol>
	无序列表<ul></ul>
	<li> abc <li>列表项  
	<hr>一条分界线
```
## 五.标题
HTML中共6级标题；从h1-h6
		<h1>中北大学</h1>
		<h2>软件学院</h2>
		<h3>暑期小假期</h3>  
		
## 六.段落与div块
段落p：会自动换行
块div ：会自动换行
span:不会自动换行的
label：不会自动换行
```html
		<p>这是一个段落</p>
		<div>这是一个块</div>
		<span>密码必须是6位</span>
		<span>用户名不为空</span>
		<label>这个是标签 中北大学</label>
```
## 七.html颜色
颜色表示两种：1.用颜色名；2.颜色的值（主要用它）,是16进制，以#开头
颜色是由3种色调配而成：RGB（red、green、blue）
做网页的在公司里是网页美工或UI工程师；
我们开发人员不去做网页，更不会去做网站。我们需要能看懂他们的。
## 八.字符实体
面试题：HTML里的空格怎么表示 &nbsp；
## 九. iframe框架(常用)
## 高频面试题
post与get的区别  
 1. post方式提交表单，表单数据在地址栏不显示，比较安全
      get方式提交表单，数据会显示在地址栏上，不安全
   
2. post提交数据，数据量大小不限；get一般最大为2K，  一般使用post。
# lesson1—周一(7.12)
##  问题总结  
1.代码格式规范不清晰  
没有了解 提交按钮和跳转按钮的区别
## 一.htlm介绍  
1. htlm是什么（5w1h）      
   超文本标记语言 最新htlm5    
2. 为什么用  		why    
    web项目界面  
3. 谁来用    		who    
后端开发人员一定要会、Web前端开发工程师、网页美工（UI）  
4. 什么时候用   	when  
5. 用在哪里  		where  
 网页上搭建网页结构或元素
6. 怎么用 		how   
## 二.HTML表单开发  
 1.文本框怎么写      
 ```htlm    
 <input type="text" ><br>  
 ```
 2.密码框怎么写？    
 ```htlm  
 <input type="password">  
 ```
 3.单选按钮怎么写？    
 ```htlm
 	<input type="radio" >
	<input type="radio" ><br>	
 ```
 4.下拉选择怎么写？   
 ```htlm  
 		<select>  
		<option>abc</option>  
		<option>abc</option>  
		<option>abc</option>  
		</select><br>  
 ```
 5.复选框怎么写？    
 ```htlm  
 		<input type="checkbox">abc   (abc 为举例)
		<input type="checkbox">abc  
		<input type="checkbox">abc<br>  
 ```
 6.文本域怎么写？    
 ```htlm  
 	<textarea row="5" cols="50">  
					abc  
	</textarea><br>  
 ```
 7.文件上传怎么写？   
 ```htlm  
 	<input type="file">  
 ```
 8.提交按钮怎么写？
 ```htlm  
 	<input type="submit" value="abc"><!--acb会呈现在按钮上 -->
 ```
 9.重置按钮怎么写？  
 ```htlm  
 	<input type="reset" value="abc">
 ```
 10.如何跳转网页？ 
 ```htlm  
 	<form action="receive.html">
 	<input type="submit" value="注册">
 	</form>
 ```