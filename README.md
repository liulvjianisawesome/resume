
## 教育经历  
2012/9-2016/6 就读于湖南大学(985)软件院的数字媒体技术专业  
## 学历  
全日制本科 学士学位  英语四级  
## 联系方式
- 联系电话：15575918345
- Email：634098330@qq.com
- 微信：llj8714300
## 个人信息  
- 刘吕健 男 23岁

- 工作经验：一年

- 目前状态： 离职，正在找工作

- 居住地点： 深圳市龙岗区坂田街道

- 应聘职位：前端开发工程师

- 期望薪资：月薪6k以上

- 期望工作地点：深圳

- Github：https://github.com/q123321

## 工作经历
#### 中软国际科技服务有限公司（2016年6月到2017年3月）
- 工作描述： 
## 项目作品
#### 京东云首页
- 对京东云首页进行了还原，基于 react 和 redux 构建 ，采用 es6 语法，用了 class 类、解构赋值、箭头函数、函数默认值、块级作用域等知识。使用 npm、webpack 作为自动化构建工具 es6 转 es5、打包合并代码。
- 在动手开发之前发现京东云首页有非常多html结构完全一样的模块，所以决定使用react进行开发把结构相同的模块组件化，这样一来页面结构变得非常清晰并且实现了代码的复用。开发过程中发现不同的react组件之间往往需要使用对方的数据，所以使用redux来进行组件间的交流。
- 首页的轮播图部分会加载几张很大的超清图片，在网速不够快时会加载的很慢很影响体验，所以对于轮播图中的图片采用了按需加载的方式，大大提高了网页加载的速度。页面中有大量的图片，每一个图片都会发出一个请求极大的拖慢了页面的加载速度。观察发现这些图片大部分都是纯色图片，阿里巴巴矢量图标库把这些图片打包到一个字体文件中，引入该字体文件即可，大大减少了图片请求的数量。
- 适当地添加了一些css3动画使得页面的交互更加流畅、美观。
- [预览地址](https://q123321.github.io/JDcloud/build/index.html)
#### 网页计算器
- 一个网页版的计算器应用，用户通过电击按钮输入自己想要计算的算式，按下=按钮后得到计算后的值。
- 一个算式可以拆分成很多子算式，不同的子算式计算的优先级不同，而括号中的算式优先级最高。先使用正则匹配括号中的算式，然后正则匹配括号中优先级高的子算式并计算，全部计算完之后再正则匹配优先级低一级的子算式并计算，以此类推计算出所有子算式后得到括号中的结果。把所有括号中的算式算完了后得到一个没有括号的算式，同样按照优先级从高到低计算得到结果。
- 测试时发现错误的输入会引发程序报错或者得到奇怪的结果，所以对输入的算式再计算前进行合法性校验以保证输入的算式是合法的。
- [预览地址](https://q123321.github.io/calculator/calculator.html)


