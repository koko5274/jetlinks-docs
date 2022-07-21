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

## 流媒体服务

#### 新增
##### 操作步骤
1.**登录**Jetlinks物联网平台。
2.在左侧导航栏，选择**运维管理>流媒体服务**，进入列表页。
![](./img/78.png)
3.点击**新增**按钮，进入流媒体详情页。
![](./img/79.png)
4.填写流媒体服务配置信息，然后点击**保存**。

流媒体服务配置参数说明：
<table class='table'>
        <thead>
            <tr>
              <td>参数</td>
              <td>说明</td>
            </tr>
        </thead>
        <tbody>
          <tr>
            <td>流媒体名称</td>
            <td>为流媒体服务命名，最多可输入64个字符。</td>
          </tr>
          <tr>
            <td>服务商</td>
            <td>配置流媒体服务商。</td>
          </tr>
          <tr>
            <td>秘钥</td>
            <td>调用流媒体API服务的秘钥。</td>
          </tr>
          <tr>
            <td>API Host</td>
            <td>调用流媒体接口时请求的服务地址</td>
          </tr>
           <tr>
            <td>RTP IP</td>
            <td>视频设备将流推送到该IP地址下，部分设备仅支持IP地址，建议全是用IP地址</td>
          </tr>
          </tbody>
</table>
<div class='explanation'>
  <span class='explanation-icon primary-color ring-border'></span>
  <span class='primary-color font-weight'>说明</span>
  若系统中存在多个流媒体服务，播放视频时会进行随机调用。
</div>

#### 编辑
##### 操作步骤
1.**登录**Jetlinks物联网平台。
2.在左侧导航栏，选择**运维管理>流媒体服务**，进入列表页。
3.点击具体流媒体服务的**编辑**按钮，进入流媒体详情页。
4.编辑所需要修改的配置参数，然后点击**保存**。
![](./img/80.png)


#### 删除
##### 操作步骤
1.**登录**Jetlinks物联网平台。
2.在左侧导航栏，选择**运维管理>流媒体服务**，进入列表页。
3.点击具体流媒体服务的**删除**按钮，然后点击**确定**。
![](./img/81.png)








