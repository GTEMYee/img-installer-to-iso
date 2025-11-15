[![Github](https://img.shields.io/badge/Release文件可在国内加速站下载-FC7C0D?logo=github&logoColor=fff&labelColor=000&style=for-the-badge)](https://wkdaily.cpolar.top/archives/1) 

#### 适用范围:任意的 x86_64 实机和虚拟机
#### 安装器中的 iStoreOS
#### 默认管理页面地址 `192.168.100.1`
#### 用户名 `root` 密码：`password`
#### 默认软件包大小 2GB 
#### 默认带 docker
#### 下列属性刷机前必读

- 为最大程度上避免误操作，在正式安装系统前必须只保留需要安装系统的硬盘，并保证该硬盘无任何重要内容
- 该固件刷入【单网口设备】默认采用DHCP模式,自动获得ip。类似NAS的做法
- 该固件刷入【多网口设备】默认WAN口采用DHCP模式，LAN 口ip为 192.168.100.1
- 其中eth0为WAN 其余网口均为LAN (自动将剩余其他网口桥接 无需手动)
- iStoreOS终端中使用 `quickstart` 可查看网口信息
- 默认情况下 只要你知道wan口分配的ip 就能访问web页 前提是在 `quickstart` 中启用了 `ALLOW WAN ACCESS`
- 出处：https://fw0.koolcenter.com/iStoreOS/x86_64_efi/istoreos-22.03.7-2024122712-x86-64-squashfs-combined-efi.img.gz

#### 如何安装
(注意: 本安装流程是在`只有需要安装系统的硬盘`下进行的)</br>
1.ISO启动后，在命令行中出现井号和闪动的下划线时，输入 ddd ，按下 Enter 运行安装程序</br>
2.输入 1 ，按下Enter，选择 Install iStoreOS</br>
3.此时只有一部硬盘，输入数字 1 并按 Enter 来安装</br>
4.按一次`Caps Lock/大写锁定`，输入 YES 并按 Enter 继续安装</br>
5.显示 done! 之后输入 poweroff 并按 Enter 进行关机操作，在关机后将启动ISO的设备移除，防止通电开机后还是上次的启动设备(一般出现在传统启动上)</br>
6.在只有安装系统后的硬盘时，进行开机操作，然后尽情享受吧</br>
7.根据实际情况在关机后加装回其他硬盘
