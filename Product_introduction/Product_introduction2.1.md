
# 产品简介

<div class='divider'></div>

### 什么是Jetlinks物联网平台
**Jetlinks物联网平台**是一个集成了设备接入、设备全生命周期管理、规则引擎、消息订阅等能力的一体化开源PAAS服务平台。向下支持连接海量设备，采集设备数据上云；向上提供北向输出功能和系统API，服务端可通过调用API将指令下发至设备端，实现远程控制。

### 产品架构图
![](./img/01.png)

### 设备接入流程
![](./img/03.svg)

### 许可版本
JetLinks所有版本均开放源代码.

<div class='explanation primary'>
  <p class='explanation-title-warp'>
    <span class='iconfont icon-bangzhu explanation-icon'></span>
    <span class='explanation-title font-weight'>说明</span>
  </p>
 JetLinks使用模块化(git submodule+maven)管理,部分核心模块是单独的仓库并定期发布到maven中央仓库。可在github (opens new window)中找到全部代码。
</div>

| 功能                         | 社区版 | 企业版                    |
| ---------------------------- | ------ |  ------------------------- |
| 开放源代码                   | ✅      | ✅                         |
| 设备管理,设备接入            | ✅      | ✅                         |
| 多消息协议支持               | ✅      |  ✅                         |
| 规则引擎-设备告警            | ✅      |  ✅                         |
| 规则引擎-数据转发            | ✅      |  ✅                         |
| 系统监控,数据统计            | ✅      |  ✅                         |
| 邮件消息通知                 | ✅      |  ✅                         |
| 微信企业消息                 | ✅      | ✅                         |
| 钉钉消息通知                 | ✅      | ✅                         |
| MQTT(TLS)                    | ✅      |  ✅                         |
| TCP(TLS)                     | ✅      | ✅                         |
| UDP,CoAP(DTLS)                   | ⭕      |  ✅                         |
| Http,WebSocket(TLS)          | ⭕      |  ✅                         |
| 转发设备数据到RabbitMQ,Kafka | ⭕      |  ✅                         |
| Geo地理位置支持              | ⭕      |  ✅                         |
| 规则引擎-可视化设计器        | ⭕      |  ✅                         |
| OpenAPI,OAuth2认证           | ⭕      | ✅                         |
| 数据权限控制                 | ⭕      |  ✅                         |
| 集群支持                     | ⭕      |  ✅                         |
| QQ群技术支持                 | ⭕      |  ✅                         |
| 一对一技术支持               | ⭕      | ✅                         |
| 微服务架构                   | ⭕      |  ✅                         |
| 可视化大屏设计器             | ⭕      | ✅                         |
| 定制开发                     | ⭕      |  ✅                         |
| 阿里云协议适配               | ⭕      |  ✅ (付费选配模块)          |
| 阿里云平台接入               | ⭕      |  ✅ (付费选配模块)          |
| 小度平台接入                 | ⭕      |  ✅ (付费选配模块)          |
| 电信CTWing平台接入           | ⭕      |  ✅ (付费选配模块)          |
| 移动OneNet平台接入           | ⭕      |  ✅ (付费选配模块)          |
| GBT/28181视频设备接入        | ⭕      |  ✅ (付费选配模块)          |
| OPC UA                     | ⭕      |  ✅ (付费选配模块)          |
| 商业限制                    | 仅用于自有项目<br>禁止售卖源代码.  | <span style='color:green;font-weight:800'>不限项目数量</span> |
| 定价                         | 免费   |  加QQ群`2021514`联系商务     |