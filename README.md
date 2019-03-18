# vue-electron-music

> nodejs、vue、electron制作的网易云音乐客户端(MacOs)版，目前没有在Windows运行过，所以样式可能有点差异，时间不足，有空再更新。

[运行效果预览视频](http://v.youku.com/v_show/id_XMjk2MzYxODUyMA==.html?spm=a2hzp.8244740.0.0)

### 技术栈
- vue全家桶(vue vue-router vuex)
- electron(应用框架)
- request(请求数据)
- ES6
- SCSS
- 更多...

## 图片预览
![](https://github.com/eugeneCN/vue-electron-music/blob/master/doc/3872766167-5999ac798b713_articlex.png)
![](https://github.com/eugeneCN/vue-electron-music/blob/master/doc/3913213729-5999ac98a8c6c_articlex.jpeg)
![](https://github.com/eugeneCN/vue-electron-music/blob/master/doc/1588237435-599597952042d_articlex.jpeg)

## 安装运行（Build Setup）

> 确保项目正常运行，请将你的node版本升级为7.0+以上，低版本node没有测试过。

``` bash

# 克隆项目
git clone https://github.com/eugeneCN/vue-electron-music.git

# 安装依赖
npm install

# 启动api localhost:3000
cd api/
npm install
npm start

# 启动本地服务 localhost:9080
npm run dev

# 打包成本地应用
npm run build

# 开启控制台
Ctrl + Shift + i

```

## 鸣谢

此应用提供的API: [https://github.com/Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) ,此接口的说明请到这里[查看](https://binaryify.github.io/NeteaseCloudMusicApi/#/)
