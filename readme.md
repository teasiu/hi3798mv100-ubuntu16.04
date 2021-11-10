# 华为悦盒ec6108v9 hi3798mv100 刷ubuntu16.04

<br>用户名root 密码1234

<br>登陆后 resize2fs /dev/mmcblk0p3 扩展到4G空间

<br>vi /etc/network/interfaces

<br>/etc/init.d/networking restart

<br>cp /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
<br>ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
<br>date
