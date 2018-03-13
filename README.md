开发实战资源整合 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/lyfyeaj/awesome-resources)
=====================



> *如同开源项目一样, 这篇文档如果没有人关心和维护, 里面的内容就会过时, 从而不再具有参考价值. 所以, 希望所有喜欢的人都能够一起来维护. 放心大胆的纠错和增加新的内容吧!*

喜欢么？或者对您有用？那就 Star 一下吧 ^_^

## 贡献方式

+ Fork 这个项目
+ 请不要直接在 `README.md` 中直接添加内容
+ 所有的文档都放在 `docs` 中, 请根据内容找到相应的文件并添加
+ 如果是 Mac 或者 Linux 用户, 请在提交前运行 ./build.sh 来自动生成 `README.md` 文件
+ 保存并提交
+ 新建一个 Pull Request

## 目录

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Web 前端](#web-%E5%89%8D%E7%AB%AF)
    - [Javascript](#javascript)
        - [Polyfills](#polyfills)
        - [HTML5 相关](#html5-%E7%9B%B8%E5%85%B3)
        - [React](#react)
    - [CSS](#css)
    - [ICON](#icon)
- [Web 后端](#web-%E5%90%8E%E7%AB%AF)
    - [Ruby](#ruby)
    - [Python](#python)
    - [Node.js](#nodejs)
        - [Express](#express)
    - [Erlang](#erlang)
    - [Java](#java)
    - [C/C++](#cc)
    - [Go](#go)
    - [Lua](#lua)
- [IOS 或 OSX](#ios-%E6%88%96-osx)
- [Android](#android)
- [代码效率](#%E4%BB%A3%E7%A0%81%E6%95%88%E7%8E%87)
    - [CoffeeScript](#coffeescript)
    - [TypeScript](#typescript)
    - [Sublime Text](#sublime-text)
- [云计算](#%E4%BA%91%E8%AE%A1%E7%AE%97)
    - [Docker](#docker)
    - [OS](#os)
- [开源产品(论坛、在线教育、项目管理等)](#%E5%BC%80%E6%BA%90%E4%BA%A7%E5%93%81%E8%AE%BA%E5%9D%9B%E5%9C%A8%E7%BA%BF%E6%95%99%E8%82%B2%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E7%AD%89)
- [代码规范&设计模式](#%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F)
    - [Ruby](#ruby-1)
        - [Rails](#rails)
    - [Javascript](#javascript-1)
        - [AngularJS](#angularjs)
    - [Java](#java-1)
        - [Android](#android-1)
    - [Bash](#bash)
    - [Objective-C](#objective-c)
        - [IOS](#ios)
    - [Swift](#swift)
    - [Design](#design)
- [数据库](#%E6%95%B0%E6%8D%AE%E5%BA%93)
- [博客 / 网站](#%E5%8D%9A%E5%AE%A2--%E7%BD%91%E7%AB%99)
    - [设计](#%E8%AE%BE%E8%AE%A1)
    - [技术](#%E6%8A%80%E6%9C%AF)
- [书籍 / 阅读 / 学习](#%E4%B9%A6%E7%B1%8D--%E9%98%85%E8%AF%BB--%E5%AD%A6%E4%B9%A0)
    - [Awesome 系列](#awesome-%E7%B3%BB%E5%88%97)
    - [前端](#%E5%89%8D%E7%AB%AF)
        - [Web](#web)
        - [React](#react-1)
        - [IOS](#ios-1)
        - [Android](#android-2)
    - [后端](#%E5%90%8E%E7%AB%AF)
        - [Node.js](#nodejs-1)
        - [Ruby](#ruby-2)
        - [PHP](#php)
        - [Go](#go-1)
        - [Bash](#bash-1)
        - [接口](#%E6%8E%A5%E5%8F%A3)
    - [算法 & 论文](#%E7%AE%97%E6%B3%95--%E8%AE%BA%E6%96%87)
    - [其他](#%E5%85%B6%E4%BB%96)
- [科学上网](#%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91)
- [Git 相关](#git-%E7%9B%B8%E5%85%B3)
- [其他](#%E5%85%B6%E4%BB%96-1)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Web 前端

#### Javascript

+ [parallel.js](https://github.com/adambom/parallel.js): 前后端通用的一个并行库
+ [zepto](https://github.com/madrobby/zepto): 用于现代浏览器的兼容 jQuery 的库
+ [totoro](https://github.com/totorojs/totoro): 稳定的跨浏览器测试工具
+ [TheaterJS](https://github.com/Zhouzi/TheaterJS): 一个用于模拟人输入状态的 JS 库
+ [stellar.js](https://github.com/markdalgleish/stellar.js): 前端用于实现异步滚动效果的库，现已不再维护
+ [skrollr](https://github.com/Prinzhorn/skrollr): 另一款实现一步滚动的开源库，使用人数众多，可实现各种狂拽酷炫掉渣天的前端效果，[看真相](http://prinzhorn.github.io/skrollr/)
+ [Framework7](https://github.com/nolimits4web/Framework7): 前端框架，是开发人员可以基于 web 技术构建 IOS7 程序
+ [regulex](https://github.com/JexCheng/regulex): 用于生成 正则表达式 的可视化流程图
+ [markdown-it](https://github.com/markdown-it/markdown-it): 新型 Markdown 解析器，快速，支持插件
+ [multiline](https://github.com/sindresorhus/multiline): 用于 Javascript 中的多行文本，类似于 Ruby 的 HERE Doc
+ [screenfull.js](https://github.com/sindresorhus/screenfull.js): 全屏插件，支持各大浏览器
+ [lunr.js](https://github.com/olivernn/lunr.js): 类似于 Solr, 但是用于浏览器上的全文搜索引擎，可以为 JSON 创建索引，离线也可以使用
+ [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys): jQuery 插件，用于绑定热键
+ [breach_core](https://github.com/breach/breach_core): Javascript 编写的 Browser (浏览器)
+ [octocard](https://github.com/zmmbreeze/octocard): 用于生成 Github 信息卡片的库
+ [github-cards](https://github.com/lepture/github-cards): 用于生成 Github 信息卡片的库
+ [money.js](https://github.com/openexchangerates/money.js): 轻量级货币转换库，web 和 node 皆可用
+ [accounting.js](https://github.com/openexchangerates/accounting.js): 轻量级的数字、货币转换库
+ [javascript-algorithms](https://github.com/mgechev/javascript-algorithms): Javascript 实现的各种算法集合
+ [lazy.js](https://github.com/dtao/lazy.js): 类似于 underscore, 但是会延迟执行，某些场景下，性能会有很大的提升
+ [seajs](https://github.com/seajs/seajs): 前端模块加载器，解决模块化、依赖等问题
+ [jQuery-One-Page-Nav](https://github.com/davist11/jQuery-One-Page-Nav): 单页应用中一个用于处理导航栏的库
+ [js.js](https://github.com/js-js/js.js): Javascript 实现的 javascript JIT
+ [jquery-ui](https://github.com/jquery/jquery-ui): jQuery 团队开发的 UI 相关的前端库，功能强大
+ [todomvc](https://github.com/tastejs/todomvc): 分别基于 AngularJS/EmberJS/Backbone等实现的 TODO List, 帮助开发者选择前端 MVC 库
+ [localForage](https://github.com/mozilla/localForage): Mozilla 出品，用于离线存储，基于IndexedDB, WebSQL 或者 localStorage, 提供一致的接口
+ [EventEmitter](https://github.com/Wolfy87/EventEmitter): 浏览器版的 EventEmitter
+ [jquery.serializeJSON](https://github.com/marioizquierdo/jquery.serializeJSON): jQuery 插件，用于将 form 表单序列化成 JSON 数据
+ [knockout](https://github.com/knockout/knockout): 前端 MVVM 框架，用于开发富前端应用
+ [mermaid](https://github.com/knsv/mermaid): 可以根据文本生成流程图，类似于 Markdown 的语法
+ [js-sequence-diagrams](https://github.com/bramp/js-sequence-diagrams): 另一款可以根据文本生成流程图的库，类似于 Markdown 的语法
+ [flow](https://github.com/facebook/flow): 一个用来检测 Javascript 语法错误的库， Facebook 出品
+ [zoomooz](https://github.com/jaukia/zoomooz): jQuery 插件，用来处理浏览器缩放
+ [fancyBox](https://github.com/fancyapps/fancyBox): 一个用于放大缩小图片、Web 内容或者多媒体元素的库，优雅大方
+ [mithril.js](https://github.com/lhorie/mithril.js): 轻量型前端 MVC 框架，部分使用场景下性能优于 Angular.js 和 React
+ [backbone](https://github.com/jashkenas/backbone): 强大的前端 MVC 库，鼻祖级前端库，最初为了配合 Rails 来模块化前端应用，兼容性良好 (兼容到 IE6)，插件丰富，性能良好
+ [jquery.smartbanner](https://github.com/jasny/jquery.smartbanner): [smartbanner](http://developer.apple.com/library/ios/#documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html) 是从 IOS6 开始支持的一个新特性, 这个插件提供了对早期 IOS4/5 和 Android 的支持
+ [jquery.scrollTo](https://github.com/flesler/jquery.scrollTo): 在页面上以一个元素为起始以动画的方式移动(ScrollTo)到另一个元素， 支持回退等
+ [jScrollPane](https://github.com/vitch/jScrollPane): 自定义的滚动条，让所有浏览器都显示一样的滚动条
+ [onepage-scroll](https://github.com/peachananr/onepage-scroll): 提供类似于 iPhone6 展示页类似的效果，适用于单页应用，兼容到 IE8
+ [scrollMonitor](https://github.com/sakabako/scrollMonitor): 前端插件用来监控元素的滚动事件(进入、退出等)，性能很好
+ [ScrollMagic](https://github.com/janpaepke/ScrollMagic): 神奇的滚动交互效果插件，可以在滚动的过程中设置各种各样的动态效果
+ [infinite-scroll](https://github.com/paulirish/infinite-scroll): 滚动加载，滚动到最下到自动加载， Paul Irish 大神之作
+ [animatable](https://github.com/LeaVerou/animatable): 仅仅依靠 `border-width` 和 `background-position` 实现的各种动态效果，[看真相](http://leaverou.github.io/animatable/)
+ [Fluidbox](https://github.com/terrymun/Fluidbox): 页面上内嵌图片的放大缩小效果，类似于 [Medium](http://medium.com) 中的效果
+ [jquery-validation](https://github.com/jzaefferer/jquery-validation): jQuery 的一个插件，用于校验 Form 表单
+ [BigVideo.js](https://github.com/dfcb/BigVideo.js): jQuery 的一个插件, 用于实现大背景(视频、图片)效果
+ [emscripten](https://github.com/kripken/emscripten): 一款基于 LLVM, 可以将 C/C++ 转换成 Javascript 的工具，使得 Javascript 可以近乎 Native 的速度
+ [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator): 各种语言的二维码生成工具
+ [device.js](https://github.com/matthewhudson/device.js): 一个可以检测设备类型的工具，可以让我们根据不同的设备来为其定制响应的 Javascript 和 CSS
+ [jquery-qrcode](https://github.com/jeromeetienne/jquery-qrcode): jQuery 插件，用来生成二维码
+ [Wookmark-jQuery](https://github.com/GBKS/Wookmark-jQuery): jQuery 的一个插件，可以用来实现瀑布流的效果
+ [isotope](https://github.com/metafizzy/isotope): 可以用来过滤、排列布局，实现美观的动态布局切换效果，[Demo](http://isotope.metafizzy.co/)
+ [lazysizes](https://github.com/aFarkas/lazysizes): 功能强大的图片延迟加载工具，可以首先加载一个低质量的图片，然后再加载高质量的图片
+ [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js): 简洁美观的进度条，扁平化
+ [pigshell](https://github.com/pigshell/pigshell): 一个由 Javascript 实现的Shell, 将互联网当做一个大的文件系统, 通过 cd/ls/cat.....等命令, 可以访问 Facebook
/Twitter/Google Drive 等网络服务
+ [spectrum](https://github.com/bgrins/spectrum): Js实现的颜色选择器 (Colorpicker)
+ [jQuery.countdown](https://github.com/hilios/jQuery.countdown): jQuery 倒计时插件
+ [summernote](https://github.com/summernote/summernote): WYSIWYG 富文本编辑器
+ [awesomplete](https://github.com/LeaVerou/awesomplete): 非常轻型的一个自动补全 JS 库, 没有任何依赖, 配置简单, 美观
+ [switchery](https://github.com/abpetkov/switchery): IOS 7 上 Switch 的 JS 实现, 支持 IE8 及以上浏览器
+ [trix](https://github.com/basecamp/trix): Basecamp 公司出品的富文本编辑器，简洁小巧
+ [greensock](http://greensock.com/): greensock是一個非常強大的動畫庫，網站內也有很完整的API文檔和examples
+ [Moment.js](https://github.com/moment/moment/) Moment.js 是一个功能丰富的 JavaScript 日期处理类库，用于解析、检验、操作、以及显示日期
+ [webpack](https://github.com/webpack/webpack) webpack 是一个 JavaScript 模块打包工具，功能强悍、插件丰富

###### Polyfills

+ [picturefill](https://github.com/scottjehl/picturefill): 响应式的图片 `<picture>` polyfill, 支持srcset, sizes等
+ [Placeholders.js](https://github.com/jamesallardice/Placeholders.js): 为不支持的 HTML5 的浏览器提供 Placeholder 支持
+ [prefixfree](https://github.com/LeaVerou/prefixfree): 自动为 CSS 添加 Vender Prefix，把你从不停添加浏览器前缀的噩梦中解放出来
+ [history.js](https://github.com/browserstate/history.js): History 接口的功能实现
+ [html5shiv](https://github.com/aFarkas/html5shiv): 为 IE 等老旧浏览器添加 HTML5 标签支持
+ [es6-shim](https://github.com/paulmillr/es6-shim): 为浏览器添加 ES6 支持
+ [es5-shim](https://github.com/es-shims/es5-shim): 为浏览器添加 ES5 支持
+ [Respond](https://github.com/scottjehl/Respond): 为IE浏览器添加 media query 支持
+ [json3](https://github.com/bestiejs/json3): 为旧浏览器添加 JSON 支持

###### HTML5 相关

+ [sensor.js](https://github.com/branding-fe/sensor): 在智能移动设备浏览器上，通过HTML5的api使用移动设备的功能。定位、运动、倾斜等
+ [hyhyhy](https://github.com/maciejczyzewski/hyhyhy): 用于创建 基于 HTML5 的 演示文稿
+ [swipebox](https://github.com/brutaldesign/swipebox): jQuery 插件，用于处理移动端的触摸事件
+ [FileAPI](https://github.com/mailru/FileAPI): 前端用户处理文件（拖放、多文件上传等）
+ [Sortable](https://github.com/RubaXa/Sortable): 现代浏览器上用于实现元素拖拽排序的功能，支持 Meteor, AngularJS, React，不依赖 jQuery
+ [Swiper](https://github.com/nolimits4web/Swiper): 用于实现浏览器上的滑动切换效果，支持硬件加速
+ [matter-js](https://github.com/liabru/matter-js): 2D 物理效果引擎，碰撞、弹跳等
+ [jQTouch](https://github.com/senchalabs/jQTouch): 用于辅助创建手机端的 Web 应用，支持主题、Zepto.js 等
+ [snabbt.js](https://github.com/daniel-lundin/snabbt.js): 一个利用 Javascript 和 CSS transform 的 animation 库
+ [c3](https://github.com/masayuki0812/c3): 基于 D3 的图表库
+ [echarts](https://github.com/ecomfe/echarts): 企业级图表库，百度开发
+ [parallax.js](https://github.com/wagerfield/parallax): 一个用于响应智能手机 orientation 的库
+ [jQuery-Animate-Enhanced](https://github.com/benbarnett/jQuery-Animate-Enhanced): jQuery 动画库的一个增强，用于现代浏览器
+ [wysihtml](https://github.com/Voog/wysihtml): 富文本编辑器，适用于现代浏览器
+ [slip](https://github.com/pornel/slip): 一个通过滑动或者拖拽来操控列表的库
+ [evil-icons](https://github.com/outpunk/evil-icons): 一个矢量图库，提供 Ruby/Node 等支持
+ [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe): JS 的一个图片展示库
+ [focusable](https://github.com/zzarcon/focusable): 是页面上一个元素高亮的库，[有图有真相](http://zzarcon.github.io/focusable/)
+ [firefox.html](https://github.com/paulrouget/firefox.html): Firefox 在浏览器端的实现 —— HTML 版的 Firefox
+ [jquery-mobile](https://github.com/jquery/jquery-mobile): jQuery 团队开发的用于辅助手机端 web app 开发的库，基于 HTML5
+ [mobile-angular-ui](https://github.com/mcasimir/mobile-angular-ui): 基于angularjs和bootstarp的web app开发框架
+ [interact.js](https://github.com/taye/interact.js): 一个适用于现代浏览器的，用于处理 手势、拖放、缩放等的库
+ [rebound-js](https://github.com/facebook/rebound-js): 实现部分物理效果，Facebook 出品
+ [basket.js](https://github.com/addyosmani/basket.js): 基于 LocalStorage 的资源加载器，可以用来缓存 script 和 css, 手机端使用速度快于浏览器直接缓存
+ [iscroll](https://github.com/cubiq/iscroll): 高性能的滚动(scroll)处理库，功能强大，支持各种事件，不依赖任何的库，且插件丰富, 大众点评的手机端列表滚动就是用这个库处理的
+ [metrics-graphics](https://github.com/mozilla/metrics-graphics): 基于 D3 的图表库，简洁、高效，Mozilla 出品
+ [accessible-html5-video-player](https://github.com/paypal/accessible-html5-video-player): Paypal 出品的 Video 播放器
+ [loading](https://github.com/jxnblk/loading): 几种 Loading 效果，基于 SVG
+ [flippant.js](https://github.com/mintchaos/flippant.js): 一款能够漂亮的网页元素翻转效果库，代码许久不更新，不过作为源码学习还是不错的
+ [move.js](https://github.com/visionmedia/move.js): 基于 CSS3 的前端动画框架
+ [scrollReveal.js](https://github.com/julianlloyd/scrollReveal.js): 使元素以非常酷帅的方式进入画布 (Viewpoint)，看 [Demo](http://scrollrevealjs.org/)
+ [Modernizr](https://github.com/Modernizr/Modernizr): 一个用来检测 HTML5 和 CSS3 支持情况的库
+ [foundation](https://github.com/zurb/foundation): 另一款前端模版框架，类似于 Bootstrap
+ [Flat-UI](https://github.com/designmodo/Flat-UI): Bootstrap 的一款主题，简洁美观
+ [iCheck](https://github.com/fronteed/iCheck): 一款漂亮的 Checkbox 插件
+ [Swipe](https://github.com/lyfeyaj/Swipe): 非常轻量级的一个图片滑动切换效果库, 性能良好, 尤其是对手机的支持, 压缩后的大小约 5kb
+ [slick](https://github.com/kenwheeler/slick): 功能异常强大的一个图片滑动切换效果库
+ [SocialButtons](https://github.com/t4t5/SocialButtons): 漂亮的社交按钮
+ [sweetalert](https://github.com/t4t5/sweetalert): 一个非常美观的用于替换浏览器默认 alert 的库
+ [web-animations-js](https://github.com/web-animations/web-animations-js): Javascript 实现的 Web Animation API
+ [vivus](https://github.com/maxwellito/vivus): 可以动态描绘 SVG 的 JS 库, 支持多种动画
+ [plyr](https://github.com/Selz/plyr): 轻量, 小巧, 美观的 HTML5 视频播放器
+ [timesheet.js](https://github.com/sbstjn/timesheet.js): 基于  HTML5 & CSS3 时间表
+ [slideout](https://github.com/Mango/slideout): 一个非常美观的侧滑菜单
+ [pixi.js](https://github.com/pixijs/pixi.js): 非常強大的2d遊戲庫，網站內有許多的examples可以學習
+ [three.js](https://github.com/mrdoob/three.js/): 非常強大的3d遊戲庫
###### AngularJS

+ [angular-masonry](https://github.com/passy/angular-masonry): Masonry 的 AngularJS 插件，用于瀑布流
+ [angular-schema-form](https://github.com/Textalk/angular-schema-form): 根据 JSON 生成响应的 Form 表单
+ [restangular](https://github.com/mgonto/restangular): Angular 中用来处理 RESTful API 的插件，可替代 $resource
+ [ng-cordova](https://github.com/driftyco/ng-cordova): Cordova 常用组件的 Angular 版本
+ [angular-translate](https://github.com/angular-translate/angular-translate): Angular 的国际化 (I18n)
+ [ng-inspector](https://github.com/rev087/ng-inspector): Chrome 插件，用于调试 Angular
+ [angularjs-style-guide](https://github.com/mgechev/angularjs-style-guide): AngularJS 代码风格
+ [ngReact](https://github.com/davidchang/ngReact): React 的 Angular 插件，可以在 Angular 中使用 React Components
+ [material](https://github.com/angular/material): Google Material Design 效果的 Angular 实现
+ [angular-local-storage](https://github.com/grevory/angular-local-storage): Angular 插件, 提供了对 localStorage 的友好支持, 并对不支持的浏览器使用 cookie 优雅降级
+ [angular-filter](https://github.com/a8m/angular-filter): 一组有用的 Angular Filters
+ [bindonce](https://github.com/Pasvaz/bindonce): Angular 插件, 用于减少 Watcher 的数量, 提升性能

###### React

+ [react](https://github.com/facebook/react): React 框架源代码
+ [react-native](https://github.com/facebook/react-native): Facebook 出品的使用 React 开发 IOS 原生应用的框架
+ [react-hot-loader](https://github.com/gaearon/react-hot-loader): 实时调整 React 组件效果
+ [grunt-react](https://github.com/ericclemmons/grunt-react): React 的 Grunt 组件, 用于将 JSX 编译成 JS
+ [touchstonejs](https://github.com/JedWatson/touchstonejs): 基于 React 的手机应用前端框架
+ [essential-react](https://github.com/pheuter/essential-react): 基于 React, ES6, React-Router的一个应用脚手架
+ [react-router](https://github.com/rackt/react-router): React 路由解决方案
+ [react-redux](https://github.com/reactjs/react-redux): React redux 插件, 提供 React 的 Redux 支持
+ [redux](https://github.com/reactjs/redux): Javascript的可预测状态容器, 主要用于处理数据流向和管理状态
+ [recharts](https://github.com/recharts/recharts): 基于 React 和 D3 实现的图表工具

#### CSS

+ [Hover](https://github.com/IanLunn/Hover): 基于 CSS3 的各种 鼠标悬停(hover)特效, [点击查看效果](http://ianlunn.github.io/Hover/)
+ [normalize.css](https://github.com/necolas/normalize.css): 一个用于重置浏览器内置样式的库
+ [Skeleton](https://github.com/dhg/Skeleton): 一个 CSS 相关的库，用于构建对手机友好的网站
+ [pure](https://github.com/yahoo/pure): Yahoo 出品的前端样式框架, 支持响应式
+ [materialize](https://github.com/dogfalo/materialize/): 基于谷歌 Material Design 的响应式 CSS
框架
+ [Metro UI](https://github.com/olton/Metro-UI-CSS): 一个 Metro 风格的前端框架
+ [animate](https://daneden.github.io/animate.css): 簡單又好用的動畫庫，網站內有簡單的範例跟demo效果

#### ICON

+ [icono](https://github.com/saeedalipoor/icono): 一款用纯 CSS 实现的图标库
+ [material-design-icons](https://github.com/google/material-design-icons): Google 为 Material Design 出品的 ICON


## Web 后端

#### Ruby

+ [ruby](https://github.com/ruby/ruby): Ruby 源代码
+ [spyke](https://github.com/balvig/spyke): 像使用 ActiveRecord 一样使用 RESTful API
+ [reactive_record](https://github.com/twopoint718/reactive_record): 根据 ActiveRecord 的 数据库 Schema 来反向生成 Model
+ [eventmachine](https://github.com/eventmachine/eventmachine): Ruby 中著名的事件驱动库
+ [faker](https://github.com/stympy/faker): Perl 的 Data::Faker 库的一个 Ruby 实现，用于虚拟各种类型的数据
+ [amqp](https://github.com/ruby-amqp/amqp): RabbitMQ 的 Ruby 客户端，基于 EventMachine
+ [bunny](https://github.com/ruby-amqp/bunny): 另一个 RabbitMQ 的 Ruby 客户端
+ [thinking-sphinx](https://github.com/pat/thinking-sphinx): Sphinx 全文搜索的 ActiveRecord 插件
+ [ruby-vips](https://github.com/jcupitt/ruby-vips): Ruby 的一款图像处理库, 基于 libvips
+ [statesman](https://github.com/gocardless/statesman): Ruby 的一个状态机
+ [aasm](https://github.com/aasm/aasm): 另一款 Ruby 状态机
+ [paper_trail](https://github.com/airblade/paper_trail): 一款强大的用于记录 Model 变更的库，非常适合于 创建记录的版本和审查变更
+ [timers](https://github.com/celluloid/timers): Ruby 的一个 Timer 库，适合于配合事件使用
+ [gitlab-shell](https://github.com/gitlabhq/gitlab-shell): gitlab 的命令行工具，用于替换 gitolite
+ [money](https://github.com/RubyMoney/money): Ruby 的一个数字、货币转换库
+ [money-rails](https://github.com/RubyMoney/money-rails): Rails 的一个数字、货币转换库
+ [houston](https://github.com/nomad/houston): APN 的 Ruby 库
+ [devise_invitable](https://github.com/scambra/devise_invitable): Devise 的一个插件，用于邀请用户
+ [mail](https://github.com/mikel/mail): Ruby 的处理邮件的库
+ [commander](https://github.com/tj/commander): Ruby 的命令行辅助库
+ [helios](https://github.com/helios-framework/helios): 一个为 IOS 提供后端支撑的库
+ [middleman](https://github.com/middleman/middleman): 一个辅助制作静态网站的工具
+ [pundit](https://github.com/elabs/pundit): 一个处理认证的库
+ [refile](https://github.com/elabs/refile): 一个处理图片上传的库
+ [sharedrop](https://github.com/cowbell/sharedrop): Airdrop 的 HTTP5 实现，基于 WebRTC
+ [mailman](https://github.com/titanous/mailman): 处理接收邮件的库
+ [mruby](https://github.com/mruby/mruby): mini-ruby (light-weight ruby) 轻量级 Ruby 源代码
+ [sidekiq-status](https://github.com/utgarda/sidekiq-status): Sidekiq 插件，用来监控任务状态
+ [postgres_ext](https://github.com/dockyard/postgres_ext): ActiveRecord 的插件，扩展了 PostgreSQL 相关的一些功能
+ [prawn](https://github.com/prawnpdf/prawn): Ruby 的 PDF 编辑工具
+ [spring](https://github.com/rails/spring): Rails 的加载器，可以加速 Rails 开发
+ [rails](https://github.com/rails/rails): Rails 源代码
+ [newrelic-grape](https://github.com/xinminlabs/newrelic-grape): Grape 的 Newrelic 插件
+ [newrelic_moped](https://github.com/stevebartholomew/newrelic_moped): Moped 的 Newrelic 插件
+ [rack-attack](https://github.com/kickstarter/rack-attack): 基于 Rack 的防攻击中间件
+ [rack-utf8_sanitizer](https://github.com/whitequark/rack-utf8_sanitizer): Rack 的 UTF8 序列化中间件
+ [redis-stat](https://github.com/junegunn/redis-stat): Redis 监控工具
+ [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler): Rack 中间件，用于分析各个性能指标，如 SQL, View渲染等
+ [memory_profiler](https://github.com/SamSaffron/memory_profiler): 用于分析内存占用
+ [gctools](https://github.com/tmm1/gctools): 用于分析和优化 Ruby GC，可以配合 Unicorn 使用
+ [wicked_pdf](https://github.com/mileszs/wicked_pdf): Rails 插件，用于生成 PDF
+ [request_store](https://github.com/steveklabnik/request_store): Rack 中间件，用于保存仅单次请求有效的的全局变量，线程安全
+ [slim](https://github.com/slim-template/slim): 基于 Ruby 的前端模板引擎，类似于 Haml, 语法更简洁，据说相比于 Haml 会更快一些
+ [simplecov](https://github.com/colszowka/simplecov): Ruby 测试代码的覆盖率分析
+ [sass](https://github.com/sass/sass): CSS 框架，使得编写 CSS 更加容易和有趣，支持模块化、变量、运算、Mixin等
+ [slate](https://github.com/tripit/slate): 静态的 API 接口文档生成工具，干净、整洁、对手持设备友好、单页应用、代码高亮
+ [ruby-destroyed_at](https://github.com/dockyard/ruby-destroyed_at): ActiveRecord 扩展，支持安全删除
+ [taps](https://github.com/ricardochimal/taps): 支持数据库导入导出 -> 原理是，对导出目标数据库建立一个服务器提供数据接口，然后对目标导入数据库进行数据导入，依赖 Sinatra 启动数据库接口服务
+ [meta-tags](https://github.com/kpumuk/meta-tags): 为 Rails 应用提供 SEO 优化支持
+ [logstash](https://github.com/elasticsearch/logstash): 日志、时间管理工具
+ [rspec-rails](https://github.com/rspec/rspec-rails): Rspec 的 Rails 插件
+ [nokogiri](https://github.com/sparklemotion/nokogiri): 一个功能强大，性能良好的用于解析 HTML, XML 的工具，支持 XPath 和 CSS 选择器
+ [vcr](https://github.com/vcr/vcr): 一个测试辅助库，纪录一组 HTTP 请求交互，并作为测试重现
+ [factory_girl](https://github.com/thoughtbot/factory_girl): 一个用来准备测试数据的库
+ [mongoid_paranoia](https://github.com/simi/mongoid_paranoia): Mongoid 软删除功能, 通过添加一个 destroyed_at
+ [treat](https://github.com/louismullie/treat): Ruby的自然语言处理
+ [MacGap1](https://github.com/MacGapProject/MacGap1): 一款工具可以将 HTML/CSS/JS 网络应用打包成 Mac App
+ [ffi](https://github.com/ffi/ffi): 可以帮助 Rubyer 开发基于 C 的 ruby 库, 提供了一套接口
+ [api_cache](https://github.com/mloughran/api_cache): 可以为外部接口添加缓存的工具
+ [ckeditor](https://github.com/galetahub/ckeditor): Rails 的 Ckeditor 插件
+ [mailboxer](https://github.com/mailboxer/mailboxer): Rails 插件, 可以发送消息/邮件
+ [gc_tracer](https://github.com/ko1/gc_tracer): Ruby GC 跟踪器
+ [carrierwave-qiniu](https://github.com/huobazi/carrierwave-qiniu): Carrierwave 的 七牛 插件
+ [mongoid-ancestry](https://github.com/skyeagle/mongoid-ancestry): Mongoid Ancestry 实现
+ [countries](https://github.com/hexorx/countries): 一个库包含全球各个国家的信息 (ISO 3166 (countries and states/subdivisions ), ISO 4217 (currency), and E.164 (phone numbers))
+ [chruby](https://github.com/postmodern/chruby): 切换 Ruby 的版本 和 可以和 ruby-install 配合
+ [ruby-install](https://github.com/postmodern/ruby-install): 用来安装 Ruby, JRuby, Rubinius, MagLev 或者 MRuby 环境
+ [caphub](https://github.com/railsware/caphub): 基于 capistrano 的集中发布管理实例
+ [chruby](https://github.com/capistrano/chruby): capistrano 的 chruby 支持
+ [byebug](https://github.com/deivid-rodriguez/byebug): Ruby 2 的一个调试器
+ [opal](https://github.com/opal/opal): Ruby -> Javascript 代码转换工具
+ [volt](https://github.com/voltrb/volt): Ruby 的 一个 Web 框架, 使用 opal 使得前后端均可以用 Ruby 编写
+ [tunemygc](https://github.com/bear-metal/tunemygc): 用于分析 Ruby 的 GC, 并给出最合适的配置
+ [parallel](https://github.com/grosser/parallel): Ruby 的一个并行运算库
+ [http.rb](https://github.com/httprb/http.rb): Ruby 的一个 HTTP 库, 提供了链式的语法和完全的 Streaming 支持
+ [has_scope](https://github.com/plataformatec/has_scope): 用于在控制器中钩子中使用Scope
+ [linguist](https://github.com/github/linguist): Github 官方出品, 用于识别编程语言, 以及代码高亮
+ [markup](https://github.com/github/markup): Github 官方出品, 用于解析各类 markup 文件

#### Python

+ [django](https://github.com/django/django): 一个全栈式的 web 框架, 类似于 Rails
+ [django-rest-framework](https://github.com/tomchristie/django-rest-framework): django 的 一个  Rest API 框架
+ [flask](https://github.com/pallets/flask): 一个轻量级的 web 框架
+ [wifiphisher](https://github.com/sophron/wifiphisher): WIFI 中间人钓鱼攻击工具，获取用户名密码
+ [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit): Python 的交互命令行工具，提供代码补全、高亮等
+ [redis-rdb-tools](https://github.com/sripathikrishnan/redis-rdb-tools): Redis 的 dump.rdb 文件解析器，用于分析内存使用、导出 JSON 以及 比较不同 rdb 文件差异
+ [supervisor](https://github.com/Supervisor/supervisor): 类UNIX下用于控制进程的一个开源库，通过配置可以监控、自动重启各种服务
+ [pyenv](https://github.com/yyuu/pyenv): Python 版本管理工具，类似于 RVM
+ [scrapy](https://github.com/scrapy/scrapy): 一个全能型的爬虫框架
+ [pyspider](https://github.com/binux/pyspider): 一个爬虫系统


#### Node.js

+ [Node-Webkit.js](https://github.com/nwjs/nw.js): Node-Webkit 是基于Chromium 和 node.js的运行环境，可以用来创建桌面应用程序
+ [request](https://github.com/request/request): 基于 Node.js 的用于网络请求的库，使用简单，功能强大
+ [hapi](https://github.com/hapijs/hapi): 一个配置优先的 web 框架，[hapijs.com](http://hapijs.com/)
+ [psi](https://github.com/addyosmani/psi): 用于分析页面速度的工具，支持命令行
+ [gulp](https://github.com/gulpjs/gulp): 基于 Node.js 的流式构建系统
+ [orchestrator](https://github.com/orchestrator/orchestrator): 一个可以并行执行任务和依赖的库
+ [johnny-five](https://github.com/rwaldron/johnny-five): 用 Javascript 控制机器人
+ [popcorn-js](https://github.com/mozilla/popcorn-js): Mozilla 的一个开源项目，允许开发者基于 HTML5 音视频的时间线添加互动元素，比如注释，字幕，甚至动画
+ [connect](https://github.com/senchalabs/connect): Node 中间件支持，注：Express 4 以下依赖此库，从 4 开始支持全新的 Router，类似于 Rails Engine
+ [faker.js](https://github.com/Marak/faker.js): Faker 的 Node 实现，用于生成假数据
+ [chart](https://github.com/jstrace/chart): 用于终端生成 ASCII 图表
+ [drawille](https://github.com/asciimoo/drawille): 用于终端生成 ASCII 图形
+ [sparkly](https://github.com/sindresorhus/sparkly): spark.sh 的一个 Javascript 实现，终端生成 sparklines
+ [node-inspector](https://github.com/node-inspector/node-inspector): Node 的调试神器，使用方法，用 `node-debug` 代替 `node` 启动服务，并在你想调试的地方输入 `debugger`
+ [NodeOS](https://github.com/NodeOS/NodeOS): 基于 Node 的操作系统
+ [pdfkit](https://github.com/devongovett/pdfkit): Node 和 浏览器均可以使用的，用于生成 PDF 的库
+ [empty-trash](https://github.com/sindresorhus/empty-trash): 清空垃圾桶
+ [trash](https://github.com/sindresorhus/trash): 安全删除文件 -> 将文件放入垃圾桶
+ [rabbit.js](https://github.com/squaremo/rabbit.js): RabbitMQ 的 Node 客户端
+ [htmlbars](https://github.com/tildeio/htmlbars): 基于 Handlebars 的一个变种，可以编写直接操作 DOM 的辅助方法
+ [sharp](https://github.com/lovell/sharp): Node 的一个图像处理的库，基于 libvips
+ [debug](https://github.com/visionmedia/debug): 一个用于在 console 或者 浏览器输出日志，方便与 Debug 的工具
+ [github-contributions](https://github.com/IonicaBizau/github-contributions): 一个好玩的库，用于在 github 的 contribution calendar 上输出你想要的文字或者图案
+ [hexo](https://github.com/hexojs/hexo): 基于 Node 的静态博客，类似于 Octopress
+ [GhostScroll](https://github.com/grmmph/GhostScroll): Ghost 的一个主题
+ [ghost-themes](https://github.com/haydenbleasel/ghost-themes): 多个 Ghost 主题
+ [TermKit](https://github.com/unconed/TermKit): 一个基于 Chrome 和 Node 的终端应用
+ [h5ai](https://github.com/lrsjng/h5ai): 配置简单，美观的 http 静态目录，支持 Nginx、Apache 等
+ [http-server](https://github.com/nodeapps/http-server): Http 静态服务器，基于 Node, 配置简单
+ [node-apn](https://github.com/argon/node-apn): Node 的 APN (Apple Push Notification) 模块
+ [chai](https://github.com/chaijs/chai): Node 的 TDD/BDD 测试框架
+ [io.js](https://github.com/iojs/io.js): Node 的一个分支，更加活跃，开发更激进，最终的目的是合并入 Node.js
+ [immutable-js](https://github.com/facebook/immutable-js): 不可改变的集合, 前后端通用
+ [node-migrate](https://github.com/tj/node-migrate): Node 的数据库迁移框架
+ [pomelo](https://github.com/NetEase/pomelo): Node 游戏服务器框架，网易开发
+ [blessed-contrib](https://github.com/yaronn/blessed-contrib): 构建终端信息板 (Dashboard) 利器
+ [node-notifier](https://github.com/mikaelbr/node-notifier): Node 模块，可以发送本地通知，支持 Mac/Windows/Linux
+ [prerender](https://github.com/prerender/prerender): 用于预解析网站，主要解决单页应用(angular.js ember.js backbone.js 等)的搜索引擎 SEO 支持
+ [spider](https://github.com/alongubkin/spider): 一种新语言，目标是编译成 Javascript
+ [jsdoc](https://github.com/jsdoc3/jsdoc): 用来生成 Javascript API 文档的库
+ [browser-sync](https://github.com/shakyShane/browser-sync): 多浏览器(多设备)同步库，监控 CSS/Javascript/HTML 的变更并通知到浏览器；监控浏览器的操作，如滚动、点击等事件，同步到所有的开发设备。前端开发利器！
+ [tmi](https://github.com/addyosmani/tmi): 基于 Node 的命令行工具, 用于计算网站图片的权重，以及那些图片可以进一步优化
+ [6to5](https://github.com/6to5/6to5): 转换 ES6 代码为 ES5，提前使用 ES6 语法带来的各种畅快！
+ [js-xss](https://github.com/leizongmin/js-xss): 根据白名单过滤HTML(防止XSS攻击)
+ [PM2](https://github.com/Unitech/PM2): Node 进程管理，内置负载均衡，提供自动重启，热启动等功能，适合在生产环境下使用
+ [sinopia](https://github.com/rlidwka/sinopia): 私有 NPM 服务器
+ [validator.js](https://github.com/chriso/validator.js): 校验工具(url，邮箱，整数等), 内置几十种校验方法，前后端通用
+ [wechat](https://github.com/node-webot/wechat): 微信公共平台消息接口服务中间件
+ [superagent](https://github.com/visionmedia/superagent): 更 NB 的 Ajax 请求库，号称比 jQuery 更好用，前后端通用
+ [cheerio](https://github.com/cheeriojs/cheerio): Server 端的 jQuery, 相同的 API，支持 DOM 操作等
+ [node-restify](https://github.com/mcavage/node-restify): Node.js 的 REST API 框架，从 Express 中借鉴了很多，并去除了 render 等方法
+ [ejs](https://github.com/tj/ejs): Node.js 的前端模板引擎, 使用 <%=  %> 直接在 HTML中嵌入，简单易学
+ [Bluebird](https://github.com/petkaantonov/bluebird): 另一款实现 Promises/A+ 的库，相比于 Q，性能卓越
+ [node-amqp](https://github.com/postwait/node-amqp): RabbitMQ 的 Node 客户端
+ [Knex](https://github.com/tgriesser/knex): SQL 生成器，支持 PostgreSQL, MySQL 和 SQLite3， 用于和 Bookshelf 配合使用
+ [node_redis](https://github.com/mranney/node_redis): Node 的 Redis 客户端
+ [elasticsearch-js](https://github.com/elasticsearch/elasticsearch-js): ElasticSearch 的 Node 客户端
+ [Passport](http://passportjs.org/): Node 的认证中间件，支持 Express, 组件丰富, 支持多种认证策略，OAuth
+ [everyauth](https://github.com/bnoguchi/everyauth): 认证库，支持多种策略，OAuth，支持 Express
+ [node-oauth](https://github.com/ciaranj/node-oauth): Node 的 OAuth 支持
+ [restler](https://github.com/danwrong/restler): 一个 Node REST 客户端
+ [oauth2orize](https://github.com/jaredhanson/oauth2orize): Node 的服务端 OAuth支持
+ [Mocha](http://mochajs.org/): Node 的 TDD/BDD 测试框架
+ [nodemon](https://github.com/remy/nodemon): 开发时使用, 自动检测文件变更, 并重启服务
+ [hiredis-node](https://github.com/redis/hiredis-node): hiredis 的 Node 模块
+ [node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken): JsonWebToken 的 Node.js 实现
+ [js2coffee](https://github.com/js2coffee/js2coffee): 将 Javascript 转换成 CoffeeScript 的一个工具
+ [grunt-injector](https://github.com/klei/grunt-injector): Grunt 的 JS/CSS 自动注入工具, 可以自动将 JS/CSS 的引用注入到 HTML 文件中
+ [NativeScript](https://github.com/NativeScript/NativeScript): 使用 Javascript 来编写 IOS / Android 以及更多平台原生软件的库
+ [rosie](https://github.com/bkeepers/rosie): 用于生成 Javascript 对象, 方便测试, 类似于 factory_girl
+ [jsduck](https://github.com/senchalabs/jsduck): javascript 文档生成工具
+ [shelljs](https://github.com/arturadib/shelljs): shell 命令的 Node.js 封装, 支持 local 和 global 两种模式
+ [daemon.node](https://github.com/indexzero/daemon.node): 以后台守护进程启动 node 应用的最小化实现, 可作为学习源码使用
+ [blessed](https://github.com/chjj/blessed): Node 的命令行界面工具, 一共一组高级接口支持命令行绘图, 动画等
+ [node-spdy](https://github.com/indutny/node-spdy): Node 的 SPDY 支持
+ [node-fibers](https://github.com/laverdet/node-fibers): Node 的 Fiber 实现
+ [fast.js](https://github.com/codemix/fast.js): 对 JS 的一些方法的重新实现, 提供更高的性能
+ [log4js-node](https://github.com/nomiddlename/log4js-node): Log4js 的 Node.js 版
+ [https://github.com/andrewplummer/Sugar](https://github.com/andrewplummer/Sugar): Javascript 原生类型的功能扩充(Monkey Patch), 提供了各种语法糖
+ [shelljs](https://github.com/arturadib/shelljs): 各种 Shell 命令的 Node 实现
+ [Meteor](https://github.com/meteor/meteor): 一个基于 Node.js 的平台，用于开发实时网页和移动应用
+ [Koa](https://github.com/koajs/koa): Node.js web 框架，Express 原班人马打造，推崇极简，通过 generator 实现异步控制
+ [Power Assert](https://github.com/power-assert-js/power-assert): 报错信息极其详细的 assert 库
+ [Trevor](https://github.com/vadimdemedes/trevor): 本地的简版 Travis 集成集成测试环境，需要Docker支持

###### Express

+ [express-admin](https://github.com/simov/express-admin): Express 的后端，支持(MySQL, MariaDB, SQLite, PostgreSQL)
+ [grant](https://github.com/simov/grant): Express 认证中间件(middleware)

#### Erlang

+ [kerl](https://github.com/yrashk/kerl): 版本管理器, 用于管理 Erlang/OTP 实例, 类似于 RVM
+ [rabbitmq-server](https://github.com/rabbitmq/rabbitmq-server): RabbitMQ 消息队列 源码
+ [rabbitmq-tutorials](https://github.com/rabbitmq/rabbitmq-tutorials): RabbitMQ 教程
+ [ejabberd](https://github.com/processone/ejabberd): XMPP 协议的开源实现，用于及时聊天软件，Whatsapp 的聊天核心就是这个软件
+ [elixir](https://github.com/elixir-lang/elixir): 基于 Erlang VM 的一个语言，语法类似于 Ruby
+ [phoenix](https://github.com/phoenixframework/phoenix): 基于 Elixir 语言的 web 框架

#### Java

+ [elasticsearch](https://github.com/elasticsearch/elasticsearch): 开源的分布式搜索引擎，社区活跃，支持强大
+ [fastjson](https://github.com/alibaba/fastjson): 阿里开源的一款高效的 JSON 库

#### C/C++

+ [json](https://github.com/nlohmann/json): C++ 的 JSON 库
+ [simple-rtmp-server](https://github.com/winlinvip/simple-rtmp-server): 运营级的互联网直播服务器集群
+ [mozjpeg](https://github.com/mozilla/mozjpeg): JPEG 图片解码压缩，Mozilla 出品
+ [libsass](https://github.com/sass/libsass): SASS 的 C++ 实现
+ [QQStars](https://github.com/AfterTheRainOfStars/QQStars): 基于 WebQQ 协议和 QT 开发的 QQ 客户端
+ [caffe](https://github.com/BVLC/caffe): 一个关于数据挖掘的库
+ [fastsocket](https://github.com/fastos/fastsocket): 一个高扩展性的 Socket 库，在多核设备上有良好的表现，新浪出品
+ [C](https://github.com/ryanmjacobs/c): 将 C 语言校本化的一个工具, 可以直接编写 C 语言作为脚本使用

#### Go

+ [delve](https://github.com/derekparker/delve): Go 调试器
+ [go](https://github.com/golang/go): Go 源码
+ [beego](https://github.com/astaxie/beego): 国内大牛开发的 Web 框架
+ [revel](https://github.com/revel/revel): 全栈 Web 框架
+ [martini](https://github.com/go-martini/martini): 另一款 Web 框架
+ [pgweb](https://github.com/sosedoff/pgweb): PostgreSQL 的 Web 数据库浏览器

#### Lua

+ [lua-nginx-module](https://github.com/openresty/lua-nginx-module): 一个 Nginx 组件包, 可以使用 Lua 来开发 Nginx 插件, 将之变成一个全功能的 Web 应用服务器
+ [kong](https://github.com/Mashape/kong): 一个专注于可扩展, 高性能以及可靠性的 Restful API 框架


## IOS 或 OSX

+ [Harpy](https://github.com/ArtSabintsev/Harpy): 用于检测应用更新
+ [CRToast](https://github.com/cruffenach/CRToast): 现代、时髦的 IOS 通知提醒库
+ [Ono](https://github.com/mattt/Ono): IOS 或者 OSX 中用于处理 XML & HTML 的库
+ [CocoaMarkdown](https://github.com/indragiek/CocoaMarkdown): IOS 或者 OSX 中用于解析或者渲染 Markdown 的库
+ [Haneke](https://github.com/Haneke/Haneke): 一个用于缓存图片的 IOS 库，无需配置
+ [HanekeSwift](https://github.com/Haneke/HanekeSwift): Haneke 的 swift 版本
+ [RFQuiltLayout](https://github.com/bryceredd/RFQuiltLayout): 一个用于实现 IOS 端瀑布流的库
+ [kxmenu](https://github.com/kolyvan/kxmenu): 用于 IOS 上实现垂直菜单，支持上下左右等方向
+ [peertalk](https://github.com/rsms/peertalk): IOS 或者 OSX 中用于处理 USB 通信
+ [REMenu](https://github.com/romaonthego/REMenu): IOS 中用于实现下拉菜单效果
+ [RESideMenu](https://github.com/romaonthego/RESideMenu): IOS 中侧边栏的异步效果实现，类似于 QQ 中的侧边栏
+ [AwesomeMenu](https://github.com/levey/AwesomeMenu): IOS 中用于实现类似于 Path 应用菜单的效果，各种酷炫
+ [Alamofire](https://github.com/Alamofire/Alamofire): NFNetworking 的 Swift 版本
+ [Alcatraz](https://github.com/supermarin/Alcatraz): Xcode 的包管理工具
+ [JBChartView](https://github.com/Jawbone/JBChartView): IOS 的图表库
+ [PNChart](https://github.com/kevinzhow/PNChart): 基于 IOS 的强大图表库
+ [GPUImage](https://github.com/BradLarson/GPUImage): 基于 GPU 图片、视频处理库
+ [shenzhen](https://github.com/nomad/shenzhen): 一个用于构架和发布 IOS 的命令行工具
+ [ZXingObjC](https://github.com/TheLevelUp/ZXingObjC): ZXing(二维码、条形码扫描库) 的 Objective-C 实现
+ [PKRevealController](https://github.com/pkluz/PKRevealController): IOS 上一个非常优秀的，用于实现侧边栏的库
+ [KIF](https://github.com/kif-framework/KIF): IOS 功能测试框架
+ [Bolts-iOS](https://github.com/BoltsFramework/Bolts-iOS): 为了加快开发速度的相对低层级的库集合， Parse 和 Facebook 出品
+ [MaterialKit](https://github.com/nghialv/MaterialKit): 基于 Swift 实现的 Google Material Design 效果
+ [Carthage](https://github.com/Carthage/Carthage): 一个简单的、去中心化的 Cocoa 依赖管理库, Swift 编写，仅用于 IOS8.0 及 以后的系统
+ [JSONModel](https://github.com/icanzilb/JSONModel): 智能化的数据模型，有了它，再也不用手动解析JSON数据啦
+ [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground): 提供对 Objective-C 的 Playground 支持，比 Swift 更快
+ [RMStore](https://github.com/robotmedia/RMStore): 轻量级应用内购买库，集成方便，使用简单，方便项目中快速支持应用内购买
+ [pop](https://github.com/facebook/pop): Facebook开源出来的动画扩展库
+ [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController): 一个优美大方的即时聊天 UI 库
+ [realm-cocoa](https://github.com/realm/realm-cocoa): 一个移动端数据库，提供了丰富的数据支持，快速，且不依赖 SQLite
+ [Surge](https://github.com/mattt/Surge): Swift 的高效数学运算库，基于 [Accelerate](https://developer.apple.com/library/mac/documentation/Accelerate/Reference/AccelerateFWRef/_index.html)
+ [Masonry](https://github.com/Masonry/Masonry): OSX 和 IOS 上用来简化 Autolayout 约束的一个库
+ [Side-Menu.iOS](https://github.com/Yalantis/Side-Menu.iOS): 一款精美的侧边栏实现
+ [AsyncDisplayKit](https://github.com/facebook/AsyncDisplayKit): IOS 上的一款异步界面引擎, 非常流畅, Facebook 出品
+ [Kiwi](https://github.com/kiwi-bdd/Kiwi): IOS 的 BDD 测试框架
+ [PonyDebugger](https://github.com/square/PonyDebugger): IOS 的远程调试工具, 允许开发者在 Chrome Developer Tool 中调试 IOS 应用
+ [ObjectiveSugar](https://github.com/supermarin/ObjectiveSugar): 提供一些 Objective-C 的语法糖, 类似于 Ruby 的语法
+ [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON): Swift 的一个处理 JSON 的库
+ [Cartography](https://github.com/robb/Cartography): 在 Swift 中 声明式的使用 Autolayout
+ [HanekeSwift](https://github.com/Haneke/HanekeSwift): Swift 中可用来做缓存的库,对图片的支持尤佳
+ [RuntimeBrowser](https://github.com/nst/RuntimeBrowser): IOS 和 OSX 的运行时类浏览器, 可以查看运行时的头文件, 允许动态加载新模块
+ [iOS-Runtime-Headers](https://github.com/nst/iOS-Runtime-Headers): IOS 运行时头文件, 从RuntimeBrowser抽出
+ [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole): 应用内置用于 Debug 的控制台, 支持 UIWebView & WKWebView
+ [DBCamera](https://github.com/danielebogo/DBCamera): 方便高度自定义相机UI的库
+ [UIImage-Helpers](https://github.com/NZN/UIImage-Helpers): 截图、模糊化图片、生成特定颜色的图片，都可以由这个库完成
+ [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP): Swift 的 HTTP 封装
+ [VKVideoPlayer](https://github.com/viki-org/VKVideoPlayer): 方便高度自定义视频播放器的库
+ [MagicalRecord](https://github.com/magicalpanda/MagicalRecord): 基于 Core Data 之上的 ORM, 是 Active Record 的 IOS 版实现, 可以精简 Core Data 代码
+ [SQLite.swift](https://github.com/stephencelis/SQLite.swift): SQLite3 的 Swift 层接口实现
+ [panelkit](https://github.com/louisdh/panelkit): iOS 面板组件，可以用于创建非常灵活的面板


## Android

+ [Slidr](https://github.com/r0adkll/Slidr): 一个用于给 Activity 添加滑动消隐效果的库
+ [material_design_zh](https://github.com/1sters/material_design_zh): Material Design 的中文协同翻译
+ [galgo](https://github.com/inaka/galgo): Android 的日志工具，可以将日志显示在 Activity 的最上端，方便调试
+ [sweet-alert-dialog](https://github.com/pedant/sweet-alert-dialog): Sweet Alert Android 版本，用于应用内通知和提示
+ [Side-Menu.Android](https://github.com/Yalantis/Side-Menu.Android): 一款精美的侧边栏实现
+ [dagger](https://github.com/square/dagger): Android 和 Java 的依赖注入库
+ [picasso](https://github.com/square/picasso): 一款用于下载并缓存图片的库
+ [ArcAnimator](https://github.com/asyl/ArcAnimator): 实现 ARC 动画的库
+ [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart): 强大的图表工具


## 代码效率

#### CoffeeScript

+ [coffeescript](https://github.com/jashkenas/coffeescript): Coffeescript 源码

#### TypeScript

+ [DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped): 高质量的 TypeScript 资源汇总

#### Sublime Text

+ [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel): Sublime Text 的代码补全工具，支持多种语言
+ [Emmet](https://github.com/emmetio/emmet)：一个用于提高开发效率的编辑器插件，前身是Zen coding
+ [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3): 一个提供代码质量检测的插件
+ [SublimeTmpl](https://github.com/kairyou/SublimeTmpl)：快速新建指定的模版文件
+ [Syntax-highlighting-for-Sass](https://github.com/P233/Syntax-highlighting-for-Sass)：sass代码高亮插件
+ [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing): Sublime Text 强大的 Markdown 扩展, 提供快捷键, 主题等
+ [ApplySyntax](https://github.com/facelessuser/ApplySyntax/): 辅助检测语法插件
+ [CTags](https://github.com/SublimeText/CTags/): Sublime Text Ctags 支持插件, 需要安装 ctags
+ [sublime-react](https://github.com/reactjs/sublime-react): React 代码高亮


## 云计算

#### Docker

+ [kubernetes](https://github.com/GoogleCloudPlatform/kubernetes): Google 开源的 Docker 集中管控系统
+ [weave](https://github.com/zettio/weave): 用于为基于不同主机的 Docker Containers 创建一个虚拟网络

#### OS

+ [linux](https://github.com/torvalds/linux): linux 源码，Linus 大神之作，只能膜拜了
+ [smartos-live](https://github.com/joyent/smartos-live): Joyent 出品的用于云平台的智能 OS


## 开源产品(论坛、在线教育、项目管理等)

+ [Edx](https://github.com/edx/edx-platform): 在线教育平台源代码，Edx
+ [alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms): 开源 CMS 系统，基于 Rails
+ [flynn](https://github.com/flynn/flynn): 下一代 PAAS 服务产品，用于管理主机或者 AWS 实例
+ [jsgen](https://github.com/zensh/jsgen): 开源论坛、博客系统, 基于 Node.js, AngularJS, MongoDB
+ [libreboard](http://git.libreboard.com/libreboard/libreboard): [开源看板系统](https://github.com/libreboard/libreboard)，除了配色，长得几乎和 [Trello](https://trello.com) 一模一样
+ [paperwork](https://github.com/twostairs/paperwork): 开源笔记系统，类似于Evernote, Microsoft OneNote & Google Keep
+ [cabot](https://github.com/arachnys/cabot): 开源服务器监控服务
+ [firefox-ios](https://github.com/mozilla/firefox-ios): IOS 版 Firefox 源代码
+ [gogs](https://github.com/gogits/gogs): 一款开源 Git 托管服务，基于 GO 语言开发，类似于 Gitlab
+ [huginn](https://github.com/cantino/huginn): 个人代理监控，可以监控天气、Twitter、网站等等，并按照预设的条件发送通知给自己，功能强大！
+ [nodeclub](https://github.com/cnodejs/nodeclub): 社区系统，基于Node.js 和 MongoDB 开发
+ [keystone](https://github.com/keystonejs/keystone): 基于 Node.js 的 CMS 系统
+ [apostrophe](https://github.com/punkave/apostrophe): 基于 Node.js 的 CMS 系统
+ [reddit](https://github.com/reddit/reddit): Reddit 的源代码
+ [lets-chat](https://github.com/sdelements/lets-chat): 适合小团队的聊天服务, 可以自己搭建, 基于 Node.js 支持 Restful API, XMPP 等
+ [dokku](https://github.com/progrium/dokku): 基于 Docker 的 Mini-Heroku, 最小型的 PAAS 实现
+ [VLC](https://github.com/videolan/vlc): VLC 视频播放器源代码
+ [HackerNews-React-Native](https://github.com/iSimar/HackerNews-React-Native): HackerNews 基于 React Native 实现
+ [spree](https://github.com/spree/spree): 基于 Ruby on Rails 的开源在线电子商务网站
+ [v2ex](https://github.com/singro/v2ex): V2EX 的 IOS 源代码


## 代码规范&设计模式

#### Ruby

+ [Airbnb 的 ruby 代码编写规范](https://github.com/airbnb/ruby): Airbnb 的 ruby 代码编写规范

###### Rails

+ [Rails 代码编写规范](https://github.com/bbatsov/rails-style-guide): Rails 代码编写规范

#### Javascript

+ [umd](https://github.com/umdjs/umd): 全局模块定义, 提供了几种模块定义规则和模式, 使其可以支持 AMD/CMD/浏览器全局/jQuery插件等

###### AngularJS

+ [angularjs-styleguide](https://github.com/toddmotto/angularjs-styleguide): AngularJS 代码规范
+ [Angular-Design-Patterns-Best-Practices](https://github.com/trochette/Angular-Design-Patterns-Best-Practices): Angular 设计模式的最佳实现

#### Java

+ [java-design-patterns](https://github.com/iluwatar/java-design-patterns): Java 设计模式

###### Android

+ [android-best-practices](https://github.com/futurice/android-best-practices): Android 开发最佳实践

#### Bash

+ [bashstyle](https://github.com/progrium/bashstyle): Bash 代码编写规范

#### Objective-C

+ [objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide): Objective-C 代码编写规范，New York Times 出品

###### IOS

+ [ios-good-practices](https://github.com/futurice/ios-good-practices): IOS 开发最佳实践

#### Swift

+ [swift-style-guide](https://github.com/raywenderlich/swift-style-guide): Swift 代码编写规范

#### Design

+ [web-design-standards](https://github.com/18F/web-design-standards): 网站设计标准（美国政府网站）


## 数据库

+ [postgrest](https://github.com/begriffs/postgrest): PostgreSQL 的 RESTful API
+ [pgcli](https://github.com/amjith/pgcli): PostgreSQL 命令行工具，提供高亮和自动补全
+ [mongo](https://github.com/mongodb/mongo): MongoDB 源代码
+ [nedb](https://github.com/louischatriot/nedb): 纯 Javascript 实现，类 MongoDB 的内存型数据库，API 基本和 MongoDB相同，可选同步写入磁盘，小项目数据不太多时性能很强乃至超过MongoDB
+ [TokuMX MongoDB](https://github.com/Tokutek/mongo): TokuMX 版的 MongoDB, MongoDB 的一个分支，支持更快的写速度，完整的事务支持等
+ [sequelpro](https://github.com/sequelpro/sequelpro): Mac OSX 的 MySQL 数据库管理软件


## 博客 / 网站

#### 设计

+ [Dribble](https://dribbble.com/): 设计师必上的网站，各种设计资源、创意、分享等
+ [Design Museum](https://designmuseum.org/): 当代前沿设计，涉及设计的各个领域
+ [Behance](https://www.behance.net/): 创意&设计资源集合，Adobe 旗下网站(应用)
+ [Awwwards](http://www.awwwards.com/): 一家筛选评比互联网上最佳网站设计开发的网站
+ [gooood](http://www.gooood.hk/): 建筑，景观，设计，艺术在线杂志
+ [ui4app](http://ui4app.com/): 专注于 IOS UI 的一个网站，提供各种设计资源
+ [wookmark](http://www.wookmark.com/): 这上面有分享的各种各样的美图、设计等

#### 技术

+ [code4app](http://code4app.com/): 专注于IOS 代码的一个网站，提供各种功能实现 Demo
+ [CSS Tricks](http://css-tricks.com/): 各种 CSS 技巧
+ [html5rocks](http://www.html5rocks.com/en/): 提供各种各样关于 HTML5 的资讯
+ [html5weekly](http://html5weekly.com/): 提供各种各样关于 HTML5 的资讯和技巧
+ [rubyweekly](http://rubyweekly.com/): 提供各种各样关于 Ruby 的资讯和技巧
+ [javascriptweekly](http://javascriptweekly.com/): 提供各种各样关于 Javascript 的资讯和技巧
+ [ng-newsletter](http://www.ng-newsletter.com/): 提供各种各样关于 Angular 的资讯和技巧
+ [cnodejs](https://cnodejs.org/): 国内最大最火 Node.js 社区
+ [ruby-china](https://ruby-china.org/): 国内最大最火 Ruby 社区
+ [angularjs](http://angularjs.cn/): Angularjs 的国内中文社区


## 书籍 / 阅读 / 学习

#### Awesome 系列

+ [awesome](https://github.com/sindresorhus/awesome): awesome系列祖师爷，资源汇总的汇总 😄
+ [awesome-android-libraries](https://github.com/wasabeef/awesome-android-libraries): Android 各种开源库的一个汇总
+ [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui): Android 各种开源UI/UX库的一个汇总
+ [awesome-courses](https://github.com/prakhar1989/awesome-courses): 关于计算机科学的各种大学教学课程
+ [awesome-ruby](https://github.com/markets/awesome-ruby): Ruby 资源集合
+ [awesome-go](https://github.co m/avelino/awesome-go): Go 资源集合
+ [awesome-cpp](https://github.com/fffaraz/awesome-cpp): C++ 的资源集合
+ [awesome-elixir](https://github.com/h4cc/awesome-elixir): Elixir 资源集合
+ [awesome-emacs](https://github.com/emacs-tw/awesome-emacs): Emacs 资源整合
+ [awesome-apple](https://github.com/joeljfischer/awesome-apple): 关于苹果开发的插件/库/文章等资源
+ [awesome-swift)](https://github.com/matteocrippa/awesome-swift): Swift 资源整合
+ [awesome-react](https://github.com/enaqx/awesome-react): React 资源整合
+ [awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo): 一系列前端性能优化集合
+ [awesome-angularjs](https://github.com/gianarb/awesome-angularjs): AngularJS 资源整合
+ [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) : Node.js 资源整合
+ [awesome-php](https://github.com/ziadoz/awesome-php) : PHP 资源整合
+ [awesome-python](https://github.com/vinta/awesome-python) : Python 资源整合
+ [awesome-autoit](https://github.com/J2TeaM/awesome-AutoIt) : 第三方定制开源软件合集
+ [awesome-books](https://github.com/ruby-vietnam/awesome-books): 一些很不错的开发书籍
+ [awesome-npm](https://github.com/sindresorhus/awesome-npm.git): Npm 相关资源整合
+ [awesome-sysadmin-cn](https://github.com/jobbole/awesome-sysadmin-cn): 伯乐出品的系统管理员资源大全
+ [awesome-ios-cn](https://github.com/jobbole/awesome-ios-cn): 伯乐出品的 iOS 资源大全
+ [awesome-java-cn](https://github.com/jobbole/awesome-java-cn): 伯乐出品的 Java 资源大全
+ [awesome-python-cn](https://github.com/jobbole/awesome-python-cn): 伯乐出品的 Python 资源大全
+ [awesome-c-cn](https://github.com/jobbole/awesome-c-cn): 伯乐出品的 C 资源大全
+ [awesome-cpp-cn](https://github.com/jobbole/awesome-cpp-cn): 伯乐出品的 C++ 资源大全
+ [awesome-mysql-cn](https://github.com/jobbole/awesome-mysql-cn): 伯乐出品的 MySQL 资源大全
+ [awesome-machine-learning-cn](https://github.com/jobbole/awesome-machine-learning-cn): 伯乐出品的机器学习资源大全
+ [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning): 机器学习资源整合
+ [awesome-javascript-cn](https://github.com/jobbole/awesome-javascript-cn): 伯乐出品的 JavaScript 资源大全
+ [awesome-css-cn](https://github.com/jobbole/awesome-css-cn): 伯乐出品的 CSS 资源大全
+ [awesome-php-cn](https://github.com/jobbole/awesome-php-cn): 伯乐出品的 PHP 资源大全
+ [awesome-graphql](https://github.com/chentsulin/awesome-graphql): Graphql 资源大全
+ [awesome-falsehood](https://github.com/kdeldycke/awesome-falsehood): 谬误大全, 懂得谬误, 才能更接近真理~
+ [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers): 深度学习论文大全
+ [awesome-webpack-cn](https://github.com/webpack-china/awesome-webpack-cn): webpack优秀中文文章
+ [awesome-blockchain](https://github.com/coderplex/awesome-blockchain): 区块链资源整合
+ [awesome-mac](https://github.com/jaywcjlove/awesome-mac): Mac 资源整合

#### 前端

###### Web
+ [Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions): 各种前端面试问题
+ [Front-End-Develop-Guide](https://github.com/icepy/Front-End-Develop-Guide): 汇集了前端开发的主流学习资源
+ [what-happens-when](https://github.com/alex/what-happens-when): 一篇文章，详细解释了从在浏览器中输入网址之后发生的一切
+ [backbone-fundamentals](https://github.com/addyosmani/backbone-fundamentals): 关于 Backbone 的一本书，初学和高级都适用
+ [http2-spec](https://github.com/http2/http2-spec): HTTP 2 草案
+ [grid](https://github.com/aekaplan/grid): 响应式布局指南
+ [fks](https://github.com/JacksonTian/fks): 前端技能汇总
+ [AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning): AngularJS 的各种学习资源
+ [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS): 一个 Javascript 系列图书，主要讲述 JS 的核心概念和机制
+ [JavaScript-Garden](https://github.com/BonsaiDen/JavaScript-Garden): 一个关于 Javascript 的诡异特性集合
+ [在控制台中调试 AngularJS 应用](http://lyfeyaj.com/2015/01/07/debugging-angularjs-apps-from-the-console/): 在控制台中调试 AngularJS 应用的几种方法
+ [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/): 学习 Javascript 设计模式
+ [es6features](https://github.com/lukehoban/es6features): ECMAScript 6 特性概览
+ [es6-tools](https://github.com/addyosmani/es6-tools): ECMAScript 6 工具集合
+ [frontend-guidelines](https://github.com/bendc/frontend-guidelines): 前端指南, 主要讲述 HTML, CSS 和 JS 的最佳实践
+ [es6tutorial](https://github.com/ruanyf/es6tutorial): 《ECMAScript 6入门》是一本开源的JavaScript语言教程，全面介绍ECMAScript 6新增的语法特性。
+ [AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning): AngularJS 学习资源
+ [practical-ui-physics](https://github.com/desandro/practical-ui-physics): 各种前端物理效果的实现原理
+ [understandinges6](https://github.com/nzakas/understandinges6): 电子书： Understanding ES6
+ [frontend-stuff](https://github.com/moklick/frontend-stuff): 前端相关的各种资源, JS 内容居多
+ [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks): 前端开发资源的集合, 内容极多

###### React

+ [React 中文文档](http://reactjs.cn/react/docs/getting-started-zh-CN.html): React 中文文档
+ [Redux 英文文档](http://redux.js.org/docs/introduction/): Redux 英文文档, 比较详尽
+ [Redux 中文文档](http://cn.redux.js.org/index.html): Redux 中文文档, 比较详尽

###### IOS
+ [30min_guides](https://github.com/qinjx/30min_guides): 覃健祥的学习笔记，若干个几十分钟入门的文档
+ [The Swift Programming Language 中文版](http://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/): The Swift Programming Language 中文版, 苹果官方教程的中文翻译
+ [cocoacontrols](https://www.cocoacontrols.com/): 包含各种 OSX 或者 IOS 的开源 UI 库或者 商业库
+ [iOS 学习资料整理](https://github.com/Aufree/trip-to-iOS): IOS 的各种学习资料整理，初学者必备

###### Android

+ [android-training-course-in-chinese](https://github.com/kesenhoo/android-training-course-in-chinese): Google Android官方培训课程中文版
+ [AndroidDevTools](https://github.com/inferjay/AndroidDevTools): Android 收集整理Android开发所需的Android SDK、开发中用到的工具、Android开发教程、Android设计规范，免费的设计素材等

#### 后端

###### Node.js

+ [node-lessons](https://github.com/alsotang/node-lessons): Node.js 包教不包会
+ [node-books](https://github.com/pana/node-books): 关于 Node.js 的一些书籍
+ [art-of-node](https://github.com/maxogden/art-of-node): Node的艺术, 一本简短的书，旨在介绍 Node
+ [Node.js 实战](http://nodejs.ucdok.com/): 以实战开发中的应用为例的讲解
+ [http://nodeschool.io/](http://nodeschool.io/): 基于 Node.js 打造的、跑在终端上的开源教学课程。
+ [stream-handbook](https://github.com/jabez128/stream-handbook): 讲解 Node Stream(流) 的详细教程,中文版
+ [7-days-nodejs](https://github.com/nqdeng/7-days-nodejs): 七天学会 Node.js

###### Ruby

+ [fast-ruby](https://github.com/JuanitoFatas/fast-ruby): 怎样写出更快的 Ruby

###### PHP

+ [phpbook](https://github.com/walu/phpbook): PHP扩展开发及内核应用
+ [tipi](https://github.com/reeze/tipi): 深入理解PHP内核
+ [php-the-right-way](https://github.com/wulijun/php-the-right-way): PHP之道

###### Go

+ [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang): beego 作者写的关于怎么使用 Go 语言开发 web 应用的书

###### Bash

+ [bash-handbook](https://github.com/denysdovhan/bash-handbook): Bash 手册，教你如何学习 Bash

###### 接口

+ [http-api-design](https://github.com/interagent/http-api-design): 从 Heroku 接口总结出的，如何更好地设计 API 接口

#### 算法 & 论文

+ [The-Art-Of-Programming-By-July](https://github.com/julycoding/The-Art-Of-Programming-By-July): 程序员编程艺术：面试和算法心得
+ [papers-we-love](https://github.com/papers-we-love/papers-we-love): 计算机科学学术论文的一个集合，内容丰富有深度
+ [Tensorflow 中文文档](https://github.com/jikexueyuanwiki/tensorflow-zh): 人工智能系统 Tensorflow 的中文文档

#### 其他

+ [til](https://github.com/thoughtbot/til): 今天我们学了什么，thoughtbot 出品，建议 watch
+ [tenant-point](https://github.com/soulteary/tenant-point): 租房要点，适用于北上广深杭
+ [linux-insides](https://github.com/0xAX/linux-insides): 关于 Linux 内核的一些知识
+ [慕课网](http://www.imooc.com/): 在线学习平台，各种编程学习资源
+ [alternative-internet](https://github.com/redecentralize/alternative-internet): 一些有趣的新型互联网和技术,主要目的是去中心化
+ [cocktails_for_programmers](https://github.com/the-teacher/cocktails_for_programmers): 程序员鸡尾酒, 一个特意为专业节日“程序员日”而建立的鸡尾酒项目！“程序员日”在每年的第256天。
+ [Wait but Why?](http://waitbutwhy.com/): 非常有意思的一个网站, 会有一些有趣的观点和文章
+ [ideas](https://github.com/samsquire/ideas): 有趣的想法, 更多是一个作者对于编程/软件/工具 的思考和整理
+ [Developing_iOS_8_Apps_With_Swift](https://github.com/X140Yu/Developing_iOS_8_Apps_With_Swift): 斯坦福大学公开课： 如何使用 Swift 开发 iOS8 应用
+ [Open Source Guide](https://github.com/github/open-source-guide): Github 出品，教你如何做开源项目
+ [Design Patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans): 真正给人看的设计模式


## 科学上网

+ [ShadowVPN](https://github.com/clowwindy/ShadowVPN): 科学上网之 VPN
+ [shadowsocks](https://github.com/shadowsocks/shadowsocks): 科学上网利器(服务器端) ~ 墙外的世界丰富多彩
+ [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android): shadowsocks 安卓客户端
+ [gfwlist2pac](https://github.com/clowwindy/gfwlist2pac): 科学上网之 GFWlist to Pac
+ [PPTP VPN 搭建](https://edgepeek.com/articles/144-ubuntu-12-dot-04-shang-pptp-vpn-da-jian): PPTP VPN 搭建教程
+ [Google-IPs](https://github.com/justjavac/Google-IPs): Google 全球 IP 地址库
+ [RevokeChinaCerts](https://github.com/chengr28/RevokeChinaCerts): 一次性删除所有 CNNIC 证书的工具
+ [lantern](https://github.com/getlantern/lantern): 新一代翻墙工具, 借助于P2P, 速度很快
+ [hosts](https://github.com/racaljk/hosts): 科学上网专用Hosts


## Git 相关

+ [gitolite](https://github.com/sitaramc/gitolite): 用于构建 Git 服务器
+ [lolcommits](https://github.com/mroth/lolcommits): 给自己的 git commit
+ [scm_breeze](https://github.com/ndbroadbent/scm_breeze): Git 流程的辅助简化工具
+ [gitlet](https://github.com/maryrosecook/gitlet): Javascript 实现的 Git
+ [js-git](https://github.com/creationix/js-git): Git 的 Javascript 实现


## 其他

+ [retter](https://github.com/maciejczyzewski/retter): 密码学相关的算法库
+ [uBlock](https://github.com/gorhill/uBlock): Chrome, Firefox, Safari 插件用来屏蔽内容（如广告等），可自定义
+ [rust](https://github.com/rust-lang/rust): Rust 语言源码
+ [font-spider](https://github.com/aui/font-spider): 中文 WebFont 自动化压缩工具
加一张杀马特的照片
+ [github-awesome-autocomplete](https://github.com/algolia/github-awesome-autocomplete): Github 的浏览器插件, 用于辅助搜索, 更加人性化的搜索结果
+ [dotenv](https://github.com/bkeepers/dotenv): 用于配置本地环境, 可以为不同的文件夹设置不同的环境
+ [No more secrets](https://github.com/bartobri/no-more-secrets): 科幻电影中的解密效果
+ [chinese-programmer-wrong-pronunciation](https://github.com/shimohq/chinese-programmer-wrong-pronunciation): 中国程序员容易发音错误的单词
+ [programmer-job-blacklist](https://github.com/shengxinjing/programmer-job-blacklist): 程序员找工作黑名单，换工作和当技术合伙人需谨慎啊
+ [movies-for-hackers](https://github.com/k4m4/movies-for-hackers): 黑客和科幻迷必看电影


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).


