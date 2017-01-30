
## 購買
整理一下自己所買的洋垃圾資訊

來源 : [華南X79電腦主板cpu套裝2011針八核2660 16G內存可配E5 2670超X58](https://world.taobao.com/item/531884712559.htm)  [華鑫科技貿易](https://shop68152013.world.taobao.com)

套餐三 + 風扇 1688.00 RMB: 
  - CPU : E5-2670 C2 
  - MB  : 華南金牌 X79 
  - RAM : REG ECC 8GB x 4
  - CPU FAN : 加購 

## 資源

1. [华南x79第二版，基本完美，板载声卡已残](http://bbs.pcbeta.com/viewthread-1724967-1-1.html)

> [11F](http://bbs.pcbeta.com/forum.php?mod=redirect&goto=findpost&ptid=1724967&pid=46745860)
> 
> [kexts.zip](hackintosh/11F/kexts.zip)
> 更新2016.11.5，版号10.12.2 Beta（16C32f）
> 声卡已经驱动VoodooHDA.kext（集成声卡ALC662，887可以驱动），kXAudioDriver.kext（SB0105，SB0600，SB0900）完美无五国，后续版本待测试，
> config适用与MAC10.12版本，无需适用DSDT

> [14F](http://bbs.pcbeta.com/forum.php?mod=redirect&goto=findpost&ptid=1724967&pid=46746481)
>
> 华南X79 第二版：2.43全部整理
> 支持声卡（ALC662，ALC887），目前可以无痛升级。感谢论坛兄弟支持！
>
> 附上华南X79第二版最新BIOS，已经加入NVME补丁，待测试是否支持NMVE固态硬
> 修改NVME固态硬盘
>
> [x79_nvem.rom.zip](hackintosh/14F/x79_nvem.rom.zip) [EFI_3882.zip](hackintosh/14F/EFI_3882.zip) [新X79 BIOS.rar](hackintosh/14F/new_X79_BIOS.rar)


> [30F](http://bbs.pcbeta.com/forum.php?mod=redirect&goto=findpost&ptid=1724967&pid=46809163)
> > 请问一下楼主 睡眠是怎么解决的呢，我的机器睡眠不行，其他都差不多了，想了解学习一下
>
> 这板主电源管理芯片， 支持S1， S4和关机， 不支持S3睡眠。 
> 如果想实现睡眠功能，要自己换芯片，还要自己改bios， 不怎么现实。。。


> [69F](http://bbs.pcbeta.com/forum.php?mod=redirect&goto=findpost&ptid=1724967&pid=46905832)
> 比较完整的一次更新，Clover版本是3969，nvme硬盘完美内建
> [华南x7946_nvme_201701.zip](hackintosh/69F/x7946_nvme_201701.zip)  [config.plist.zip](hackintosh/69F/config.plist.zip) [kexts.zip](hackintosh/69F/kexts.zip)
> ![](http://i.imgur.com/lZiJj54.png)
> 适应CPU E5 1650
> 变频问题，系统成功安装完成后，运行 10.12 aicpm patch.command 补丁 [10.12 aicpm patch.command.zip](hackintosh/69F/10.12_aicpm patch.command.zip)
> 其他CPU请根据CPU核心数量修改驱动VodoTSCSync的info：核心数-1=IOCPUNumber
> ![](http://i.imgur.com/W63Lxa5.png)
> 感谢远景论坛同盟友的帮助！
