
### 安装
```
npm install http-push-webpack-plugin --save-dev
```

### 配置
```
var HttpPushWebpackPlugin = require('./tools/http-push-webpack-plugin');

new HttpPushWebpackPlugin({
    receiver: 'http://host:port/receiver', // 服务端文件上传接口
    token: 'token', // 验证token
    to: '/home/work/xxx' // 上传文件目录
})
```
