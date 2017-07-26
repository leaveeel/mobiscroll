# select
1.部分样式可以在css文件内修改，滚动选项高度和部分样式可以在js文件内修改；
2.使用ajax调用数据需要将$(function(){ }); 放在ajax sucess内，否则仅有样式，滚动无法生效，无法获取数据；
3.onSelect方法为点击"确定"后的事件，更多方法在官网API DOCUMENT内；
4.select方法暂时不知道怎么显示三列，并且无法获得</optgroup>的label值，获取</option>文本和value值的方法在onSelect方法内； 
5.select方法仅返回</option>文本，可隐藏</input>自制显示层，模拟点击，自定义返回文本，但会出现双击才能触发的问题；
6.模拟点击方法为$(inputId).focus()；
# treelist
7.多列表可以选用treelist方法，具体用法见treelist.html；
8.treelist方法获取值为index值，解决方法可同5；
9.treelist获取值方法在onSelect内

10.更多mobiscroll方法可以查看官网，demo地址https://demo.mobiscroll.com/v3/number
11.api文档地址https://docs.mobiscroll.com/