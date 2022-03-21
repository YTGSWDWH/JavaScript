# JavaScript

一、语法基础

    1.一个完整的JavaScript实现应该包括：ECMAScript、DOM和BOM
    2.使用了src属性的<script>元素不应该再在<script>和</script>标签中再包含其他JavaScript代码。如果两者都提供的话，则浏览器只会下载并执行脚本文件，从而忽略行内代码。
    3.HTML 4.01为<script>元素定义了一个叫defer的属性。这个属性表示脚本在执行的时候不会改变页面的结构。也就是说，脚本会被延迟到整个页面都解析完毕后再进行。因此，在<script>元素中设置defer属性，相当于告诉浏览器立即下载，但延迟执行。
    4.可以使用多个<script>元素来使用多个外部js文件
    5.js中严格区分大小写
    6.除了0，NAN，undefined，null以及空字符串，其他bool值都是true
    7.任何数和NAN做运算，结果都是NAN
    8.在网页中使用Unicode编码：&#编码，这里的编码需要使用十进制
    9.prompt()可以弹出一个提示框，该提示框中会带有一个文本框
