# 构思 Thinking  
在我的世界中，Arduino可根据周围环境的变化而**生长**，所以我名为**NURTSHELL**的外壳必须通透，留有余空，底座也要与环境共生，让Arduino被摆放在各个生长点上。  
In my envisioned world, the Arduino can **grow according to changes in its surroundings.** Therefore, my **NURTSHELL** must be transparent and spacious, and the base must coexist with the environment, allowing the Arduino to be placed at various growth points. I planned to use 3D printing to create a root-shaped base and a semi-enclosed shell, and laser cutting and engraving to build a wooden support inside.

# 木质支撑的制作 making the wooden support
## 第一步：制图  drawing
### 使用工具：AI  
**1、** 在官网（https://www.arduino.cc/ ）了解Arduino Uno R3的尺寸。  

Visit the official website (https://www.arduino.cc/) to learn the dimensions of the Arduino Uno R3.  
<p align="center">
<img src="illustrating pictures/arduino尺寸.png" alt="loading" width="600"/>
</p>

**2、** 在AI中画出想要的木质支撑的切割形状，确保其能覆盖Arduino的大小。  

Draw the cutting shape of the wooden support in Illustrator (AI), ensuring it can cover the size of the Arduino.

**3、** 添加想要雕刻的纹路。  

Add the engraving patterns you desire.

<p align="center">
<img src="illustrating pictures/AI操作.png" alt="loading" width="600"/>
</p>
<p align="center">
我此处添加的雕刻纹路有些过于密集，打出来效果还可以，但尽量避免这么密集的线条。  
  
The engraving lines I added here were a bit too dense. Although the outcome was acceptable, it’s better to avoid such dense lines.
</p>

**4、** 留出需要与3D打印部分使用钉子连接固定的孔位。（我将使用直径为3.9mm的洞与其适配的热熔螺母、钉子）

**注意：** 此条需要重视，我就遗漏了这一步。 

Reserve holes for connecting with 3D-printed parts using screws. (I used 3.9 mm holes with matching heat-set inserts and screws.)  
 
**Note:** This step is crucial—I personally forgot it.

**5、** 将文件保存为**AI** 格式或**DXF**格式。  
 
 Save the file in **AI** or **DXF**format.

## 第二步：切割与雕刻  Cutting and Carving
### 使用工具：工坊一楼的激光切割机与一旁的电脑 The laser cutting machine on the first floor of the workshop and the computer next to it.

### 第一部分：电脑操作  
**1、** 在电脑上打开自己画好的图纸，打开方式选择LaserCAD。  

Open your design file on the computer using LaserCAD.

<p align="center">
<img src="illustrating pictures/lasercad.jpg" alt="loading" width="600"/>
</p>

**2、** 观察图纸是否有乱线、图案是否完全显示。 

**提示：** 乱线删除即可，图案不显示很有可能是没有将文字、图形进行扩展。  

Check for stray lines or missing graphics.  

**Tip:** Delete stray lines; missing graphics are often caused by unexpanded text or shapes.

**3、** 全部选中线条，改为蓝色，需要切割的部分改为黑色。（剩下的蓝色部分为雕刻）  

原理：**不同颜色对应不同运行速度与功率，图层顺序先雕刻再切割。**  

Select all lines and set engraving lines to blue, cutting lines to black.  

Principle: **Different colors correspond to different speed and power settings. The machine engraves first, then cuts.**

<p align="center">
<img src="illustrating pictures/lasercad.jpg" alt="loading" width="600"/>
</p>

**4、** 双击查看**右侧运行数值**，切割参数可参考电脑桌面“切割参数”PDF文件，雕刻参数可询问负责老师，3mm木板一般使用功率3-5，速度300。  

Double-click to view the **operation settings** on the right. Cutting parameters can be found in the “Cutting Parameters” PDF on the desktop; engraving parameters can be confirmed with the instructor. For 3mm wood, power 3–5 and speed 300 are typical.

<p align="center">
<img src="illustrating pictures/lasercad2.jpg" alt="loading" width="700"/>
</p>
<p align="center">
<img src="illustrating pictures/切割.jpg" alt="loading" width="300"/>
<img src="illustrating pictures/雕刻.jpg" alt="loading" width="400"/>
</p>

**5、** 全部选中进行加载。  
 
 Select everything and load it into the machine.

### 第二部分：激光切割机操作 Laser cutting
**1、** 旋转电源打开切割机，打开激光切割房门旁的**排风扇**。 

Turn on the power switch of the laser cutter and activate the **exhaust fan**
 next to the room door.

**2、** 图纸加载后，显示屏上应出现图案。打开舱门，将材料放在雕刻头附近，或使用按键操控雕刻头移向材料。  
**提示：舱门很重，请做好托举的准备再开合。**

After loading, the design should appear on the display. Open the chamber, place the material near the laser head, or move the head using the control buttons.  
**Tip: The chamber door is heavy—be prepared before opening or closing it.**

**3、** 点击**边框**按钮，走边框查看切割范围，检查是否被材料完全覆盖，确认后点击**定位**进行位置保存。  

Press the **Frame** button to preview the cutting boundary. Ensure the material fully covers the area, then press **Position** to save location.

**4、** 将机上U盘放入雕刻头与板材中间**测量焦距**，刚刚好即可，如需调节需要按动遥控板上的上、下按键。  

Use the onboard USB stick as a gauge between the laser head and the material to **set focal length**.Adjust using the up/down keys on the control panel if needed.

**5、** 关上舱门，点击**开始**，即开始切割。  

Close the chamber door and press **Start** to begin cutting.

<p align="center">
<img src="illustrating pictures/激光机操作面板.png" alt="loading" width="400"/>
</p>

<p align="center">
<img src="illustrating pictures/雕刻机工作.jpg" alt="loading" width="400"/>
</p>

**6、** 制作完毕后打开舱门，取下板材和成品，若成品掉入底部，需要拉开底部的抽屉进行拿取。  

 After processing, open the chamber, remove the material and finished part. If it falls inside, pull out the bottom tray to retrieve it.

<p align="center">
<img src="illustrating pictures/成品木板.jpg" alt="loading" width="400"/>
</p>

# 3D打印底座、壳子的制作 Making the 3D Printed Base and Shell

## 第一步：建模 Modeling

### 使用工具：Tripo3d、Blender、Meshmixer（可自行选择）  
### Tools Used: Tripo3d, Blender, Meshmixer (optional)

**1、** 根据尺寸精准地进行建模。  
 
 Model accurately according to the required dimensions.

<p align="center">
<img src="illustrating pictures/建模.png" alt="loading" width="400"/>
</p>

提示Tips：   
1、若使用Blender，导出时请注意**单位**的修改，否则导出的大小可能与建造时的比例不同。  

If using Blender, pay attention to adjusting the **units** when exporting, or the size may differ from the intended scale.  

2、留出需要安装热熔螺母的洞。（3D打印物件通常使用热熔螺母与螺丝钉来连接）  

Leave holes for inserting heat-set nuts. (3D printed parts usually use heat-set nuts and screws for assembly)

## 第二步：打印 Printing

### 使用工具：Ultimaker软件、Bambu Studio软件、对应打印机  
### Tools Used: Ultimaker Software, Bambu Studio, Corresponding 3D Printer

**1、** 将模型导入打印机对应的打印设置软件，进行大小检查、摆放、确定是否加支撑、设定内部结构的密度等。  

Import the model into the printer's slicing software, check size, positioning, decide whether supports are needed, and set infill density.

**2、** 进行 **Slice**查看，若发现不当之处回到第一步调整。  

Perform slicing and preview; if any issue is found, return to Step 1 to modify.

**3、** 保存打印文件，使用读卡器拷贝至储存卡。  

Save the print file and copy it to an SD card using a card reader.

**4、** 将储存卡插回打印机。打开打印机电源、进行预热、打印。  

Insert the SD card into the printer. Turn on the printer, preheat, and start printing.

<p align="center">
<img src="illustrating pictures/ulti打印机.jpg" alt="loading" width="200"/>
<img src="illustrating pictures/底座打印.jpg" alt="loading" width="450"/>  
</p>

**5、** 打印完成后取出底板，待彻底 **冷却后铲下。**（不冷却完毕就铲除可能导致物品弯曲！）  

After printing, remove the base and only **scrape it off after it has completely cooled.**(Removing it too early may cause warping!)

**6、** 打理打印后的成品，如拆除支撑。  

Clean up the printed object, such as removing supports.

<p align="center">
<img src="illustrating pictures/support.png" alt="loading" width="400"/>
</p>

<p align="center">  
这是支撑未完全拆掉时的样子  
  
This is how it looks before all supports are removed  
</p>

注意：  
Notes:  
1、使用工坊的自费打印机时，请务必向负责老师确认**Slice后的效果，** 以免出错后白做。  

When using self-funded workshop printers, always ask the instructor to confirm the **slicing preview** to avoid mistakes.  

2、使用Fablab中的Bambu打印机时，打印第一层时可以使用最低档速度，进行上层的打印时可以加快速度。  

When using Bambu printers in the FabLab, use the lowest speed for the first layer, and speed up for upper layers.

# 整体拼接 Final Assembly

**1、** 将大小合适的热熔螺母通过熔笔安装在打印件上。  

Install appropriate heat-set nuts into the printed parts using a soldering iron or heat pen.

<p align="center">
<img src="illustrating pictures/热熔螺母.jpg" alt="loading" width="400"/>
</p>
<p align="center">  
由于我忘记拍照，使用了同学相同步骤的照片  
</p>  
<p align="center">  
I forgot to take a photo, so I used my classmate’s photo for this step  
</p>  

**2、** 用螺丝刀将长度合适的螺丝钉安装木板与打印件。（打印件与打印件也如是安装）  

Use a screwdriver and screws of appropriate length to connect the wooden board and printed parts. (The same applies when connecting printed parts together)

<p align="center">
<img src="illustrating pictures/螺丝钉.jpg" alt="loading" width="400"/>
</p>

<p align="center">  
同样由于我忘记拍照，使用了同学相同步骤的照片  
</p>  
<p align="center">  
Again, I forgot to take photos, so I used my classmate’s  
</p>  


<p align="center"
>
<img src="illustrating pictures/连接.jpg" alt="loading" width="400"
/>
</p
>

<p align="center">  
我的打印底座与木板由此连接后的样子 
</p>
<p align="center">  
This is how my 3D printed base connects to the wooden board  
</p>

**3、** 整体组装！  

Final Assembly!

<p align="center"
>
<img src="illustrating pictures/1.jpg" alt="loading" width="300"
/>
<img src="illustrating pictures/2.jpg" alt="loading" width="300"
/>  
<img src="illustrating pictures/3.jpg" alt="loading" width="300"
/>  
</p
>
