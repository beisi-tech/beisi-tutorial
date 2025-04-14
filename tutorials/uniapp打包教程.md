1.如何打包 H5,以开发者举例![alt text](image11.png)
首先进入 src/config.js 把服务器的 url 配置一下，url 注释有说如何写，如何点击页面最上反标题那边的发行，在后面有一个![alt text](image12.png)，网站 pc-web 发行。点一下，如何把网站域名![alt text](image13.png)，写一下，如何等待一会，就会给三个文件![alt text](image14.png)，如何这三个文件放到宝塔服务器上面对应的 h5 目录下就行

2.如何打包 apk
点击发行的 APP 打包，![alt text](image15.png) ， 然后选择自有证书，key 文件在 golden-store/前端/hsck.keystore，然后输入证书密码 123123，私钥密码也是 123123，别名 hsck，然后点击打包就 ok 了。然后出现一个 apk 文件。然后有时候需要改版本号，请在前端目录下的 manifest.json 中![alt text](image16.png) ，修改对应的版本号即可

以上图片全部放到了 beisi-tutorial\src\image 目录下面
