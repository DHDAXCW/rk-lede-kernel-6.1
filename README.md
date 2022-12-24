编译openwrt 6.1

内核6.1测试版，如果有问题请issues~

支持设备：
```
embedfire_doornet1=y
embedfire_doornet2=y
embedfire_lubancat1=y
embedfire_lubancat1n=y
embedfire_lubancat2=y
embedfire_lubancat2n=y
hinlink_opc-h68k=y
friendlyarm_nanopi-r2c=y
friendlyarm_nanopi-r2s=y
friendlyarm_nanopi-r4s=y
friendlyarm_nanopi-r4se=y
friendlyarm_nanopi-r5s=y
firefly_station-p2=y
```

### 固件格式
- **ext4:** 固件文件名中带有 ext4 字样的文件为搭载 ext4 文件系统固件ext4 格式的固件更适合熟悉 Linux 系统的用户使用，在 Linux 下可以比较方便地调整 ext4 分区的大小;
- **squashfs:** 固件文件名中带有 squashfs 字样的文件为搭载 squashfs 文件系统固件而 squashfs 格式的固件适用于“不折腾” 的用户，其优点是可以比较方便地进行系统还原哪怕你一不小心玩坏固件，只要还能进入控制面板或 SSH就可以很方便地进行“系统还原操作”。
