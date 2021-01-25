# AllMusicApi

这里储存了公开使用的AllMusic外置Api,需要配合 [插件](https://github.com/HeartAge/AllMusic_P) 使用

### 使用方法
* 1.修改AllMusic服务端插件插件配置"config.json"中"Music_Url"一条为下列提供的api
  ```json
  "Music_Url": "api地址",
  ```
* 2.修改"config.json"中"Music_Api"一条为2
  ```json
  "Music_Api": 2,
  ```
* 3.输入/music reload 重载插件配置
* 4.享受外置api

### 注意事项
* 1.不要登录,不要登录,不要登录,请保持"config"中"LoginUser"和"LoginPass"两条为空
  ```json
  "LoginUser": "",
  "LoginPass": "",
  ```
* 2.我们无偿提供公开api,请不要滥用服务
* 3.若发现失效的api,请发出issues
* 4.我们不保证下列api是安全的,如有疑虑,请不要使用

### API地址列表
* http://music.s-yh-china.com
* https://api.aliserver.net/zmusicapi
* http://api.mirai.cloud:3000

### 加入此列表
如果您也想为这份列表做贡献,您可以发起pr或issues提供您的api

### 外置api搭建教程
> 还是直接看 [这个](https://binaryify.github.io/NeteaseCloudMusicApi) 比较靠谱
* 1.安装nodejs
* 2.复制[此仓库](https://github.com/Binaryify/NeteaseCloudMusicApi)
* 3.输入npm install
* 4.输入node app.js
