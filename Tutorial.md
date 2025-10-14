# 构思 Thinking
在我的世界中，Arduino可根据周围环境的变化而生长，所以我的外壳必须通透，留有余空，底座也要与环境共生，让Arduino被摆放在各个生长点上。于是我设想用3D打印制作树根状底座与半封闭外壳，用激光切割与雕刻在内部做一个木质支撑。
# 木质支撑的制作
## 第一步：制图
### 使用工具：AI
**1、** 在官网（https://www.arduino.cc/ ）了解Arduino Uno R3的尺寸。
<p align="center">
<img src="illustrating pictures/arduino尺寸.png" alt="loading" width="600"/>
</p >

**2、** 在AI中画出想要的木质支撑的切割形状，确保其能覆盖Arduino的大小。

**3、** 添加想要雕刻的纹路。
<p align="center">
<img src="illustrating pictures/AI操作.png" alt="loading" width="600"/>
</p >
<p align="center">  
我此处添加的雕刻纹路有些过于密集，打出来效果还可以，但尽量避免这么密集的线条。
</p >

**4、** 留出需要与3D打印部分使用钉子连接固定的孔位。（我将使用直径为3.9mm的洞与其适配的热熔螺母、钉子）

注意：此条需要重视，我就遗漏了这一步。

**5、** 将文件保存为**AI** 格式或**DXF** 格式。

## 第二步：切割与雕刻
### 使用工具：工坊一楼的激光切割机与一旁的电脑
### 第一部分：电脑操作
**1、** 在电脑上打开自己画好的图纸，打开方式选择LaserCAD。
<p align="center">
<img src="illustrating pictures/lasercad.jpg" alt="loading" width="600"/>
</p >
<p align="center">

**2、** 观察图纸是否有乱线、图案是否完全显示。

提示：乱线删除即可，图案不显示很有可能是没有将文字、图形进行扩展。

**3、** 全部选中线条，改为蓝色，需要切割的部分改为黑色。（剩下的蓝色部分为雕刻）
原理：**不同颜色对应不同运行速度与功率，图层顺序先雕刻再切割。**
<p align="center">
<img src="illustrating pictures/lasercad.jpg" alt="loading" width="600"/>
</p >
<p align="center">

**4、** 双击查看**右侧运行数值**，切割参数可参考电脑桌面“切割参数”PDF文件，雕刻参数可询问负责老师，3mm木板一般使用功率3-5，速度300。
<p align="center">
<img src="illustrating pictures/lasercad2.jpg" alt="loading" width="700"/>
</p >
<p align="center">
<img src="illustrating pictures/切割.jpg" alt="loading" width="300"/>
<img src="illustrating pictures/雕刻.jpg" alt="loading" width="400"/>
</p >

**5、** 全部选中进行加载。

### 第二部分：激光切割机操作
**1、** 旋转电源打开切割机，打开激光切割房门旁的**排风扇** 。

**2、** 图纸加载后，显示屏上应出现图案。打开舱门，将材料放在雕刻头附近，或使用按键操控雕刻头移向材料。

**提示：舱门很重，请做好托举的准备再开合。** 

**3、** 点击**边框** 按钮，走边框查看切割范围，检查是否被材料完全覆盖，确认后点击**定位** 进行位置保存。

**4、** 将机上U盘放入雕刻头与板材中间**测量焦距** ，刚刚好即可，如需调节需要按动遥控板上的上、下按键。

**5、** 关上舱门，点击**开始** ，即开始切割。
<p align="center">
<img src="illustrating pictures/激光机操作面板.png" alt="loading" width="400"/>
</p >
<p align="center">
<img src="illustrating pictures/雕刻机工作.jpg" alt="loading" width="400"/>
</p >

**6、** 制作完毕后打开舱门，取下板材和成品，若成品掉入底部，需要拉开底部的抽屉进行拿取。
<p align="center">
<img src="illustrating pictures/成品木板.jpg" alt="loading" width="400"/>
</p >

# 3D打印底座、壳子的制作
## 第一步：建模
### 使用工具：Tripo3d、blender、Meshmixer（可自行选择）
**1、** 根据尺寸精准地进行建模。
<p align="center">
<img src="illustrating pictures/建模.png" alt="loading" width="400"/>
</p >
提示：

1、若使用blender，导出时请注意**单位**的修改，否则导出的大小可能与建造时的比例不同。

2、留出需要安装热熔螺母的洞。（3D打印物件通常使用热熔螺母与螺丝钉来连接）

## 第二步：打印
### 使用工具：Ultimaker软件、bambu Studio软件、对应打印机
**1、** 将模型导入打印机对应的打印设置软件，进行大小检查、摆放、确定是否加支撑、设定内部结构的密度等。

**2、** 进行**Slice**查看，若发现不当之处回到第一步调整。

**3、** 保存打印文件，使用读卡器拷贝至储存卡。

**4、** 将储存卡插回打印机。打开打印机电源、进行预热、打印。
<p align="center">
<img src="illustrating pictures/ulti打印机.jpg" alt="loading" width="200"/>
<img src="illustrating pictures/底座打印.jpg" alt="loading" width="450"/>  
</p >

**5、** 打印完成后取出底板，待彻底**冷却后铲下。**（不冷却完毕就铲除可能导致物品弯曲！）

**6、** 打理打印后的成品，如拆除支撑。
<p align="center">
<img src="illustrating pictures/support.png" alt="loading" width="400"/>
</p >
<p align="center">  
这是支撑未完全拆掉时的样子
</p >

注意：
1、使用工坊的自费打印机时，请务必向负责老师确认**Slice后的效果**，以免出错后白做。

2、使用fablab中的bambu打印机时，打印第一层时可以使用最低档速度，进行上层的打印时可以加快速度。

# 整体拼接
**1、** 将大小合适的热熔螺母通过熔笔安装在打印件上。
<p align="center">
<img src="illustrating pictures/热熔螺母.jpg" alt="loading" width="400"/>
</p >
<p align="center">  
由于我忘记拍照，使用了同学相同步骤的照片
</p >

**2、** 用螺丝刀将长度合适的螺丝钉安装木板与打印件。（打印件与打印件也如是安装）
<p align="center">
<img src="illustrating pictures/螺丝钉.jpg" alt="loading" width="400"/>
</p >
<p align="center">  
同样由于我忘记拍照，使用了同学相同步骤的照片
</p >
<p align="center">
<img src="illustrating pictures/连接.jpg" alt="loading" width="400"/>
</p >
<p align="center">  
我的打印底座与木板由此连接后的样子
</p >

**3、** 整体组装！

<p align="center">
<img src="illustrating pictures/1.jpg" alt="loading" width="300"/>
<img src="illustrating pictures/2.jpg" alt="loading" width="300"/>  
<img src="illustrating pictures/3.jpg" alt="loading" width="300"/>  
</p >
