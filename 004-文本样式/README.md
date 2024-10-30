## 文本缩进  

- 属性名：text-indent  
- 取值：  
    - 数字 + px  
    - 数字 + em（推荐：1em = 当前标签的font-size的大小）
- eg：4.1  

## 文本水平对齐方式  

- 属性名：text-align  
- 取值：  
    > - left：左对齐  
    > - center：居中对齐  
    > - right：右对齐  
- 注意点：  
    > 如果需要让文本水平居中，text-align属性给文本所在标签（文本的父元素）设置  
- eg：4.2  

## 文本修饰  

- 属性名：text-decoration  
- 取值：  
    > underline：下划线  
    > line-through：删除线  
    > overline：上划线  
    > none：无装饰线  
- 注意点：  
    > 开发中会使用text-decoration: none; 清除a标签默认的下划线  
- eg：4.3  

## 行高  

- 作用：控制一行的上下行间距  
- 属性名：line-height  
- 取值：  
    > - 数字+px  
    > - 倍数（当前标签font-size的倍数  
- 应用：   
    > - 让单行文本垂直居中可以设置line-height: 文字父元素高度  
    > - 网页精准布局时，会设置line-height: 1，可以取消上下间距  
- 行高与font连写的注意点：  
    > - 如果同时设置了行高和font连写，注意覆盖问题  
    > - font: style weight size/line0height family;  

---  

## 学习资料

- 视频：<a href="https://www.bilibili.com/video/BV1Kg411T7t9?spm_id_from=333.788.player.switch&vd_source=0af3f3aee70186db0ff8b48dc6b2a415&p=55">前端开发入门教程，web前端零基础html5 + css3 + 前端项目视频教程</a>