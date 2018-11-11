# service-mini

> A Mpvue project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


https://www.jianshu.com/p/2c363ea29cda
https://blog.csdn.net/abczdefg/article/details/54407526

基础框架
https://blog.csdn.net/qq_31393401/article/details/80728523

mpvue注意事项
https://www.jianshu.com/p/184db91b101d

icon
http://www.fontawesome.com.cn/faicons/

https://lbs.qq.com/product/miniapp/jssdk/
https://blog.csdn.net/zhongguohaoshaonian/article/details/80870415
LT5BZ-BLKW3-MKP3M-YB3AY-IQSWK-GUFLN

// 画图开源框架
https://juejin.im/post/5b40b158e51d4518f543c7b0

https://developers.weixin.qq.com/community/develop/doc/166eb4bdf352f67a45e993a0bfdc2025

简单的，就是通过canvas绘制而成的图片。

1、在wxml中放置<canvas canvas-id="myCanvas"/>标签。

2、创建canvas绘图上下文： const ctx = wx.createCanvasContext('myCanvas');

3、通过wx.download()接口下载你要绘制的图片素材，获得一个临时路径tempFilePath。

4、调用canvas的drawImage接口将图片素材（第3步的tempFilePath）绘制到canvas画布上面。

ctx.drawImage(tempFilePath,0,0,100,100);

ctx.draw();//绘制完成

5、绘制完成之后将画布导出图片，并获得临时路径tempFilePath，具体接口如下

wx.canvasToTempFilePath();

6、最好调用预览图片接口，传入第5步的tempFilePath，预览您生成的图片，具体接口如下

wx.previewImage();

https://github.com/davidlin88/mpvue-vuex-demo/blob/master/src/http/api.js