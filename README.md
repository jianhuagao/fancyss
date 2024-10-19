
1. 在`packages`目录下，点击tar.gz后缀文件，下载当前最新版本的离线安装包
2. 在[fancyss_history_package](https://github.com/hq450/fancyss_history_package)项目中，包含**历史版本**和**最新版本**的离线安装包

插件离线包下载导航：

| 平台 | 最新full版本下载                                             | 最新lite版本下载                                             | 历史版本下载（包含最新版）                                   |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| hnd  | [fancyss_hnd_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_full.tar.gz) | [fancyss_hnd_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_lite.tar.gz) | [fancyss_hnd](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_hnd) |
| qca  | [fancyss_qca_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_qca_full.tar.gz) | [fancyss_qca_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_qca_lite.tar.gz) | [fancyss_qca](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_qca) |
| farm | [fancyss_arm_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_arm_full.tar.gz) | [fancyss_arm_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_arm_lite.tar.gz) | [fancyss_arm](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_arm) |

## 插件安装

1. 离线安装：下载并校验好离线安装包后，在软件中心内使用**离线安装**/**手动安装**功能，选择安装包后上传并安装即可。

2. 命令安装：(以fancyss_hnd_lite.tar.gz为例，先下载好安装包，并将其上传到路由器的/tmp目录)

   ```bash
   mv /tmp/fancyss_hnd_lite.tar.gz /tmp/shadowsocks.tar.gz
   tar -zxvf /tmp/shadowsocks.tar.gz
   sh /tmp/shadowsocks/install.sh
   ```

## 注意事项

* 强烈建议使用chrome或者chrouium内核的浏览器！以保证最佳兼容性！
* 强烈建议在`最新版本的固件`和`最新版本软件中心`上使用fancyss_hnd！
* 插件会自动跟随当前固件的皮肤类型，支持assuwrt、rog、tuf三种皮肤。
* 一些机型的联名版，只要刷了官改/梅林改版固件的，均能安装本插件！
