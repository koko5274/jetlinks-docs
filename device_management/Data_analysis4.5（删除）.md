<style>
  .primary-color {
    color: #2F54EB;
  }

  .primary-color-2 {
    color: rgba(255, 88, 0, 1);
  }

  .text-color {
    color: rgba(0, 0, 0, 0.85);
  }

  .font-size-12 {
    font-size: 12px
  }

  .font-size-14 {
    font-size: 14px
  }

  .font-size-16 {
    font-size: 16px
  }

  .font-size-18 {
    font-size: 18px
  }

  .font-weight {
    font-weight: bold;
  }

  .padding-28 {
    padding: 28px;
  }

  .flex {
    display: flex;
  }

  .padding-left-28 {
    padding-left: 28px;
  }

  .explanation {
    padding: 8px 16px;
    border: 1px solid rgba(231, 237, 253, 1);
    border-left: 2px solid #2F54EB;
  }

  .explanation-icon::after {
    width: 16px;
    height: 16px;
    border-radius: 50%;
    border: 1px solid #2F54EB;
    font-size: 14px;
    content: '?';
    display: inline-block;
    text-align: center;
    line-height: 16px;
  }

  .collapse {
    border: 1px solid #F0F0F0;
    margin: 16px 0;
  }

  .collapse-title {
    background: #FAFAFA;
    padding: 9px 18px;
  }

  .collapse-body {
    padding: 16px;
  }

  .no-margin {
    margin: 0;
  }

  .table {
    width: 100%;
  }

  .table td {
    border-color: #F0F0F0;
    word-break: break-all;
  }

  .table tbody tr:nth-child(even) {
    background-color: #F6F8FA;
  }

  ul li::marker {
    color: #2F54EB;
  }

  .divider {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    color: #000000d9;
    font-size: 14px;
    font-variant: tabular-nums;
    line-height: 1.5715;
    list-style: none;
    font-feature-settings: "tnum";
    border-top: 1px solid rgba(0,0,0,.06);
    margin: 16px 0;
  }

  img {
    vertical-align: text-bottom;
  }
</style>

<div class='text-color font-size-14'>

## 数据解析

<div class='divider'></div>

#### 配置解析规则
##### 操作步骤
1.<a>登录</a>Jetlinks物联网平台。
2.在左侧导航栏，选择**设备管理>产品**，点击**查看**，切换至数据解析tab页。
3.在数据解析页面，自定义编写**数据解析脚本**，
4.输入**Topic**或**URL**进行调试。
<div class='explanation'>
  <span class='explanation-icon primary-color ring-border'></span>
  <span class='primary-color font-weight'>注意</span>
  显示Topic或者URL由协议包拟定。
</div>

5.调试通过后，点击**保存**。

![](./img/31.png)

<div class='explanation'>
  <span class='explanation-icon primary-color ring-border'></span>
  <span class='primary-color font-weight'>注意</span>
  <li>该tab页的展示与否由协议包拟定。</li>
  <li>设备-数据解析将自动继承产品的数据解析规则。</li>
</div>








