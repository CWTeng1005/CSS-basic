## 标签选择器  

- 结构：标签名 { css属性名:属性值; }  
- 作用：通过标签名，找到页面中所有这类标签，设置样式  
- 注意点：  
    > - 标签选择器选择的是一类标签，而不是单独某一个  
    > - 标签选择器无论嵌套关系有多深，都能找到对应的标签  
    > - eg：2.1  

## 类选择器  

- 结构：.类名 { css属性名:属性值; }  
- 作用：通过类名，找到页面中所有带有这个类名的标签，设置样式  
- 注意点：  
    > - 所有标签上都有class属性，class属性的属性值称为类名  
    > - 类名可以由数字、字母、下划线、中划线组成，但不能以数字或者中划线开头  
    > - 一个标签可以同时有多个类名，类名之间以空格隔开  
    > - 类名可以重复，一个类选择器可以同时选中多个标签
    > - 优先级大于标签选择器    
    > - eg: 2.2  

## id选择器  

- 结构： #id属性值 { css属性名:属性值; }  
- 作用：通过id属性值，找到页面中带有这个id属性值的标签，设置样式  
- 注意点：  
    > - 配合js使用（后期）  
    > - 所有标签上都有id属性  
    > - id属性值类似于身份证号码，在一个页面中是唯一的，不可重复的！  
    > - 一个标签上只能有一个id属性值  
    > - 一个id选择器只能选中一个标签  
    > - eg: 2.3  

## 通配符选择器  

- 结构：* { css属性名:属性值; }  
- 作用：找到页面中所有的标签，设置样式  
- 注意点：  
    > - 开发中使用极少，只会在极特殊情况下才会用到  
    > - 可用于去除标签默认的margin和padding  

--- 

## 学习资料

- 视频：<a href="https://www.bilibili.com/video/BV1Kg411T7t9?spm_id_from=333.788.player.switch&vd_source=0af3f3aee70186db0ff8b48dc6b2a415&p=47">前端开发入门教程，web前端零基础html5 + css3 + 前端项目视频教程</a>