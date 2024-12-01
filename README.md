# OpenWrt-K
[原项目地址](https://github.com/chenmozhijin/OpenWrt-K):

> OpenWRT软件包与固件自动云编译

### 已内置以下软件包：

1. LuCI插件：  
  “✓”[luci-app-adguardhome](https://github.com/chenmozhijin/luci-app-adguardhome) :AdGuardHome广告屏蔽工具的luci设置界面  
  “✓”[luci-app-argon-config](https://github.com/jerrykuku/luci-app-argon-config):Argon 主题设置  
  “✓”luci-app-firewall：防火墙  
  “✓”luci-app-opkg：软件包  
  “✓”[luci-app-passwall2](https://github.com/xiaorouji/openwrt-passwall2)：passwall2  
  “✓”[luci-app-turboacc](https://github.com/chenmozhijin/turboacc)：Turbo ACC 网络加速  
  “✓”luci-app-upnp：通用即插即用（UPnP）   
  “✓”luci-app-webadmin：Web 管理页面设置  
  
1. 其他部分软件包：  
  “✓”ethtool-full：网卡工具用于查询及设置网卡参数  
  “✓”sudo：sudo命令支持  
  “✓”htop：系统监控与进程管理软件    
  “✓”bc：一个命令行计算器  
  “✓”pciutils：PCI 设备配置工具  
  “✓”usbutils：USB 设备列出工具  

1. LuCI主题：[Argon](https://github.com/jerrykuku/luci-theme-argon)

    > + 以上软件包都在生成在Releases的package.zip文件中，可安装使用。

2. 网卡驱动：   
  kmod-e1000  
  kmod-e1000e  
  kmod-igb  
  kmod-igbvf  
  kmod-igc  
  kmod-ixgbe  
  kmod-macvlan  
  kmod-phy-realtek  
  kmod-phy-smsc  
  [kmod-r8125](https://github.com/sbwml/package_kernel_r8125)  
  kmod-r8152  
  kmod-r8168  
  kmod-tg3     
  kmod-vmxnet3

 感谢以下项目与各位制作软件包大佬的付出
+ [chenmozhijin/OpenWrt-K](https://github.com/chenmozhijin/OpenWrt-K/)
+ [openwrt/openwrt](https://github.com/openwrt/openwrt/)
+ [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
+ [Lienol/openwrt](https://github.com/Lienol/openwrt)
+ [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt/)
+ [wongsyrone/lede-1](https://github.com/wongsyrone/lede-1)
+ [Github Actions](https://github.com/features/actions)
+ [softprops/action-gh-release](https://github.com/ncipollo/release-action)
+ [dev-drprasad/delete-older-releases](https://github.com/mknejp/delete-release-assets)
