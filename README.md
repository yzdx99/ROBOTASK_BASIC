# LED0  ROBO_TASK-BASIC

Lighting up an LED with STM32F103C8T6
The project files for basic mission of Robomini screen

利用STM32F103C8T6点亮LED
Robomini初筛的初级任务文件


硬件介绍：
    使用STM32F103C8T6、STlink、LED

软件介绍：
    1.该工程使用CubeMX生成初始化代码。
    2.使用端口为PA2，点亮一个外部LED。
    3.初始化为低电平。
      通过delay控制其 点亮1s,熄灭0.5s 的闪烁

电路介绍：
    LED正极接GPIO A2,负极共地。



YZDX