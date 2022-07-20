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

## 使用限制

<div class='divider'></div>

<span class='font-size-18'>本文介绍了物联网平台的使用限制及性能指标。</span>

#### 设备接入

##### [#]()产品优势

专用宿主机是搭载了虚拟化环境的专属物理服务器，具有以下优点：

##### 独享资源
通过购买专用宿主机可独享宿主机资源，与其他用户资源物理隔离。宿主机内资源供您自主规划，避免其他租户的资源竞争。

##### 创建灵活
用户可以在指定的专用宿主机上创建自定义规格的云服务器实例，自主规划宿主机资源的使用。实例规格支持自定义，可灵活配置，打破实例规格的限制，保障业务性能的同时充分利用物理服务器资源。支持专用实例配置调整，提供实例不关机随时调整网络，关机状态下可调整实例配置的能力。

<div class='explanation'>
  <span class='explanation-icon primary-color ring-border'></span>
  <span class='primary-color font-weight'>说明</span>
  若设备限制数量不能满足您的业务需求，请
  <a>提交工单</a>
  说明您的需求。
</div>

<table class='table'>
        <thead>
            <tr>
              <td>地域</td>
              <td>描述</td>
              <td>限制</td>
            </tr>
        </thead>
        <tbody>
          <tr>
            <td>华东2（上海）、华北2（北京）、华南1（深圳）</td>
            <td>一个实例下最多可以创建的产品数。</td>
            <td>1,000</td>
          </tr>
          <tr>
            <td>新加坡、德国（法兰克福）、美国（硅谷）、美国（弗吉尼亚）、日本（东京）</td>
            <td>一个实例下最多可以创建的产品数。</td>
            <td>1,000</td>
          </tr>
          <tr>
            <td>华东2（上海）、华北2（北京）、华南1（深圳）</td>
            <td>一个实例下最多可以创建的产品数。
              <div class='explanation'>
    <span class='explanation-icon primary-color ring-border'></span>
    <span class='primary-color font-weight'>说明</span>
    <ul>
      <li>
      若设备限制数量不能满足您的业务需求，请
        <a href='#'>提交工单</a>
        说明您的需求。
      </li>
            <li>
      若设备限制数量不能满足您的业务需求，请
        <a href='#'>提交工单</a>
        说明您的需求。
      </li>
    </ul>
  </div></td>
            <td>1,000</td>
          </tr>
        </tbody>
      </table>
<div class='explanation'>
    <span class='explanation-icon primary-color ring-border'></span>
    <span class='primary-color font-weight'>说明</span>
    <ul>
      <li>
      若设备限制数量不能满足您的业务需求，请
        <a href='#'>提交工单</a>
        说明您的需求。
      </li>
    </ul>
  </div>

<!-- <div class='padding-left-28'>
  <details open class='collapse'>
    <summary class='collapse-title'>HTML 5</summary> 
     <div class='collapse-body'>
    </div>
  </details>
</div> -->

##### [#]()网关子设备
一个网关设备下最多添加的子设备数为1500。
网关设备及其子设备的消息限流，请参见[连接通信]()中的《消息通信限流》。

##### 连接通信
<table class='table'>
        <thead>
            <tr>
              <td>地域</td>
              <td>描述</td>
              <td>限制</td>
            </tr>
        </thead>
        <tbody>
          <tr>
            <td>华东2（上海）、华北2（北京）、华南1（深圳）</td>
            <td>一个实例下最多可以创建的产品数。</td>
            <td>1,000</td>
          </tr>
          <tr>
            <td>新加坡、德国（法兰克福）、美国（硅谷）、美国（弗吉尼亚）、日本（东京）</td>
            <td>一个实例下最多可以创建的产品数。</td>
            <td>1,000</td>
          </tr>
          <tr>
            <td>华东2（上海）、华北2（北京）、华南1（深圳）</td>
            <td>一个实例下最多可以创建的产品数。</td>
            <td>1,000</td>
          </tr>
        </tbody>
      </table>
<div class='explanation flex'>
  <div style="width: 80px;">
    <image src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAFKSURBVHgBpVNNTsJAFP5eO0sWNRENK2EvAW9AbwAG1uIJ4AaEG+gJhDWYcAPqDUp0T3cmYCILNsYyzzc1EGuwtvBt+vI638+8mQEORLU+d8yXkBGXzWXNBnpS1og+rlQaknHTKtchUBdg4+xFP9h2rP/cKs3llFXuXaJ2CXxP4fpkNs672zUqjZuQXX+c9/aZRALiwtuGKYSwMm4I13f+pLRCAnYJCLoPogBMwV9uiQKA9vxRwUNGWDgSuwSa7Xq5tShKsXp+PJ9kFiCiDkUTJFRab4He6L6tN54/KQRJArGbaE6DNN/CoiJ/3zYjONjw5/BlHJ9PtBah+3sGPttWj5kuYI6SRAxwbKippJqXrxftav21+JMQE6AwbLDWT9J1hOz6o7PBbHTakH6JmIcWocdKzUXsYe8W0qDaWrQl4Q3MY5It4FBsn/MXdUWDn6mhEzkAAAAASUVORK5CYII='>
    <span class='primary-color font-weight'>说明</span>
  </div>
  <div>
    若物模型功能限制数量不能满足您的业务需求，请
    <a href='#'>提交工单</a>
    说明您的需求。此时，即使增加了物模型功能限制数量，设备单次上报物模型属性数量也不能超过500。
  </div>
</div>

</div>

