---
title: react 基础知识
date: 2020-08-25 21:58:46
tags:
---

> ### prop 和 state
1. prop 不可改变，从父组件传递到子组件， state是组件内部状态，state改变，页面也会重新渲染，如果state是对象，需要改变引用地址。

> ### react class 组件  
1. class组件 具有生命周期钩子函数，可以在钩子函数改变state，例如componentDidMount()
2. class组件 新手更容易掌握，render() 函数返回jsx, 组件嵌套可以通过prop，从上往下传递，如瀑布流，每层都可以添加prop

>### react hooks
1. hooks 