## v2ray-heroku
[![](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/dhthtrhde/heroku)https://heroku.com/deploy?template=

## 注意事项
### heroku上部署v2ray
- [x] 支持VMess和VLESS两种协议
- [x] 使用v2ray最新版构建

### 客户端配置

```
  - 别名: "yourName"
    协议: vless
    地址: yourName.workers.dev
    端口: 443
    用户id: yourUuid
    流控: xtls-rprx-direct
    加密: none
    伪装域名: yourName.workers.dev
    传输类型: ws
    路径: /
    传输层安全：tls   跳过证书验证：false
    SNI：yourName.workers.dev
```






