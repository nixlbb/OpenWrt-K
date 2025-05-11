# OpenWrt-K
原项目:https://github.com/chenmozhijin/OpenWrt-K
## 固件介绍

1. 基于OpenWrt官方源码编译
2. 自带丰富的LuCI插件与软件包（见内置功能）
3. 自带SmartDNS+AdGuard Home配置（AdGuard Home 默认密码：```password```）
4. 随固件编译几乎全部kmod（无sfe），拒绝kernel版本不兼容(kmod在Releases allkmod.zip中，建议与固件一同下载)
5. 固件自带OpenWrt-K工具支持升级官方源没有的软件包（使用```openwrt-k```命令）
6. 提供多种格式固件以应对不同需求

### 内置功能

已内置以下软件包：

1. LuCI插件：  
  [luci-app-adguardhome](https://github.com/chenmozhijin/luci-app-adguardhome) :AdGuardHome广告屏蔽工具的luci设置界面  
  luci-app-firewall：防火墙  
  luci-app-opkg：软件包  
  [luci-app-openclash](https://github.com/vernesong/OpenClash):可运行在 OpenWrt 上的 Clash 客户端  
  luci-app-upnp：通用即插即用（UPnP）  
  luci-app-webadmin：Web 管理页面设置  

1. 其他部分软件包：  
  ethtool-full：网卡工具用于查询及设置网卡参数  
  sudo：sudo命令支持  
  htop：系统监控与进程管理软件    
  cfdisk：磁盘分区工具  
  bc：一个命令行计算器  
  pciutils：PCI 设备配置工具  
  usbutils：USB 设备列出工具  

1. LuCI主题：[Argon](https://github.com/jerrykuku/luci-theme-argon)

    > + 以上软件包都在生成在Releases的package.zip文件中，可安装使用。

2. 网卡驱动： 
  kmod-alx  
  kmod-amazon-ena  
  kmod-amd-xgbe  
  kmod-bnx2  
  kmod-bnx2x  
  kmod-e1000  
  kmod-e1000e  
  kmod-forcedeth  
  kmod-i40e  
  kmod-iavf  
  kmod-igb  
  kmod-igbvf  
  kmod-igc  
  kmod-ixgbe  
  kmod-libphy  
  kmod-macvlan  
  kmod-mii  
  kmod-phy-realtek  
  kmod-phy-smsc   
  kmod-r8152  
  kmod-tg3  
  kmod-vmxnet3


 感谢以下项目与各位制作软件包大佬的付出

+ [openwrt/openwrt](https://github.com/openwrt/openwrt/)
+ [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
+ [Lienol/openwrt](https://github.com/Lienol/openwrt)
+ [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt/)
+ [wongsyrone/lede-1](https://github.com/wongsyrone/lede-1)
+ [Github Actions](https://github.com/features/actions)
+ [softprops/action-gh-release](https://github.com/ncipollo/release-action)
+ [dev-drprasad/delete-older-releases](https://github.com/mknejp/delete-release-assets)
