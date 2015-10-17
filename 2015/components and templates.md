# Web应用组件化的权衡
  组件与模板
  by 民工精髓V
  ________________________________
  （观赏本 slide 请使用 Chrome 45+ 等支持 ES6、Fetch API 等新特性的浏览器）

## WHO AM I
  name: 徐飞（民工叔）
  weibo: @民工精髓V
  github: @xufei
  zhihu： 徐飞 /*三流程序员，二流架构师*/
  AngularJS等前端组件化框架，组件化与快速开发

## 一些基础概念

什么是Web应用

组件化开发的优势是什么

在Web应用中，组件化一般指什么

在Web应用中，组件化的主要目标是什么

## 组件化应当做到什么程度

资产与耗材

组件是资产还是耗材

模板是资产还是耗材

大部分Web应用中，资产部分多，还是耗材部分多

大部分Web应用都适合“全”组件化吗

要考虑的东西
  成本
  实现难度
  集成难度
  ……

组件与模板的对比

HTML，CSS，JS，谁是入口

Web应用的入口不再是HTML，而是JS 

动态HTML是模板还是组件？

## 组件化框架

流行的组件化框架
  Angular，Vue，Aurelia
  React
  Polymer

React的组件相当于MVVM体系中的什么

不同流派的框架有共同的未来吗

## 组件化的实践

组件树

组件树的层级

组件的粒度

组件之间的通讯方式

```
<TodoList>
    <TodoItem></TodoItem>
    <TodoItem></TodoItem>
    <TodoItem></TodoItem>
</TodoList>
```

props

dispatcher

如何选择组件间通讯方式

数据模型的耦合程度

上下级组件之间关系的密切程度

Web应用的关键步骤
  框架选择
    业务架构

数据通讯层

Meteor

Relay
GraphQL

## 其他思考

可视化继承

从继承到组合
  模板外置的组件实现

模板的意义

React DOM

"组件的字面量形式"

HTML体系做组件化的不利因素

缺少命名空间机制

DOM节点存在一些限制
  不能随意嵌套

Web Components

Shadow DOM的重要性还有那么大吗

Scoped CSS 碰到 Theme

Web技术对客户端技术的借鉴

谢谢听到这里

完整文章：https://github.com/xufei/blog/issues/22

鸣谢：@hax 的幻灯片模板
