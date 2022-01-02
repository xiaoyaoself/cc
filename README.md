# V2

**若需部署 V2 VLESS，请转到 [vless](https://github.com/xiaoyaoself/cc/tree/vless) 分支。**

## 概述


## 部署



> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/xiaoyaoself/cc)

 4. 回到专案首页，点击上面的链接以部署 V2Ray

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `41b67fde-6baf-489f-878b-bce3ad2a6114` | VMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `AID` | `64` | 为进一步防止被探测所设额外 ID，即 AlterID，范围为 0 至 65535 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |



## 注意

 2. 若使用域名接入 Cl，请考虑启用 TLS 1.3
 3. AWS 绝大部分 IPv4 地址已
