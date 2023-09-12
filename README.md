# tony-mockjs

# 为啥要fock
基于 http://mockjs.com, 他已经不维护了


# 我们是谁
我们是广联达的一个前端团队，自研了一套内部的 **Tony-Design** 大屏可视化组件，其中用到了mock，但官方不维护了，于是我们做了一部分维护和修复的工作，回馈给开源社区。

# 我做了什么
1. **fix: responseType 初始化失败**，官方一直没修复，有很多相关 [issue](https://github.com/nuysoft/Mock/issues?q=is%3Aissue+is%3Aopen+responseType) 

# 编译
* 安装 `glup`
* 运行 `glup`, 实时生成 `dist`目录内容

---


# Mock.js
<!-- 模拟请求 & 模拟数据 -->
[![Build Status](https://travis-ci.org/nuysoft/Mock.svg?branch=refactoring)](https://travis-ci.org/nuysoft/Mock)

<!-- [![Coverage Status](https://coveralls.io/repos/nuysoft/Mock/badge.png?branch=refactoring)](https://coveralls.io/r/nuysoft/Mock?branch=refactoring)
[![NPM version](https://badge.fury.io/js/mockjs.svg)](http://badge.fury.io/js/mockjs)
[![Bower version](https://badge.fury.io/bo/mockjs.svg)](http://badge.fury.io/bo/mockjs)
[![Dependency Status](https://gemnasium.com/nuysoft/Mock.svg)](https://gemnasium.com/nuysoft/Mock)
[![spm package](http://spmjs.io/badge/mockjs)](http://spmjs.io/package/mockjs) -->

Mock.js is a simulation data generator to help the front-end to develop and prototype separate from the back-end progress and reduce some monotony particularly while writing automated tests.

The official site: <http://mockjs.com>

## Features

* Generate simulated data according to the data template
* Provide request/response mocking for ajax requests
* ~~Generate simulated data according to HTML-based templates~~

This library is loosely inspired by Elijah Manor's post [Mocking
Introduction](http://www.elijahmanor.com/2013/04/angry-birds-of-javascript-green-bird.html), [mennovanslooten/mockJSON](https://github.com/mennovanslooten/mockJSON), [appendto/jquery-mockjax](https://github.com/appendto/jquery-mockjax) and [victorquinn/chancejs](https://github.com/victorquinn/chancejs/).

## Questions?
If you have any questions, please feel free to ask through [New Issue](https://github.com/nuysoft/Mock/issues/new).

## Reporting an Issue
Make sure the problem you're addressing is reproducible. Use <http://jsbin.com/> or <http://jsfiddle.net/> to provide a test page. Indicate what browsers the issue can be reproduced in. What version of Mock.js is the issue reproducible in. Is it reproducible after updating to the latest version?

## License
Mock.js is available under the terms of the [MIT License](./LICENSE).