![vue](https://upload-images.jianshu.io/upload_images/12890819-7820bc20092c4c40.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 1.前言

本文内容讲解的内容：**一张思维导图辅助你深入了解 Vue | Vue-Router | Vuex 源码架构**。


[文章的图文结合版](https://biaochenxuying.cn/articleDetail?article_id=5cd7896c74289f3d47ed13ea)

[Vue-family.md](https://github.com/biaochenxuying/vue-family-mindmap/blob/master/Vue-family.md)

[Vue-family.pdf](https://github.com/biaochenxuying/vue-family-mindmap/blob/master/Vue-family.pdf)

## 2. Vue 全家桶

先来张 Vue 全家桶 总图：

![](https://upload-images.jianshu.io/upload_images/12890819-f7a2788fbc61e68a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 3. Vue 

细分如下

### 源码目录

![](https://upload-images.jianshu.io/upload_images/12890819-41efc5a9eec040f8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 源码构建，基于 Rollup 

![](https://upload-images.jianshu.io/upload_images/12890819-dfc52768e1942719.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



### Vue 本质：构造函数

![](https://upload-images.jianshu.io/upload_images/12890819-712e7ffb25339677.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 数据驱动

![](https://upload-images.jianshu.io/upload_images/12890819-d76f2eaddae2f07a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 组件化

![](https://upload-images.jianshu.io/upload_images/12890819-1b0a5e99649978c2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 深入响应式原理

![](https://upload-images.jianshu.io/upload_images/12890819-f7d67d439ddf2acd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 编译

![](https://upload-images.jianshu.io/upload_images/12890819-2257b1dd6c529899.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 扩展

![](https://upload-images.jianshu.io/upload_images/12890819-228d9b7ad530fff2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 4. Vue-Router

![](https://upload-images.jianshu.io/upload_images/12890819-facaee2ee08767ff.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### introduction

![](https://upload-images.jianshu.io/upload_images/12890819-83538269d41514ee.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 路由注册

![](https://upload-images.jianshu.io/upload_images/12890819-c20923bc2697cd76.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### VueRouter 对象

![](https://upload-images.jianshu.io/upload_images/12890819-28eff7d99d9725f8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### matcher

![](https://upload-images.jianshu.io/upload_images/12890819-f96c095cf5ea7570.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 路径切换

![](https://upload-images.jianshu.io/upload_images/12890819-9aaef94d98dab920.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 5. Vuex

![](https://upload-images.jianshu.io/upload_images/12890819-5710f3019ec2b189.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### introduction

![](https://upload-images.jianshu.io/upload_images/12890819-840551bd55102022.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### Vuex 初始化

![](https://upload-images.jianshu.io/upload_images/12890819-bd0c497f48f4430c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### API

![](https://upload-images.jianshu.io/upload_images/12890819-af5afdab0bd77514.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 插件

![](https://upload-images.jianshu.io/upload_images/12890819-ebb4c7e7a9903949.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 6. 已完成与待完成

**已完成**：

- 思维导图

**待完成**：

- 继续完善 思维导图
- 添加 流程图

因为该项目都是业余时间做的，笔者能力与时间也有限，很多细节还没有完善。

如果你是大神，或者对 vue 源码有更好的见解，**欢迎提交 issue ，大家一起交流学习，一起打造一个像样的 讲解 Vue 全家桶源码架构 的开源项目**。

## 7. 总结

以上内容是笔者最近学习 Vue 源码时的收获与所做的笔记，本文内容大多是开源项目 **Vue.js 技术揭秘** 的内容，只不过是以思维导图的形式来展现，内容有省略，还加入了笔者的一点理解。

笔者之所以采用思维导图的形式来记录所学内容，是因为思维导图更能反映知识体系与结构，更能使人形成完整的知识架构，知识一旦形成一个体系，就会容易理解和不易忘记。


