如果需要通过黑石 NAT 网关使 VPC 内物理主机访问 Internet，只需要创建 NAT 网关；

## 创建 NAT 网关
- 登录 [腾讯云黑石控制台](https://console.cloud.tencent.com/vpcpm)，选择【黑石私有网络】选项卡，选择【NAT 网关】
- 单击左上角【新建】按钮，在弹出框中依次输入或确定以下参数：
- 网关名称
- 类型
- 转发方式
- NAT 网关所属 VPC
- 为 NAT 网关分配 EIP，可以选择已有 EIP，或者重新购买并分配 EIP
- 关联子网，选择子网中全部/部分 IP
- 选择结束后单击【确认】按钮，即可完成 NAT 网关的创建。
![](https://mc.qcloudimg.com/static/img/947540abff9a3f9861fcc802b25a611f/image.png)
![](https://mc.qcloudimg.com/static/img/3d0ae90dc3b0726893d1b62b80145797/image.png)

## 修改 NAT 网关
NAT 网关创建后，可以对其属性进行修改
- 登录 [腾讯云黑石控制台](https://console.cloud.tencent.com/vpcpm)，选择【黑石私有网络】选项卡，选择【NAT 网关】
- 在 NAT 网关列表页中单击需要修改的 NAT 网关 ID 进入详情页，在详情页可以完成以下属性修改：
- 修改 NAT 网关名称
- 更改 NAT 网关类型，更改后实时生效
- 绑定 EIP 修改
- 关联子网修改
![](https://mc.qcloudimg.com/static/img/5ddafd9af5b3af09a36ba975c98bbc9f/image.png)

## 查看 NAT 网关监控
- 登录 [腾讯云黑石控制台](https://console.cloud.tencent.com/vpcpm)，选择【黑石私有网络】选项卡，选择【NAT 网关】
- 在 NAT 网关列表页，单击需要查看的 NAT 网关条目中的监控按钮，即可查看该 NAT 网关的监控信息
- （或）在 NAT 网关列表页，单击需要查看的 NAT 网关 ID 进入详情页，单击监控选项卡查看该 NAT 网关的监控信息

## 删除 NAT 网关
用户可以在不需要 NAT 网关时将其删除，删除后 Internet 转发请求将立即中断，请提前做好网络中断准备。
- 登录 [腾讯云黑石控制台](https://console.cloud.tencent.com/vpcpm)，选择【黑石私有网络】选项卡，选择【NAT 网关】
- 选中需要删除的 NAT 网关，单击【删除】按钮并确认即可完成删除