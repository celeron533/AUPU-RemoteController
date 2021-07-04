# AUPU-RemoteController
记录一下某型号奥普浴霸遥控面板设计

主机依靠不同的电阻值来确认用户按下了哪一个按钮。6\*6 戴帽轻触开关时间久了触点氧化，自身也会产生不小的接触电阻。所以到后期你按一个按钮，根据你的按下的力度、时长、空气湿度等因素，其激活的功能一切随缘。

|按钮|功能|贴片电阻A|贴片电阻B|
|----|----|---------|---------|
|K01|负离子|R3: 1001 (1k)|R4: 1200 (120)|
|K02|照明|R5: 4301 (4.3k)||
|K03|换气|R6: 2701 (2.7k)||
|K04|干燥|R7: 1001 (1k)|R8: 5601 (5.6k)|
|K05|风暖弱|R9: 1002 (10k)||
|K06|风暖强|R10: 1502 (15k)||
|K07|？？？|R11: ??|R12: ??|
|K08|待机|R13: 203 (20k)|R14: 203 (20k)|
|K09|？？？|R15: ??||
|POWER|电源\*|R16: 511 (510)||

1. 每个功能对应电阻A和电阻B串接。
2. 电源并接在所有按钮功能上。
3. 读图仓促，可能有误。

## 有图有真相

拆机

![拆机](image/01.jpg)

PCB背面，已换防水轻触（没吸锡器）

![PCB背面，已换防水轻触](image/03.jpg)

PCB正面，已换防水轻触

![PCB正面，已换防水轻触](image/04.jpg)

面板背面

![面板背面](image/02.jpg)


PCB设计不会也不折腾，换防水轻触（6\*6\*7 无帽）草草了事
![准备更换防水无帽轻触](image/06.jpg)
