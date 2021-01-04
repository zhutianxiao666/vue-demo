# vue-demo
public文件夹为测试用，包括案例

src为后期搭建脚手架用
# 1.核心
## 1.1基本认识
### 1.1.1官网
渐进式JavaScript框架

本身能做一部分工作，配合插件可以做的更多

特点：
 - 简单：知道html css js就可以使用vue
 - 灵活：具有渐进增量的生态系统，可以根据项目规模，在库和全特效框架之间灵活选择
 - 高效：20kb min+gzip 运行大小。超快虚拟dom。最省心的优化

### 1.1.2介绍描述
1.渐进式JavaScript框架

2.作者

3.作用 动态构建（显示）用户界面
### 1.1.3Vue的特点
1.遵循mvvm模式

2.编码简洁

3.它本身只关注ui可以轻松高效的引入vue插件或者其他库
### 1.1.4与其他js库的关联
1.借鉴react的组件化和虚拟dom

2.借鉴angular的模板和数据绑定技术
### 1.1.5Vue的扩展插件

1.vue-cli:vue脚手架

2.vue-resource(axios):ajax请求 // 现在基本都用axios

3.vue-router:路由

4.vuex:状态管理

5.vue-lazyload:图片懒加载

6.vue-scrollar:页面滑动相关

7.mint-ui:基于vue的ui组件库(移动端)

8.element-ui:基于vue的ui组件库(pc端)

## 1.2基本使用
### 1.2.1效果
查看文件01

模板语法：js+html

js以什么形式存在？

指令：vue自定义的标签属性（以v-开头），属性值是js的表达式

插值：{{msg}}，用来显示数据



### 1.2.2编码
```html
<div id="app">
    <input type="text" v-model="msg"> {{msg}}
    <p v-on:click="f1">aaccdddd</p>
    <div style="background: yellow;width: 100px;height: 100px"></div>

</div>
```
```javascript
new Vue({
    el: '#app',
    data: {
        msg: 'helloworld'
    },
    methods: {
        f1() {
            console.log(22)
        }
    }
})
```
### 1.2.3使用vue调试工具
vscode可以下载live server，右键Open width live server。可以自动刷新
给谷歌浏览器添加一个扩展。可以在github中下载vue-devtools
### 1.2.4理解vue的mvvm
m->model 模型：data;v=>view 视图 DOM;

VM->DOM\data(视图模型):Date Bindlings 数据绑定 Dom Listeners dom监听

## 1.3模板语法
## 1.4计算属性和监视
computed watch

数据监视的原理

1.对象中的属性值给对象添加setter方法

2.数组中的元素数组
重写（重新定义）数组的一系列方法

调用方法时更新数组，同时更新界面

## 1.5class与style绑定

### 1.5.1效果


### 1.5.2理解
改变class和style绑定的内容
### 1.5.3class绑定
:class="
### 1.5.4style绑定
:style=""





# 2.组件化编码

# 3.vue-ajax

# 4.vue-UI组件

# 5.vue-router

# 6.vuex

# 7.vue源码

# 8。自定义全局事件总线

# 9.自定义消息机制

