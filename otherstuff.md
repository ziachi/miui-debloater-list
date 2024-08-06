对于所有应用，不建议直接删除，使用`adb shell pm disable-user package-name`禁用即可，方便出问题时恢复。


## DO NOT UNINSTALL:

- com.miui.securitycenter
- com.miui.securityadd
- com.xiaomi.finddevice 

(Don’t uninstall these three apps or services from your Xiaomi device. Otherwise, you may encounter device bricking or bootloop issues.)

## Attention

**Tested on MIUI 13 on Mi 11 Pro**

**I suggest do not uninstall any prefix with com.android apps**


# 不能禁用或删除（会导致无法启动） [WILL BOOTLOOP, DO NOT UNINSTALL OR DISABLE]
- com.lbe.security.miui 权限管理服务*
- com.android.updater 系统更新*
- com.miui.securitycenter 手机管家*
- com.xiaomi.finddevice 查找手机*
- com.miui.home 系统桌面*
- com.miui.guardprovider MIUI安全组件*
- com.xiaomi.market 应用商店*
- com.xiaomi.account 小米账号*
- com.miui.packageinstaller 应用包管理组件*

# 必须为小米签名 [DO NOT UNINSTALL OR DISABLE]
- com.android.updater 系统更新
- com.miui.securitycenter 手机管家
- com.xiaomi.finddevice 查找手机
- com.xiaomi.market 应用商店

# 不建议禁用或删除 [CAN DISABLE, NOT RECOMMANDED]
- com.miui.powerkeeper 电量和性能
- com.xiaomi.metoknlp 网络位置服务
- com.miui.tsmclient 小米智能卡
- com.miui.accessibility 无障碍服务(TTS)
- com.miui.backup 备份与恢复
- com.miui.freeform 自由窗口
- com.miui.face 人脸识别
- com.miui.miwallpaper 桌面壁纸
- com.miui.aod 息屏显示

# 禁用后会自动启用 [DISABLE NOT WORKING]
- com.miui.contentcatcher
- com.android.printspooler
- com.miui.audiomonitor
- com.miui.voicetrigger
- com.xiaomi.mircs
- com.miui.daemon
- com.xiaomi.xmsfkeeper

# 可以安全禁用 [SAFE TO UNINSTALL OR DISABLE]
- com.xiaomi.ab
- com.xiaomi.aiasst.service
- com.xiaomi.bluetooth
- com.xiaomi.gamecenter.sdk.service
- com.xiaomi.joyose
- com.xiaomi.mi_connect_service
- com.xiaomi.micloud.sdk
- com.xiaomi.migameservice
- com.xiaomi.miplay_client
- com.xiaomi.mircs
- com.xiaomi.mirror
- com.xiaomi.payment
- com.xiaomi.powerchecker
- com.xiaomi.simactivate.service
- com.xiaomi.xmsf
- com.xiaomi.xmsfkeeper

# 可以安全禁用 [SAFE TO UNINSTALL OR DISABLE]
- com.milink.service
- com.miui.analytics
- com.miui.audioeffect
- com.miui.audiomonitor
- com.miui.bugreport
- com.miui.cit
- com.miui.cloudbackup
- com.miui.cloudservice
- com.miui.cloudservice.sysbase
- com.miui.contentcatcher
- com.miui.daemon
- com.miui.hybrid
- com.miui.hybrid.accessory
- com.miui.maintenancemode
- com.miui.micloudsync
- com.miui.miservice
- com.miui.mishare.connectivity
- com.miui.misound
- com.miui.nextpay
- com.miui.personalassistant
- com.miui.phrase
- com.miui.smsextra
- com.miui.systemAdSolution
- com.miui.touchassistant
- com.miui.translation.kingsoft
- com.miui.translation.xmcloud
- com.miui.translation.youdao
- com.miui.translationservice
- com.miui.voiceassist
- com.miui.voicetrigger
- com.miui.vsimcore
- com.miui.wmsvc
- com.mobiletools.systemhelper
