# CSS 基础语法
##CSS id 和 class
###id
id 选择器可以为标有特定 id 的 HTML 元素指定特定的样式。
HTML元素以id属性来设置id选择器,CSS 中 id 选择器以 "#" 来定义。
###class
class 选择器用于描述一组元素的样式，class 选择器有别于id选择器，class可以在多个元素中使用。
class 选择器在 HTML 中以 class 属性表示, 在 CSS 中，类选择器以一个点 . 号显示：
##css创建
插入样式表的方法有三种:
外部样式表(External style sheet)
内部样式表(Internal style sheet)
内联样式(Inline style)

### 外部样式表
当样式需要应用于很多页面时，外部样式表将是理想的选择。在使用外部样式表的情况下，你可以通过改变一个文件来改变整个站点的外观。每个页面使用 <link> 标签链接到样式表。 <link> 标签在（文档的）头部：
浏览器会从文件 mystyle.css 中读到样式声明，并根据它来格式文档。
外部样式表可以在任何文本编辑器中进行编辑。文件不能包含任何的 html 标签。样式表应该以 .css 扩展名进行保存。

###内部样式表
当单个文档需要特殊的样式时，就应该使用内部样式表。可以使用 <style> 

###内联样式
由于要将表现和内容混杂在一起，内联样式会损失掉样式表的许多优势。请慎用这种方法，例如当样式仅需要在一个元素上应用一次时。
要使用内联样式，你需要在相关的标签内使用样式（style）属性。Style 属性可以包含任何 CSS 属性。本例展示如何改变段落的颜色和左外边距：

###多重样式优先级
样式表允许以多种方式规定样式信息。样式可以规定在单个的 HTML 元素中，在 HTML 页的头元素中，或在一个外部的 CSS 文件中。甚至可以在同一个 HTML 文档内部引用多个外部样式表。
一般情况下，优先级如下：
（内联样式）nline style > （内部样式）Internal style sheet >（外部样式）External style sheet > 浏览器默认样式

##css 背景
background	简写属性，作用是将背景属性设置在一个声明中。
background-attachment	背景图像是否固定或者随着页面的其余部分滚动。
background-color	设置元素的背景颜色。
background-image	把图像设置为背景。
background-position	设置背景图像的起始位置。
background-repeat	设置背景图像是否及如何重复。

##css 文本属性
所有CSS文本属性。
属性	描述
color	设置文本颜色
direction	设置文本方向。
letter-spacing	设置字符间距
line-height	设置行高
text-align	对齐元素中的文本
text-decoration	向文本添加修饰
text-indent	缩进元素中文本的首行
text-shadow	设置文本阴影
text-transform	控制元素中的字母
unicode-bidi	设置或返回文本是否被重写 
vertical-align	设置元素的垂直对齐
white-space	设置元素中空白的处理方式
word-spacing	设置字间距

##css字体

Property	描述
font	在一个声明中设置所有的字体属性
font-family	指定文本的字体系列
font-size	指定文本的字体大小
font-style	指定文本的字体样式
font-variant	以小型大写字体或者正常字体显示文本。
font-weight	指定字体的粗细。

##css链接
链接样式
链接的样式，可以用任何CSS属性（如颜色，字体，背景等）。
特别的链接，可以有不同的样式，这取决于他们是什么状态。
这四个链接状态是：
a:link - 正常，未访问过的链接
a:visited - 用户已访问过的链接
a:hover - 当用户鼠标放在链接上时
a:active - 链接被点击的那一刻

当设置为若干链路状态的样式，也有一些顺序规则：
a:hover 必须跟在 a:link 和 a:visited后面
a:active 必须跟在 a:hover后面

##css表格
属性	描述
list-style	简写属性。用于把所有用于列表的属性设置于一个声明中
list-style-image	将图像设置为列表项标志。
list-style-position	设置列表中列表项标志的位置。
list-style-type	设置列表项标志的类型。

##css盒子模型
CSS 盒子模型(Box Model)
所有HTML元素可以看作盒子，在CSS中，"box model"这一术语是用来设计和布局时使用。
CSS盒模型本质上是一个盒子，封装周围的HTML元素，它包括：边距，边框，填充，和实际内容。
盒模型允许我们在其它元素和周围元素边框之间的空间放置元素。
下面的图片说明了盒子模型(Box Model)：

