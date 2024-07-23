
HTML 文档（通常指的是通过 DOM (Document Object Model) 与之交互的网页）提供了多种方法来访问和操作网页的内容。以下是一些主要的方法：

getElementById(): 返回具有指定 ID 的元素。


```JAVASCRIPT
var element = document.getElementById("myId");
```

getElementsByTagName(): 返回包含具有指定标签名的所有元素的 NodeList。
```JAVASCRIPT

var elements = document.getElementsByTagName("myTag");
```
getElementsByClassName(): 返回包含具有指定类名的所有元素的 NodeList。   
```JAVASCRIPT
var elements = document.getElementsByClassName("myClass");
```
querySelector(): 返回与指定选择器匹配的第一个元素。
```JAVASCRIPT
    var element = document.querySelector("#myId");
    var element = document.querySelector(".myClass");
    var element = document.querySelector("myTag");
    var element = document.querySelector("myTag.myClass");
    var element = document.querySelector("myTag#myId");
    var element = document.querySelector("myTag.myClass#myId");
    var element = document.querySelector("myTag[attribute]");
    var element = document.querySelector("myTag[attribute=value]");
    var element = document.querySelector("myTag[attribute~=value]");
    var element = document.querySelector("myTag[attribute|=value]");
    var element = document.querySelector("myTag[attribute^=value]");
    var element = document.querySelector("myTag[attribute$=value]");
    var element = document.querySelector("myTag[attribute*=value]");
    var element = document.querySelector("myTag:active");
    var element = document.querySelector("myTag:checked");
    var element = document.querySelector("myTag:disabled");
    var element = document.querySelector("myTag:empty");
    var element = document.querySelector("myTag:enabled");
    var element = document.querySelector("myTag:first-child");
    var element = document.querySelector("myTag:first-of-type");
    ```
    querySelectorAll(): 返回与指定选择器匹配的所有元素的 NodeList。
    ```JAVASCRIPT
    var elements = document.querySelectorAll("#myId");
    ```
