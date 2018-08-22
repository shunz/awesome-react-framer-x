# [Awesome React Framer X](https://github.com/davo/awesome-react-framer-x) 中文版 [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

这是一份 Awesome 列表，内容是所有与 [React](https://reactjs.org/) 和 [ES6](https://tc39.github.io/ecma262/) 有关的课程、教程和视频的学习链接 。

## Framer X 是什么?

[Framer X](https://framer.com/x) 是一个强大的交互设计工具。其 Beta 测试版已于 2018 年 8 月 1 日发布并正收集试用反馈。请阅读 **[官方文档](https://framer.gitbook.io/framer/)**。

开发团队最近开了一个 Facebook group **[Framer X Beta](https://www.facebook.com/groups/framer.x.feedback/)** 用来收集 bug 报告、试用反馈、建议和问题。

Beta 1 里新增了一个设计商店，提供可复用的 UI 组件（由 NPM 强力驱动）。在商店里你可以找到许多诸如地图、随机图片生成器、视频和音频播放器、设计系统套件（iOS & Android）等等交互式的设计和代码组件。

Framer X Beta 1 版中 React 组件 **仅支持 `TypeScript`**。`ES6` 预计需最终发布版才支持。

如果你想开始使用 React：

-   [React 文档](https://reactjs.org/docs/getting-started.html) - 请务必看看新的 React 文档，其中概括了最有用的资源，包括 [React 简介](https://reactjs.org/tutorial/tutorial.html) 教程。

-   [面向设计师的 React](http://reactfordesigners.com/)，由 [@zach\_\_johnston](https://twitter.com/zach__johnston) 制作，一个帮你避免选择恐惧症的快速指南。

### 从 Framer Studio 到 Framer X

<b>目前我们所知道的</b>
-   [x] Framer X 将不再支持 `CoffeeScript`。
-   [x] 基于代码的组件将支持 Beta 1 上的 Typescript。最终版本将支持普通 ES6。
-   [x] Framer.js 将会植入一组 `React` 「小助手」，用于动画、手势和插值（interpolation），它将是开源的。
-   [x] React 提供了很多方法来将 CSS 添加到代码组件中，Beta 1 已支持其中一些方法。
-   [x] Framer X 不再和 Framer Studio 一样内置代码编辑器。详情见 [如何设置和自定义代码编辑器](https://github.com/framer/FramerXDocs/tree/688689a9ac4f47d06eb9e17a32bb7aab6666eca4/application#setup-and-workflow) 。
-   [x] 要在新的「设计商店」上发布组件包，建议编辑一个 `readme.md` 文件。Github 有一个全面的 [ `Markdown` 介绍](https://guides.github.com/features/mastering-markdown/)。

## 学习目录

-   [免费 React 课程](#免费-react-课程)
-   [付费 React 课程](#付费-react-课程)
-   [ES6 课程](#es6-课程)
-   [工具](#基于-react-的设计工具-在线工具--交互式开发环境repl)
-   [代码编辑器](#代码编辑器)
-   [教程](#教程)
-   [文章](#文章)
-   [聚会活动](#其他列表-社区-聚会活动等)


## 课程

### 免费 React 课程

-   [Codecademy - React 101](https://www.codecademy.com/learn/react-101) - 深入了解 React 最基本的概念。
-   [Egghead.io: Start Learning React](https://egghead.io/courses/start-learning-react) - 探索 React 的基本原理，以帮你入门。 by [@joemaddalone](https://twitter.com/joemaddalone).
-   [Egghead.io: The Beginner's Guide to React](https://egghead.io/courses/the-beginner-s-guide-to-react) - 给 React 新手和那些希望更好的了解 React 基础知识的人。 by [@kentcdodds](https://twitter.com/kentcdodds).
-   [React Crash Course 2018](https://www.youtube.com/watch?v=Ke90Tje7VS0) - React 带案例教程。by [@moshhamedani](http://www.twitter.com/moshhamedani)
-   [ReactJS Crash Course](https://youtu.be/A71aqufiNtQ) - 了解 React.js 的基础知识。 by [@traversymedia](https://twitter.com/traversymedia) - [源代码](https://github.com/bradtraversy/projectmanager).
-   [React JS Tutorials](https://www.youtube.com/playlist?list=PLoYCgNOIyGABj2GQSlDRjgvXtqfDxKm5b) - 快速上手 React.js 开发。 by LearnCode.academy.
-   [React Armory Learn React by Itself](https://reactarmory.com/guides/learn-react-by-itself) - 无专业术语学习 React。 by [@james_k_nelson](https://twitter.com/james_k_nelson).
-   [Free React bootcamp](https://tylermcginnis.com/free-react-bootcamp/) - 所有录音、链接和作业来源于 "Free React.js Bootcamp", 直播并于2018年4月录制。 by [@tylermcginnis](https://twitter.com/tylermcginnis).
-   [React Rapid Course](https://www.youtube.com/watch?v=MhkGQAoc7bc&list=PLoYCgNOIyGABj2GQSlDRjgvXtqfDxKm5b) - 课程将帮助您快速掌握 React.js 开发 - [源代码](https://github.com/learncodeacademy/react-js-tutorials).

### 付费 React 课程

-   [React for Designers](https://designcode.io/react) - A 6-hour React course for designers, by designers. React for Designers is a free update, with a Design+Code account.
-   [Learn React](https://learnreact.design/) - Unleash Your Design Superpowers with this straightforward, with just enough JS, focused on UI design, layouts, styles and animations, by [@lintonye](https://twitter.com/lintonye).
-   [React For Beginners](https://reactforbeginners.com/) - [Source Code](https://github.com/wesbos/React-For-Beginners-Starter-Files) - Learn React.js in just a couple of afternoons, by [@wesbos](https://twitter.com/wesbos).
-   [Essential React 2018](https://learnreact.com/lessons/2018-essential-react-1-overview) - A crash course for doers, moving fast from "Hello World" to advanced component composition, by [@chantastic](https://twitter.com/chantastic). Some sections of this course are free.
-   [Udemy: The Complete React Web Developer Course (with Redux)](https://www.udemy.com/react-2nd-edition/) - Learn how to build and launch React web applications using React v16.
-   [Udemy: Modern React with Redux](https://www.udemy.com/react-redux/) - Fundamentals of React, Redux, React Router, Webpack and ES6, by [@ste_grider](https://twitter.com/ste_grider)
-   [Treehouse: Learn React:](https://teamtreehouse.com/tracks/learn-react) - Get up and running with React, a JavaScript library for building user interfaces, by [@jimrhoskins](https://twitter.com/jimrhoskins).
-   [Frontend Masters: Complete Intro to React, v3 (feat. Redux, Router & Flow)](https://frontendmasters.com/courses/react/) - Learn how to build real world applications with React with Brian Holt.

### ES6 课程

-   [Learn ES6](https://egghead.io/courses/learn-es6-ecmascript-2015) - 本课程介绍 ES6 的一些新功能, by [@johnlindquist](https://twitter.com/johnlindquist).
-   [ES6 for Everyone](https://es6.io/) - 提高您的核心 JavaScript 技能并掌握 ES6 的必备功能, by [@wesbos](https://twitter.com/wesbos).
-   [Introduction to ES6+](https://scrimba.com/g/gintrotoes6) - 通过 23 个视频学习现代 JavaScript, by Per Harald Borgen - [Article](https://medium.freecodecamp.org/want-to-learn-es6-take-this-free-23-part-course-and-become-a-javascript-ninja-55002db1ff74).

### 基于 React 的设计工具, 在线工具 & 交互式开发环境(REPL)

-   [Guppy](https://github.com/joshwcomeau/guppy) - A friendly application manager and task runner for React.js.
-   [Iso](https://compositor.io/iso/) - Build and prototype with pure JSX – no build setup or command line required.
-   [Alva](https://github.com/meetalva/alva) - Alva is a React based Design Tool (in beta).
-   [React for Designers](http://reactfordesigners.com/) - A friendly guide to start learning React. Created by [@zach\_\_johnston](https://twitter.com/zach__johnston). [Source](https://github.com/zachj0hnston/reactfordesignersdotcom).
-   [HTMLtoJSX](https://magic.reactjs.net/htmltojsx.htm) - A web based tool that converts HTML to JSX compatible with React (v15).
-   [SVG2JSX](https://svg2jsx.herokuapp.com/) - A web based tool that converts SVG to valid JSX.
-   [React Patterns](https://reactpatterns.com/) - A comprehensive collection of 17 React patterns and practices, by [@chantastic](https://twitter.com/chantastic).
-   [React Cheat Sheet](https://reactcheatsheet.com/) - An interactive documentation tool for the latest React API, by [@chantastic](https://twitter.com/chantastic).
-   [React.js Cheatsheet](https://devhints.io/react) - A complete reference of components, properties and states, life cycle methods and more.

### 代码编辑器

Framer X will not have a code editor. Good news is that you can install and customize your code editor. Here are the most popular ones.

-   [Visual Studio Code](https://code.visualstudio.com/download) - VS Code is a fast, lightweight, code editor developed by Microsoft. Is open source, comes with built-in support for `JavaScript`, `TypeScript` and `Node`.
    -   [Extensions for Visual Studio Code](https://marketplace.visualstudio.com/search?term=React&target=VSCode&category=All%20categories&sortBy=Relevance).
    -   [Framer VS Code Theme](https://github.com/framer/syntax-vsc).
    -   [Awesome VS Code List](https://github.com/viatsko/awesome-vscode).
-   [Sublime Text 3](https://www.sublimetext.com/3) - ST3 is a super fast and feature-packed code editor. Checkout [Package Control](https://packagecontrol.io/), the Sublime Text package manager. It includes a list of over 4,500 packages ready to install.
-   [Atom](https://atom.io/) - Atom is the code editor developed by Github. Ultra hackable, with tons of packages created by the community.
    -   [Framer Atom Theme](https://github.com/framer/syntax-atom).
-   [Codesandbox](https://codesandbox.io/dashboard) - CodeSandbox is an online editor that helps you create web applications, from prototype to deployment.

## 教程

-   [Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html) - 建立一个游戏，掌握创建 React 应用程序的基础知识。
-   [What Is React?](https://learnreact.design/2017/06/08/what-is-react/) - 用简单的英语和涂鸦解释 React 术语。
-   [Build with React - Tutorial](http://buildwithreact.com/tutorial) - 通过此交互式教程快速学习 React。
-   [React Tutorial for Beginners](https://ihatetomatoes.net/react-tutorial-for-beginners/) - 本教程将以简单的术语和简明的英语解释所有内容，这样您在学习 React 时就不会感到不知所措或沮丧, by [@ihatetomatoes](https://twitter.com/ihatetomatoes).
-   [React Tutorial](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/) - 一个学习React.js 的综合指南 in 2018, by [@tylermcginnis](https://twitter.com/tylermcginnis).

## 文章

### React 文章

-   [JavaScript fundamentals before learning React](https://www.robinwieruch.de/javascript-fundamentals-react-requirements/) - “在研讨会/网上教学 React 时，我经常发现自己解释的 JS 比 React 更多。这就是为什么我把所有重要的 JS 基础知识（对于 React）放在一篇大文章中” - by [@rwieruch](https://twitter.com/rwieruch).
-   [How to Learn React: A Five-Step Plan](https://www.lullabot.com/articles/how-to-learn-react) - 这五个步骤将让一个专注投入的学生花大约一周，将为您提供入门所需的基础, by [@\_\_jhannah](https://twitter.com/__jhannah).
-   [Learn React.js in 5 minutes](https://medium.freecodecamp.org/learn-react-js-in-5-minutes-526472d292f4) - 快速介绍流行的 JavaScript 库, by Per Harald Borgen.
-   [Learning React.js is easier than you think](https://edgecoders.com/learning-react-js-is-easier-than-you-think-fbd6dc4d935a) - 在一篇 Medium 文章中了解 React.js 的基础知识。
-   [9 things every React.js beginner should know](https://camjackson.net/post/9-things-every-reactjs-beginner-should-know) - 一系列提示，帮助您通过 React 获得更好的基础 by [@thecamjackson](https://twitter.com/thecamjackson).
-   [Every UI Designer needs to learn React](https://blog.continuum.cl/every-ui-designer-needs-to-learn-react-heres-why-f2b8c2ff2c86)

## 其他列表, 社区, 聚会活动等

-   [Awesome React](https://github.com/enaqx/awesome-react) - 关于 React 生态系统的一览表。
-   [Discussion forum at discuss.reactjs.org](https://discuss.reactjs.org/) - 这个论坛是讨论最佳实践和应用程序架构以及React未来的好地方。
-   [React.js meetup groups](https://www.meetup.com/topics/reactjs/): 学习 React.js 的一个好方法是参与他们精彩的社区。全世界有 500 多个聚会。马上加入！
-   [Spectrum.chat/react](https://spectrum.chat/react) - A community of developers, designers and others who love React.js.
-   [Framer X Slack Channel](https://framer.slack.com/app_redirect?channel=framer-x) - Share your work, questions or resources here!
-   [Framer React Slack Channel](https://framer.slack.com/app_redirect?channel=react) - If you have questions, resources or just want to share something, join us!
