# JS-effects
## 烟花点击效果
代码来源：https://www.onesrc.cn/p/add-a-fireworks-click-effect-to-your-website.html
https://cdn.jsdelivr.net/gh/kaygb/blog-images/fireworks.js
### 同步加载
~~~html
<script src="//cdn.jsdelivr.net/gh/kaygb/JS-effects/fireworks.js"></script>
~~~
### JS监听加载（测试）
~~~html
<script>
window.onload = function() {
        setTimeout(function() {
                let script = document.createElement("script");
                script.src = "//cdn.jsdelivr.net/gh/kaygb/JS-effects/fireworks.js";
                document.body.appendChild(script);
        }, 2e3);
}
</script>
~~~
[![](https://data.jsdelivr.com/v1/package/gh/kaygb/JS-effects/badge)](https://www.jsdelivr.com/package/gh/kaygb/JS-effects)
