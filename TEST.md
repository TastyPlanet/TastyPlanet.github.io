```sequence
participant chrome
participant bilibili

chrome - bilibili: 建立连接
chrome -> bilibili: 请求：访问B站首页
note over bilibili:处理请求中...
bilibili --> chrome: 响应：网页数据
chrome -> bilibili: 请求：av285136543
note over bilibili: 资料搜索中...
bilibili --> chrome: 响应：视频数据
chrome -> bilibili: 请求：我很可爱，请给我钱
bilibili --> chrome: 响应：404 not found
chrome -> bilibili: 你已经没用了，请求关闭连接
bilibili --> chrome: 连接关闭
```