CSS box-model
不同部分的说明：
Margin(外边距) - 清除边框外的区域，外边距是透明的。
Border(边框) - 围绕在内边距和内容外的边框。
Padding(内边距) - 清除内容周围的区域，内边距是透明的。
Content(内容) - 盒子的内容，显示文本和图像。


##css尺寸
属性	描述
height	设置元素的高度。
line-height	设置行高。
max-height	设置元素的最大高度。
max-width	设置元素的最大宽度。
min-height	设置元素的最小高度。
min-width	设置元素的最小宽度。
width	设置元素的宽度。


##CSS Overflow
CSS overflow 属性可以控制内容溢出元素框时在对应的元素区间内添加滚动条。
overflow属性有以下值：
值	描述
visible	默认值。内容不会被修剪，会呈现在元素框之外。
hidden	内容会被修剪，并且其余内容是不可见的。
scroll	内容会被修剪，但是浏览器会显示滚动条以便查看其余的内容。
auto	如果内容被修剪，则浏览器会显示滚动条以便查看其余的内容。
inherit	规定应该从父元素继承 overflow 属性的值。

##css float
元素的水平方向浮动，意味着元素只能左右移动而不能上下移动。
一个浮动元素会尽量向左或向右移动，直到它的外边缘碰到包含框或另一个浮动框的边框为止。
浮动元素之后的元素将围绕它。
浮动元素之前的元素将不会受到影响。

##css 布局水平对齐
###元素居中对齐
要水平居中对齐一个元素(如 <div>), 可以使用 margin: auto;。
设置到元素的宽度将防止它溢出到容器的边缘。
元素通过指定宽度，并将两边的空外边距平均分配：
###文本居中对齐
如果仅仅是为了文本在元素内居中对齐，可以使用 text-align: center;
###图片居中对齐
要让图片居中对齐, 可以使用 margin: auto; 并将它放到 块 元素中:
###左右对齐 - 使用定位方式
我们可以使用 position: absolute; 属性来对齐元素:

注释：绝对定位元素会被从正常流中删除，并且能够交叠元素。
提示: 当使用 position 来对齐元素时, 通常 <body> 元素会设置 margin 和 padding 。 这样可以避免在不同的浏览器中出现可见的差异。

###左右对齐 - 使用 float 方式
###垂直居中对齐 - 使用 padding
###垂直居中 - 使用 line-height

