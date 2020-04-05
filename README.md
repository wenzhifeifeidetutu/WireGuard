### 关于


#### _install.sh
> centos版wireguard一键脚本 | centos 7
#### _install_ubuntu.sh
> ubuntu版wireguard一键脚本 | ubuntu >= 14.04
#### _game.sh
> centos版wireguard+udpspeeder+udp2raw一键脚本 | centos 7
#### _game_ubuntu.sh
> ubuntu版wireguard+udpspeeder+udp2raw一键脚本 | ubuntu >= 14.04

#### 基本教程

centos7

  首先下载wireguard.sh软件到服务器, 运行一下命令

  wget https://raw.githubusercontent.com/wenzhifeifeidetutu/WireGuard/master/wireguard_install.sh

  如果没有安装wget 命令 执行一下命令

  yum install wget
  
  运行wireguard 软件
  
  首先你需要设置软件是否可以运行
  
 chmod 777 wireguard.sh
 运行软件
 ./wireguard_install.sh 
 
 先选择更新wireguard 内核 然后等待内核更新完 选择y进行重启。 然后重新运行选择安装wireguard 软件，等待软件安装完成，即可

