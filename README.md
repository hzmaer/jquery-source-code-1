# jquery-source-code-1

jquery源码分析(2.0.3版本)

大概内容大纲

(function(){

(21,94)       定义了一些变量和函数 jQuery=function(){}

(96,284)      给JQ对象添加一些方法和属性

(285,347)     extend:JQ的继承方法

(349,817)     jQuery.extend扩展一些工具方法

(877,2856)    Sizzle 复杂选择器的实现

(2880,3042)   callbacks：回调函数：对函数的统一管理

(3043,3183)   deferred:延迟对象：对异步的统一管理

(3184,3295)   support：功能检测

(3308,3652)   data():数据缓存

(3653,3797)   queue():队列管理

(3803,4299)   attr(),prop()等对元素属性的操作

(4300,5128)   on(),trigger()事件操作相关方法

(5140,6057)   DOM操作：添加，删除，获取，包装，DOM刷选

(6058,6620)   css()样式的操作

(6621,7854)   提交的数据和ajax():ajax(),json().onload()

(7855,8584)   animate():运动的方法

(8585,8792)   offset():位置和尺寸的方法

(8804,8821)  JQ支持模块化的模式

(8826)       window.$=window.jQuery=jQuery;

})();
