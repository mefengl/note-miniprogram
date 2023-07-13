# note-miniprogram

## 获取可以直接使用的小程序构建产物

以`tdesign`为例，获取`tdesign`的小程序构建产物，可以直接使用。

```shell
npm i tdesign-miniprogram -S --production
```

微信开发者工具里，菜单栏：工具 -> 构建 npm

miniprogram_npm 目录下的同名目录，即为构建产物。

> 可以看到同时还有`dayjs`的构建产物，不用管，因为`tdesign-miniprogram`目录中同样包含`dayjs`的构建产物。