###css组合选择器
CSS组合选择符包括各种简单选择符的组合方式。
在 CSS3 中包含了四种组合方式:
后代选择器(以空格     分隔)
子元素选择器(以大于 > 号分隔）
相邻兄弟选择器（以加号 + 分隔）
普通兄弟选择器（以波浪号 ～ 分隔）

##css伪类
所有CSS伪类/元素
选择器	示例	示例说明
:checked	input:checked	选择所有选中的表单元素
:disabled	input:disabled	选择所有禁用的表单元素
:empty	p:empty	选择所有没有子元素的p元素
:enabled	input:enabled	选择所有启用的表单元素
:first-of-type	p:first-of-type	选择的每个 p 元素是其父元素的第一个 p 元素
:in-range	input:in-range	选择元素指定范围内的值
:invalid	input:invalid	选择所有无效的元素
:last-child	p:last-child	选择所有p元素的最后一个子元素
:last-of-type	p:last-of-type	选择每个p元素是其母元素的最后一个p元素
:not(selector)	:not(p)	选择所有p以外的元素
:nth-child(n)	p:nth-child(2)	选择所有 p 元素的父元素的第二个子元素
:nth-last-child(n)	p:nth-last-child(2)	选择所有p元素倒数的第二个子元素
:nth-last-of-type(n)	p:nth-last-of-type(2)	选择所有p元素倒数的第二个为p的子元素
:nth-of-type(n)	p:nth-of-type(2)	选择所有p元素第二个为p的子元素
:only-of-type	p:only-of-type	选择所有仅有一个子元素为p的元素
:only-child	p:only-child	选择所有仅有一个子元素的p元素
:optional	input:optional	选择没有"required"的元素属性
:out-of-range	input:out-of-range	选择指定范围以外的值的元素属性
:read-only	input:read-only	选择只读属性的元素属性
:read-write	input:read-write	选择没有只读属性的元素属性
:required	input:required	选择有"required"属性指定的元素属性
:root	root	选择文档的根元素
:target	#news:target	选择当前活动#news元素(点击URL包含锚的名字)
:valid	input:valid	选择所有有效值的属性
:link	a:link	选择所有未访问链接
:visited	a:visited	选择所有访问过的链接
:active	a:active	选择正在活动链接
:hover	a:hover	把鼠标放在链接上的状态
:focus	input:focus	选择元素输入后具有焦点
:first-letter	p:first-letter	选择每个<p> 元素的第一个字母
:first-line	p:first-line	选择每个<p> 元素的第一行
:first-child	p:first-child	选择器匹配属于任意元素的第一个子元素的 <p> 元素
:before	p:before	在每个<p>元素之前插入内容
:after	p:after	在每个<p>元素之后插入内容
:lang(language)	p:lang(it)	为<p>元素的lang属性选择一个开始值

##css 伪元素
所有CSS伪类/元素
选择器	示例	示例说明
:link	a:link	选择所有未访问链接
:visited	a:visited	选择所有访问过的链接
:active	a:active	选择正在活动链接
:hover	a:hover	把鼠标放在链接上的状态
:focus	input:focus	选择元素输入后具有焦点
:first-letter	p:first-letter	选择每个<p> 元素的第一个字母
:first-line	p:first-line	选择每个<p> 元素的第一行
:first-child	p:first-child	选择器匹配属于任意元素的第一个子元素的 <p> 元素
:before	p:before	在每个<p>元素之前插入内容
:after	p:after	在每个<p>元素之后插入内容
:lang(language)	p:lang(it)	为<p>元素的lang属性选择一个开始值

##css 导航栏

##css 下拉菜单
HTML 部分：
可以使用任何的 HTML 元素来打开下拉菜单，如：<span>, 或 a <button> 元素。

使用容器元素 (如： <div>) 来创建下拉菜单的内容，并放在任何你想放的位置上。

使用 <div> 元素来包裹这些元素，并使用 CSS 来设置下拉内容的样式。

CSS 部分：

.dropdown 类使用 position:relative, 这将设置下拉菜单的内容放置在下拉按钮 (使用 position:absolute) 的右下角位置。

.dropdown-content 类中是实际的下拉菜单。默认是隐藏的，在鼠标移动到指定元素后会显示。 注意 min-width 的值设置为 160px。你可以随意修改它。 注意: 如果你想设置下拉内容与下拉按钮的宽度一致，可设置 width 为 100% ( overflow:auto 设置可以在小尺寸屏幕上滚动)。

我们使用 box-shadow 属性让下拉菜单看起来像一个"卡片"。

:hover 选择器用于在用户将鼠标移动到下拉按钮上时显示下拉菜单。


##css 提示工具

##css 图片廊

##css媒体类型
@media 规则
@media 规则允许在相同样式表为不同媒体设置不同的样式。

媒体类型	描述
all	用于所有的媒体设备。
aural	用于语音和音频合成器。
braille	用于盲人用点字法触觉回馈设备。
embossed	用于分页的盲人用点字法打印机。
handheld	用于小的手持的设备。
print	用于打印机。
projection	用于方案展示，比如幻灯片。
screen	用于电脑显示器。
tty	用于使用固定密度字母栅格的媒体，比如电传打字机和终端。
tv	用于电视机类型的设备。

##css 属性选择器
具有特定属性的HTML元素样式
具有特定属性的HTML元素样式不仅仅是class和id。

##css 表单
输入框(input) 样式
输入框填充
输入框(input) 边框
输入框(input) 颜色
输入框(input) 聚焦
输入框(input) 图标
带动画的搜索框
文本框（textarea）样式
下拉菜单（select）样式
按钮样式
响应式表单

##css 计时器
属性	描述
content	使用 ::before 和 ::after 伪元素来插入自动生成的内容
counter-increment	递增一个或多个值
counter-reset	创建或重置一个或多个计数器

##css 网页布局
网页布局有很多种方式，一般分为以下几个部分：头部区域、菜单导航区域、内容区域、底部区域。

##css ！important
什么是 !important
CSS 中的 !important 规则用于增加样式的权重。
!important 与优先级无关，但它与最终的结果直接相关，使用一个 !important 规则时，此声明将覆盖任何其他声明。
