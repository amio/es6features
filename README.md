# ES6 入门 • 速查 [git.io/es6cn](http://git.io/es6cn)

## 简介

最新的 ECMAScript 标准 ES6（又名 ES2015）为语言添加了大量新特性，我发现即便仔细研习了每个特性之后，还是会时不时忘记具体的语法（新特性太多了）需要去查看 Babel 的 [Learn ES6](https://babeljs.io/docs/learn-es2015/)。本文旨在提供一份 ~~速成~~ 速查手册，方便 ~~十分钟入门~~ 案头参考。全面详细的语法学习建议阅读 InfoQ 的系列文章 [深入浅出 ES6](http://www.infoq.com/cn/es6-in-depth/)；完整的 ES6 规范参见 [ES6 standard](http://www.ecma-international.org/ecma-262/6.0/)；主流 JS 引擎仍在逐步实现这些特性，目前的兼容情况可查看 [ES6 特性兼容表](http://kangax.github.io/es5-compat-table/es6/)。

> 本文[最初](https://github.com/amio/es6features-depr-)翻译自 [lukehoban/es6features](https://github.com/lukehoban/es6features)，也就是 Babel 那篇 Learn ES6 的起源。翻了一半发现 Axel Rauschmayer 发出来一篇书写更友好的 [ES6 入门介绍](http://www.2ality.com/2015/08/getting-started-es6.html)，除了速查语法以外也适合做刚接触 ES6 的入门学习，所以改为基于此文而翻。Axel Rauschmayer 也是 [Exploring ES6](http://exploringjs.com/) 的作者，每个特性简介的结束都有相应详述章节的链接，完美。
