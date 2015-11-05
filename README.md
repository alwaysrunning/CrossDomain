# CrossDomain

js跨域是指通过js在不同域下面进行数据传输和通信。

在js中，XMLHttpRequest只能是在同一个域下面才能请求到数据，而跨域之后就请求不到数据了，针对js跨域请求有以下几种方法解决：

1. Jsonp

2. window.name

3. postMessage

根据实际情况来采用相应的方法

Jsonp需要服务端配合，postMessage不兼容ie6,7. window.name用的比较多
