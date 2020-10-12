# Matebook-D14-2020-OpenCore 黑苹果 hackintosh  
  
  
⭐️如果你不会安装，需要安装服务，联系微信ske1996  
可提供收费安装服务，帮你弄好一切可以弄好的驱动，并且保修1个月，收费200，非诚勿扰  
  
  
⭐️有问题只在github免费答疑，不在微信进行答疑，想白嫖请在github提交issue  
【想白嫖请在github提交issue】  
  
  
⭐️微信答疑一问50.   


姐妹项目:[MateBook 13/14 OpenCore 黑苹果](https://github.com/ske1996/matebook-13-2019-oc-efi)  


  
EFI下载地址：[releases](https://github.com/ske1996/Matebook-D14-2020-hackintosh/releases)  

如果你遇到了什么问题（与安装无关的），有可能在这里找到答案：[issues](https://github.com/ske1996/Matebook-D14-2020-hackintosh/issues)  

请在这个网页的最右上角帮我点颗小星星⭐️哟  




<details>  
<summary>⭐️点击查看如何在黑苹果下玩所有3A大作（matebook13/14的黑苹果🉑️）</summary>  
    
  
  
  
 ⚠️在注册的时候填写邀请码：DBZNT3EC  
！！可以白嫖3小时！！
  
       
      
我自己用的一个云电脑服务  
挺好用的能玩游戏（包括3A） 
也就是说在matebook13/14的黑苹果上也可以无硬件限制的玩任何游戏了  
直接4K全画质的开  
没啥延迟，就跟在本地玩一样  
我自己用的，推荐使用这个，这样在mac玩游戏也解决了  
  
⚠️在注册的时候填写邀请码：DBZNT3EC  
！！可以白嫖3小时！！
  
  
  
[点击进入它的官网](https://www.haixingcloud.com/#/Home)  
  

</details>   



       
<details>  
<summary>⭐️扫码进微信群(点击以查看二维码)</summary>  
⚠️点击以下链接，两个小问题全答对即可获得入群二维码  
  
注意:在国内的可能需要挂vpn才能访问  



[点击进入小问答](https://docs.google.com/forms/d/e/1FAIpQLSfNI8Zy9pfb6cASnH7yUk4QVuKxZWVobU9C_p7Vas2EXjVfEQ/viewform?usp=sf_link)  


</details>   
  
   



## 更新日志（⚠️一定先看这个）  
<details>  
<summary>点击以查看详细信息</summary>  
  
  
  
  
- 20201012:    
修复了唤醒后色彩失真的问题，本次缓冲帧部分来自于[@Shaopeng](https://github.com/gongshaopeng0828)  


尝试修复了hdmi问题，目前hdmi可用，但是可能唤醒后会导致色彩失真的问题，可以尝试去偏好设置，显示器，色彩的位置做调整  
另外感谢[@Shaopeng](https://github.com/gongshaopeng0828)帮忙测试  

- 20200917:  
使用了Z大的最新AirportItlwm的wifi驱动，跟heliport说拜拜啦，今后可以原生切换wifi了，另将oc升级至0.6.1  
bigsur跟catalina需要对号入座，不可串着用  

- 20200904:  
上传了根据OC官方版制成的efi  
  
  
</details>   

## 正常可用的部件：
  
 
<details>  
<summary>1.蓝牙（无需热启动）*点击查看详细说明</summary>   
  
驱动作者[@zxystd](https://github.com/OpenIntelWireless/itlwm)  
1. 华为的蓝牙鼠标不可用！！！  
2. 苹果的妙控2可用  
3. 有个可爱的小哥哥@Baiyu0124发现了一款可用的没什么牌子的鼠标[淘宝链接](https://m.tb.cn/h.VtTxb0H?sm=bfed64)   
4. 微软设计师鼠标可用[淘宝链接](https://detail.tmall.com/item.htm?id=575557854943&spm=a1z09.2.0.0.119c2e8dUqx3iI&_u=bkg3nm2911&sku_properties=5919063:6536025)  
</details>   

  
<details>  
<summary>2.wifi可用 *点击查看详细说明</summary>  
  
1. 使用了Z大的最新AirportItlwm的wifi驱动，跟heliport说拜拜啦.  

2. 驱动作者[@zxystd](https://github.com/OpenIntelWireless/itlwm)  

</details>   

3.睡眠正常  

4.触摸板可用  

<details>  
<summary>5.HDMI可用 </summary>  

感谢[@Shaopeng](https://github.com/gongshaopeng0828)帮忙测试  

</details> 

6.解锁cfg lock后可完美原生电源管理

7.已注入缓冲帧 核显正常

8.cpu变频正常（补充：此efi内涵cpufriend，设置为：1800mhz，最高性能）

9.键盘快捷键正常  

10.耳机接口正常（需要使用下面的【安装ComboJack实现耳机耳麦切换，改进电流声】）
  
  
## 无法正常工作的部件：  


1.摄像头  

2.独显  




  
## 个人使用版本信息等   
<details>  
<summary>点击以查看详细信息</summary>  
oc版本0.6.0

自用macos版本：10.15.5 Catalina    

matebook D14 2020 i5-10210U  

</details>  

## 安装方法&镜像下载&视频教程： 
 ⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️
⚠️d14很多是pm981的硬盘，建议换个硬盘，不然天天死机启动失败的够你受得，还有就是安装教程与普通的硬盘不一样  



<details>  
<summary>点击查看镜像下载</summary>  
先于此blog下载：10.15.5 19F101 双EFI分区版

这个文章很长，使劲往下翻，或使用网页搜索功能

下载链接
：https://blog.daliansky.net/macOS-Catalina-10.15.5-19F96-Release-version-with-Clover-5118-original-image-Double-EFI-Version-UEFI-and-MBR.html
  
</details>  

      
<details>  
<summary>点击查看安装视频教程</summary>

https://www.bilibili.com/video/BV1jJ41127YT/?spm_id_from=333.788.videocard.0
  
⭐️如果你不会安装，需要安装服务，联系微信ske1996
可提供收费安装服务，并且保修1个月  

有问题只在github免费答疑，不在微信进行答疑，想白嫖请在github提交issue，微信勿扰  
</details>  
  
  

<details>  
<summary>安装注意点</summary>  
⚠️事前准备：f2进bios，调成中文，然后关闭一切带有“安全”的东西，保存，退出  
  
1.安装使用的镜像推荐使用我给的链接下载的那个，不要用他给的，因为有点旧了  

2.视频的【03:57】他说把配置好的clover文件解压到这个文件夹下时，将我的库中的【安装用clover的EFI】放进去  

3.视频的【14:37】开始他开始吧u盘的clover efi复制进ESR（EFI）分区，这一步复制我的oc的efi进去。注意：这一步的efi跟第二步不一样，这一步用oc的

4.视频的【16:44】开始是使用easyuefi创建efi引导，这一步前面都跟他视频一样，他怎么点你就怎么点，只不过，选择引导文件为：EFI/BOOT/BOOTx64.efi
  
⭐️如果你不会安装，需要安装服务，联系微信ske1996  
可提供收费安装服务，帮你弄好一切可以弄好的驱动，并且保修1个月，收费200，非诚勿扰    
</details>

## 安装后：  


<details>  
<summary>安装ComboJack实现耳机耳麦切换，改进电流声。（修复耳机接口）</summary>   
  
参考： 

![image](http://m.qpic.cn/psc?/V51Uqo3Z3KmDDj0bhEZH0ySaLy25K537/ruAMsa53pVQWN7FLK88i5q01OKCJFpwjG8DeWk34ZAk2FSNjwQUoIN0*GZw*WPuJGXoFx6QKbikJBN0lMTsBAB*.2jRAK8HeEs9KtxTHRjs!/b&bo=SAdMAgAAAAADByM!&rf=viewer_4)



在这里下载由Heporis制作的ComboJack.

https://github.com/randomprofilename/ComboJack


终端运行下面路径的脚本
```bash
ComboJack_Installer/install.sh
```
  
</details>

  
  
<details>  
<summary>解锁CFG</summary>  

⚠️关于解锁cfg后能做到什么？  
完美的电源管理  
CPU完美变频  
完美睡眠（我个人经验：睡眠6H只掉了1%的电）  
⚠️以下教程的cfg lock偏移地址提取自matebook d14 2020款  
其他的需要自行提取bios并自行分析，核对偏移地址  
如因以下教程修改导致的一切后果，本人不予承担责任，下载本repo中任何一个文件视为同意以上条款  


以下教程来自：  
https://zhuanlan.zhihu.com/p/121655468

先去华为官网升级bios至1.19

然后找偏移地址就不用做了，我告诉你，就是0x3E  

【⚠️千万不要用oc去引导ru！！】懂得人自然懂，收起那个想法，老老实实按我下面写的来  
⚠️以下教程的cfg lock偏移地址提取自matebook d14 2020款  
其他的需要自行提取bios并自行分析，核对偏移地址  
如因以下教程修改导致的一切后果，本人不予承担责任，下载本repo中任何一个文件视为同意以上条款  


- U盘准备阶段：  
（大小无所谓）  

1.先准备一个u盘，格式化为fat32  
2.u盘里创建文件夹：EFI  
3.打开EFI文件夹，在里面创建文件夹BOOT  
4.复制[cfgunlock.zip(点击下载)](https://github.com/ske1996/matebook-13-2019-oc-efi/raw/master/cfgunlock.zip)里面的bootx64.efi进U盘的EFI/BOOT下  
5.关机后开机按F12使用这个U盘去引导，然后进入修改bios底层阶段  

- 以下为修改bios底层阶段：  
1. 进入后 ‘alt’ + ’=‘ 切换进 ACPI Variable  
2. 用pageup/pagedown/上下方向键找到 CPUSetup  
3. 回车进入然后用上下左右方向键找到对应的地址（也就是0x3e，那么就是纵坐标03，横坐标0e的位置）  
![image](http://m.qpic.cn/psc?/V51Uqo3Z3KmDDj0bhEZH0ySaLy25K537/ruAMsa53pVQWN7FLK88i5q01OKCJFpwjG8DeWk34ZAl40wvQBwENCvcC8AXw3U9pLndZFaQGhnrwveoEM7FzByVHyIsV*u1nI.1JoXvOXOA!/b&bo=0AIQAgAAAAABB.A!&rf=viewer_4)  
4. 一看，确实是0x01，那么回车，输入0 就可以看到它变成了0  
5. 使用'crtl' + 'w' 来保存 保存的时候屏幕上会直接显示update written 的，这说明已经写入了  
6. 使用'alt' + 'q' 来退出，然后即可回到引导进入系统了，CFG已经解锁  

</details> 

      

<details>  
<summary>解决window与macos时间不同步/显示不正确</summary>  
  
  
  
在windows下面WIN+x 选择管理员模式进入CMD  
  
  执行以下命令：  
  
```bash
Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t REG_DWORD /d 1
```  
</details>   
  
  

<details>  
<summary>关于如何在黑苹果下玩游戏（打破平台/硬件限制，黑苹果也能玩所有PC游戏）</summary>  
    
  
  
  
 ⚠️在注册的时候填写邀请码：DBZNT3EC  
！！可以白嫖3小时！！
  
       
      
我自己用的一个云电脑服务  
挺好用的能玩游戏（包括3A） 
也就是说在matebook13/14的黑苹果上也可以无硬件限制的玩任何游戏了  
直接4K全画质的开  
没啥延迟，就跟在本地玩一样  
我自己用的，推荐使用这个，这样在mac玩游戏也解决了  
  
⚠️在注册的时候填写邀请码：DBZNT3EC  
！！可以白嫖3小时！！
  
  
  
[点击进入它的官网](https://www.haixingcloud.com/#/Home)  
  


</details>   




## 如果想打赏小的，请选择一个你喜欢的方式打赏五块钱，谢谢！
  
  ⭐️打赏附言请留下自己的github的ID，用于公示感谢  
  



![image](http://m.qpic.cn/psc?/V51Uqo3Z3KmDDj0bhEZH0ySaLy25K537/ruAMsa53pVQWN7FLK88i5vhyua0NyktT47EDwPAfhtuBceWLK5.5V40I*6lQE5rORR7qbWTf9Eovur4ifsHKECewZxvEqi.ZfhaQ4ObpAl8!/b&bo=DQWcAw0FnAMBCS4!&rf=viewer_4)  


  
[看不到图片请点击](http://m.qpic.cn/psc?/V51Uqo3Z3KmDDj0bhEZH0ySaLy25K537/ruAMsa53pVQWN7FLK88i5vhyua0NyktT47EDwPAfhtuBceWLK5.5V40I*6lQE5rORR7qbWTf9Eovur4ifsHKECewZxvEqi.ZfhaQ4ObpAl8!/b&bo=DQWcAw0FnAMBCS4!&rf=viewer_4)  

    
    
  
  
如果可用请在issues中提交你的机器信息（年份，cpu，matebook13还是14）  
用于构建更好的efi

## 感谢：

- @intel 感谢10年一管牙膏

- @apple 感谢创造出macos

- [@zxystd](https://github.com/OpenIntelWireless/itlwm) 感谢创造出wifi以及蓝牙的驱动

- [@MoZyo](https://github.com/MoZyo/RedmiBook-13-10th-Gen-Intel-Hackintosh) 教会了我很多东西

- [@Edoardo001](https://github.com/Edoardo001/Matebook-13-Hackintosh) 我做黑苹果的入门引路人 感谢他在matebook13的clover版efi上的杰出贡献
