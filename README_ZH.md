## BLE-WEB
### [EN](https://gitee.com/JHPatchouli_Admin/ble-web/blob/master/README.md) _|_ [ZH](https://gitee.com/JHPatchouli_Admin/ble-web/blob/master/README_ZH.md)
### 起步
每次使用都需要输入服务UUID，演示地址 [BLE-WEB](https://jhpatchouli_admin.gitee.io/ble-web)

### 获取设备的服务UUID
如果你没有服务UUID请首先获取UUID

> 在安卓普通我们推荐 `Edge浏览器` 和 `LightBlue`.
>
> Edge浏览器 [下载地址](https://www.coolapk.com/apk/com.microsoft.emmx)
>
> LightBlue [下载地址](https://gitee.com/JHPatchouli_Admin/ble-web/raw/master/apk/LB.aPk(%E5%88%A0))
--------
#### Edge浏览器获取UUID方法如下
* 访问 `chrome://bluetooth-internals/#devices`
* 点击start scan按钮, 找到你的设备的信息部分，你应该能见到设备的服务UUID.
--------
#### LightBlue 获取UUID方法如下
* 打开LightBlue后就已经开始扫描了，找到你的设备点击CONNECT
* 连接后你应该能看到设备的服务UUID