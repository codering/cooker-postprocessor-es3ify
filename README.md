# cooker-postprocessor-es3ify
 convert ES5 syntax to be ES3-compatible

基于[es3ify](https://github.com/spicyj/es3ify)

install: 

npm i -g cooker-postprocessor-es3ify

usage： 

```js
fis.match('/components/antd/lib/**.js', {
    postprocessor: fis.plugin("es3ify")
})

```

其他类似工具
[https://github.com/sorrycc/es3ify-loader](https://github.com/sorrycc/es3ify-loader)