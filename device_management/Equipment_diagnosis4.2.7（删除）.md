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

### 设备诊断

#### 连接状态诊断
##### 操作步骤
1.<a>登录</a>Jetlinks物联网平台。
2.在左侧导航栏，选择**设备管理>设备**，点击**查看**，切换至设备诊断tab页。
3.根据系统自动诊断结果，对**异常**或**可能存在异常**的检查项进行处理。
![](./img/48.png)
 <div class='explanation'>
  <span class='explanation-icon primary-color ring-border'></span>
  <span class='primary-color font-weight'>说明</span>
 <li>人工检查：人工核查一遍对应诊断项的配置参数是否填写正确。</li>
 <li>忽略：人工判断该检查项不影响设备接入平台时，可直接点击忽略。
</div>

4.连接成功后，点击**消息通信**按钮，切换至消息通信tab，选择**调用功能**或**操作属性**。
5.配置完成后，点击**发送**按钮，在对话框中查看具体的上下行消息，同时可查看页面右侧详细日志数据。
![](./img/49.png)








