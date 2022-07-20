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

# 基本概念

<div class='divider'></div>

本文主要介绍使用Jetlinks物联网平台时需要了解的基本概念。

<table class='table'>
        <thead>
            <tr>
              <td>名称</td>
              <td>描述</td>
            </tr>
        </thead>
        <tbody>
          <tr>
            <td>产品</td>
            <td>设备的集合，通常指一组具有相同功能的设备。Jetlinks物联网平台内每个产品的id具有全局唯一性。</td>
          </tr>
          <tr>
            <td>设备</td>
            <td>归属于某个产品下的具体设备。Jetlinks物联网平台内每个设备的id具有全局唯一性。设备可以直接连接物联网平台，也可以作为子设备通过网关连接到Jetlinks物联网平台。</td>
          </tr>
          <tr>
            <td>产品分类</td>
            <td>Jetlinks物联网平台支持产品分类配置，不同的产品可以归属到同一个产品分类下。</td>
          </tr>
                    <tr>
            <td>网关</td>
            <td>能够直接连接Jetlinks物联网平台的设备，具有子设备管理功能，能够代理子设备连接云端，以实现不支持以太网的设备连接到物联网平台。
网关子设备|本质上也是设备。子设备不能直接通过以太网连接到Jetlinks物联网平台，需要先连接到网关，再由网关连接到物联网平台。</td>
          </tr>
                         <tr>
            <td>证书</td>
            <td>具有服务器身份验证和数据传输加密功能，保障设备与平台间的数据传输安全。配置后可被网络组件引用</td>
          </tr>
                        <tr>
            <td>Topic</td>
            <td>Topic是UTF-8字符串，是发布（Pub）/订阅（Sub）消息的传输中介。可以向Topic发布或者订阅消息。</td>
          </tr>
                         <tr>
            <td>发布</td>
            <td>操作Topic的权限类型，对应的英文名称为Pub。可以往此类Topic中发布消息。</td>
                         <tr>
            <td>订阅</td>
            <td>操作Topic的权限类型，对应的英文名称为Sub。可以从此类Topic中订阅消息。</td>
                        <tr>
            <td>Jetlinks官方协议</td>
            <td>Jetlinks物联网平台定义的设备与云端之间的通信协议。</td>
          </tr>
                                <tr>
            <td>物模型</td>
            <td>是对设备在云端的功能描述，包括设备的属性、功能、事件和标签。物联网平台通过定义一种物的描述语言来描述物模型，称之为TSL（即 Thing Specification Language），采用JSON格式，您可以根据TSL组装上报设备的数据。</td>
          </tr>
                                <tr>
            <td>属性</td>
            <td>用于描述设备运行时的状态，如环境监测设备所读取的当前环境温度等。属性支持GET和SET请求方式。应用系统可发起对属性的读取和设置请求。</td>
          </tr>
                                        <tr>
            <td>功能</td>
            <td>设备可被外部调用的能力或方法，可设置输入参数和输出参数。相比于属性，服务可通过一条指令实现更复杂的业务逻辑，如执行某项特定的任务。</td>
          </tr>
                                        <tr>
            <td>事件</td>
            <td>设备运行时的事件。事件一般包含需要被外部感知和处理的通知信息，可包含多个输出参数。例如，某项任务完成的信息，或者设备发生故障或告警时的温度等，事件可以被订阅和推送。</td>
          </tr>
                                 <tr>
            <td>标签</td>
            <td>设备物模型拓展字段，添加后的拓展字段，将在设备实例信息页显示
协议包|拟定设备上报数据解析规则，以适配不同厂家、不同设备上报的各类数据。</td>
          </tr>
                                 <tr>
            <td>规则引擎</td>
            <td>通过创建、配置规则，以实现服务端订阅、数据流转和场景联动。</td>
          </tr>
                                         <tr>
            <td>场景联动</td>
            <td>一种开发自动化业务逻辑的可视化编程方式，可以根据触发条件，实现不同厂家、不同设备之间的串行、并行联动。</td>
          </tr>
                                         <tr>
            <td>一机一密</td>
            <td>每个设备烧录其唯一的设备证书。当设备与物联网平台建立连接时，Jetlinks物联网平台对其携带的设备证书信息进行认证。该规则需在协议包中拟定。</td>
          </tr>
                                         <tr>
            <td>一型一密</td>
            <td>同一产品下所有设备可以烧录相同产品证书。设备发送激活请求时，Jetlinks物联网平台对其携带的产品证书信息进行认证，认证通过，下发该设备接入所需的信息。设备再携带这些信息与物联网平台建立连接。该规则需在协议包中拟定。</td>
          </tr>
        </tbody>
      </table>
</div>