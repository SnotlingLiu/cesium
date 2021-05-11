
# Get Started

在首次使用之前请执行打包命令,在Source文件夹下生成对应的文件索引方便直接引入,其命令如下:

``` npm
npm run release
```

安装依赖

``` npm
npm install
```

依赖安装完成后,可以直接在Example文件夹下根据template.html模板文件进行开发.
主要思路就是将Source文件夹中的Cesium.ts索引文件以AMD的方式进行引入后设置Cesium的全局CESIUM_BASE_URL地址即可.
