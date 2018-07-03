
# MIUI 10 China Developer Debloat

The aim of this mod is to bring optimizations that are present in MIUI EU, PRO and Epic ROM systemlessly to China Developer version.
Normally the changes lead to rebuilding Dalvik cache, please be patient when booting.

# Changelog

**v0.3**
- Added more apps to remove.
- Added Gboard.
- Added GooglePlay Installer.

**v0.2**
- Added some build.prop optimizations.
- Disabled neccessary apps to boot (These can't be removed)

**v0.1**
- Initial debloat of bloated China Developer ROM.

# Changes

<details>
  <summary>Build.prop changes</summary>

  * Telephone ring delay
  * Faster Boot-Animation FPS
  * Better Responsiveness & Speed
  * Better background memory management
  * Setup DNS servers
  * Support For IPV4 and IPV6
  * Network buffer tuning
  * Enable Quick Power-On Mode To Reduce Boot-Time
  * Indicator Hack
  * Camera2API
  * Increase jpg quality to 100%
  * Debugging Notification turned off
</details>

<details>
  <summary>These Apps will be removed</summary>

* **AnalyticsCore** *(/system/app/AnalyticsCore)*
* **BasicDreams** *(/system/app/BasicDreams)*
* **BugReport** *(/system/app/BugReport)*
* **CloudService** *(/system/app/CloudService)*
* **Email** *(/system/app/Email)*
* **GameCenter** *(/system/app/GameCenter)*
* **HybridAccessory** *(/system/app/HybridAccessory)*
* **HybridPlatform** *(/system/app/HybridPlatform)*
* **Joyose** *(/system/app/Joyose)*
* **MSA** *(/system/app/MSA)*
* **MetokNLP** *(/system/app/MetokNLP)*
* **Mipay** *(/system/app/Mipay)*
* **Music** *(/system/app/Music)*
* **PaymentService** *(/system/app/PaymentService)*
* **SogouInput** *(/system/app/SogouInput)*
* **Userguide** *(/system/app/Userguide)*
* **VirtualSim** *(/system/app/VirtualSim)*
* **VoiceAssist** *(/system/app/VoiceAssist)*
* **XMPass** *(/system/app/XMPass)*
* **YouDaoEngine** *(/system/app/YouDaoEngine)*
* **jjhome** *(/system/app/jjhome)*
* **klobugreport** *(/system/app/klobugreport)*
* **mab** *(/system/app/mab)*
* **BaiduIME** *(/system/data-app/BaiduIME)*
* **MiFinance** *(/system/data-app/MiFinance)*
* **MiLiveAssistant** *(/system/data-app/MiLiveAssistant)*
* **MiMobileNoti** *(/system/data-app/MiMobileNoti)*
* **MiShop** *(/system/data-app/MiShop)*
* **O2O** *(/system/data-app/O2O)*
* **SmartHome** *(/system/data-app/SmartHome)*
* **WaliLive** *(/system/data-app/WaliLive)*
* **XiaoAiSpeechEngine** *(/system/data-app/XiaoAiSpeechEngine)*
* **mihome** *(/system/data-app/mihome)*
* **MiGameCenterSDKService** *(/system/priv-app/MiGameCenterSDKService)*
* **Mipub** *(/system/priv-app/Mipub)*
* **MiuiVideo** *(/system/priv-app/MiuiVideo)*
* **YellowPage** *(/system/priv-app/YellowPage)*

</details>

<details>
  <summary>These Apps will be disabled</summary>

 * com.miui.video
 * com.miui.player
 * com.xiangkan.android
 * com.xiaomi.mimobile.noti
 * com.xiaomi.mibrain.speech
 * com.sohu.inputmethod.sogou.xiaomi
 * com.xiaomi.shop
 * com.wali.live
 * com.xiaomi.o2o
 * com.mi.liveassistant
 * com.baidu.input_mi
</details>

<details>
  <summary>These Apps will be installed</summary>

 * Gboard (v7.3.12.201473387)
 * GooglePlay Installer (v3 - Half translated)
</details>
