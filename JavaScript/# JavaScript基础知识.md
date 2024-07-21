# JavaScript基础知识

## 1. JavaScript输出
JavaScript可以通过不同方式输出数据：
- `window.alert()`: 弹出警告框
- `document.write()`: 将内容写入HTML文档
- `innerHTML`: 写入HTML元素
- `console.log()`: 写入浏览器控制台

## 2. JavaScript语法
- JavaScript是一种脚本语言
- 使用`var`、`let`或`const`关键字定义变量
- 使用等号`=`为变量赋值

## 3. JavaScript语句
- JavaScript语句是发送给浏览器的命令
- 语句通常以分号`;`结尾
- 代码块用`{}`包围

## 4. JavaScript注释
- 单行注释：`// 这是单行注释`
- 多行注释：`/* 这是多行注释 */`

## 5. JavaScript变量
- 变量是存储信息的容器
- 声明变量：`var x;`、`let y;`或`const z = 5;`
- 变量类型：
  - 数值（整数或浮点数）
  - 字符串
  - 布尔值
  - 数组
  - 对象
  - Undefined
  - Null

## 6. JavaScript数据类型
- 数值：`var length = 16;`
- 字符串：`var lastName = "Johnson";`
- 布尔值：`var x = true;`
- 数组：`var cars = ["Saab", "Volvo", "BMW"];`
- 对象：`var person = {firstName:"John", lastName:"Doe"};`
- Undefined：`var car;`
- Null：`var person = null;`

## 7. JavaScript运算符
- 算术运算符：`+`, `-`, `*`, `/`, `%`, `++`, `--`
- 赋值运算符：`=`, `+=`, `-=`, `*=`, `/=`, `%=`
- 比较运算符：`==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`
- 逻辑运算符：`&&`, `||`, `!`

## 8. JavaScript条件语句
- if 语句
```javascript
if (condition) {
  // 代码块
} else if (condition) {
  // 代码块
} else {
  // 代码块
}
```
- switch 语句
```javascript
switch(expression) {
  case x:
    // 代码块
    break;
  case y:
    // 代码块
    break;
  default:
    // 代码块
}
```

## 9. JavaScript循环
- for 循环
```javascript
for (let i = 0; i < 5; i++) {
  // 代码块
}
```
- while 循环
```javascript
while (condition) {
  // 代码块
}
```
- do...while 循环
```javascript
do {
  // 代码块
} while (condition);
```

## 10. JavaScript函数
- 函数定义
```javascript
function name(parameter1, parameter2, parameter3) {
  // 代码块
}
```
- 函数表达式
```javascript
const x = function(a, b) {return a * b};
```
- 箭头函数
```javascript
const x = (a, b) => a * b;
```

## 11. JavaScript对象
- 对象定义
```javascript
const person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
```

## 12. JavaScript事件
常见事件：
- `onclick`: 当用户点击某个对象时调用的事件句柄
- `onload`: 一张页面或一幅图像完成加载
- `onsubmit`: 确认按钮被点击
- `onmouseover`: 鼠标移到某个对象上
- `onmouseout`: 鼠标从某个对象移开

## 13. JavaScript字符串方法
- `length`: 返回字符串的长度
- `indexOf()`: 检索字符串
- `slice()`: 提取字符串的片断
- `replace()`: 替换字符串
- `toUpperCase()`: 转换大写
- `toLowerCase()`: 转换小写
- `concat()`: 连接字符串

## 14. JavaScript数组方法
- `push()`: 向数组的末尾添加一个或更多元素
- `pop()`: 删除数组的最后一个元素
- `shift()`: 删除并返回数组的第一个元素
- `unshift()`: 向数组的开头添加一个或更多元素
- `splice()`: 添加或删除数组中的元素
- `slice()`: 选取数组的一部分，并返回一个新数组
- `forEach()`: 数组每个元素都执行一次回调函数

## 15. JavaScript错误处理
```javascript
try {
  // 可能会导致错误的代码
}
catch(err) {
  // 错误处理
}
finally {
  // 无论是否有错误发生都会执行的代码
}
```

这个概览涵盖了JavaScript的主要基础知识。每个主题都可以进一步展开和深入。您是否希望我详细解释其中的某个特定部分？