# color_led

TCS_Slave-1.0.zip 程序文件（IAR）

stm8.zip 板子工程文件（AD）


# 接口说明：

C5--白--T2C1

C6--R--T1C1

C3--B--T1C3

C7--G--T1C2

C4--震动传感器--AIN2

D2--按键--AIN3


# 下载线：

蓝色--GND

白色--RST

紫色--SW


# 关于充电：

电池是18650 1200mah

充电亮红灯，充满亮绿灯

出现底下灯长亮或者按了没反应说明该充电了

长时间放置会掉电，使用之前先充电


# 芯片型号：

颜色传感器--TCS3472

主控--STM8S003F3U6TR（原芯片应该是STC15）

充电芯片--TP4056

灯是三极管还是MOS控制的，忘记了

没有升压
