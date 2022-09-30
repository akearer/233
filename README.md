一些js和css文件(❁´◡`❁)

## Nprogress

来自 [查看出处](https://blog.zhixuan.dev/posts/ac760353/)

```
<script
    src="https://cdn.jsdelivr.net/gh/akearer/233/js/nprogress.min.js"
    integrity="sha384-bHDlAEUFxsRI7JfULv3DTpL2IXbbgn4JHQJibgo5iiXSK6Iu8muwqHANhun74Cqg"
    crossorigin="anonymous"
></script>
<link
    rel="stylesheet"
    href="https://cdn.staticaly.com/gh/akearer/233@main/css/nprogress.css"
    integrity="sha384-JnFERzKIvXoP1L2xm0h5BOEc+ETb/0tW/yjgrqz7WafSB+XnSOqVQATznWoE8WWX"
    crossorigin="anonymous"
/>
<script>
    NProgress.start();
    document.addEventListener("readystatechange", () => {
        if (document.readyState === "interactive") NProgress.inc(0.8);
        if (document.readyState === "complete") NProgress.done();
    });
</script>
```

注：自己改了一下进度条的颜色…