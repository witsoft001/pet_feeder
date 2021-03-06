

> This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.  
>
> For more information, please check Tuya Developer Website.

# 宠物自动喂食器开发计划书

## 一、概述

家有萌宠，看到这个项目比较心动。

自己动手做一个自动喂食器！可以更加精准地掌握主子们的饭量，帮助你监管主子们的饮食，让它们健康成长！

## 二、方案应用场景

使用三明治开发套件制作这款智能宠物喂食器，实现的功能如下所示：

- 定时喂食，周定时循环，食量可选
- 语音可操控，手机可操控，点击选择喂食份量
- 可以看喂食记录
- 余粮不足告警
- 语音播放
- 自动检测碗的重量
- 记录宠物近期的饮食情况，并计算宠物的饭量是否在合适的范围

仿照网上一款宠物喂食器制作喂食器结构。

<img src="https://github.com/witsoft001/pet_feeder/blob/main/image-20210305224036338.png" alt="image-20210305224036338" style="zoom:30%;" /><img src="https://github.com/witsoft001/pet_feeder/blob/main/image-20210305224240373.png" alt="image-20210305224240373" style="zoom:30%;" />

也可以做成这个样子

<img src="https://github.com/witsoft001/pet_feeder/blob/main/image-20210305225431987.png" alt="image-20210305225431987" style="zoom:67%;" /><img src="https://github.com/witsoft001/pet_feeder/blob/main/image-20210305225502364.png" alt="image-20210305225502364" style="zoom: 67%;" />

## 三、开发计划

3月30前完成。

1）3月15前准备物料
- #### 涂鸦三明治直流供电电源板

  数量：1

  用于给涂鸦三明治其余相关的部件供电。[查看详情](https://developer.tuya.com/cn/docs/iot/device-development/tuya-development-board-kit/tuya-sandwich-evaluation-kits/power-board/tuya-sandwich-dcdc-power-board?id=K97o1vflof4gs)

- 

  #### 涂鸦三明治 Wi-Fi MCU 通信板（WB3S）

  数量：1

  适用于涂鸦 IoT 自定义方案中，照明、台灯、灯丝灯、调光器、照明遥控器、排插、开关、家电、运动健康、传感类产品原型。[查看详情](https://developer.tuya.com/cn/docs/iot/device-development/tuya-development-board-kit/tuya-sandwich-evaluation-kits/wireless-communication-board/tuya-sandwich-wifi-mcu-boarde3s?id=K97o0jmgbknqs)

- 

  #### 减速电机

  数量：1

  用于给智能宠物喂食器提供转动能力。

- 

  #### 航顺HK32F030MF4P6或其他航顺主控芯片**M3** **内核****HK32F103XXA****家族**

  数量：1

  可以通过选择 ARM 微控制器提供的各种性能和功耗特性组合来尝试新概念并构建产品原型

  

  #### 重量传感器 TAL220 

  数量：1

  称重宠物食量

  

  #### 其他物料

  数量：若干

  制作喂食器结构

- #### 涂鸦三明治直流供电电源板

  数量：1

  用于给涂鸦三明治其余相关的部件供电。[查看详情](https://developer.tuya.com/cn/docs/iot/device-development/tuya-development-board-kit/tuya-sandwich-evaluation-kits/power-board/tuya-sandwich-dcdc-power-board?id=K97o1vflof4gs)

- 

  #### 涂鸦三明治 Wi-Fi MCU 通信板（WB3S）

  数量：1

  适用于涂鸦 IoT 自定义方案中，照明、台灯、灯丝灯、调光器、照明遥控器、排插、开关、家电、运动健康、传感类产品原型。[查看详情](https://developer.tuya.com/cn/docs/iot/device-development/tuya-development-board-kit/tuya-sandwich-evaluation-kits/wireless-communication-board/tuya-sandwich-wifi-mcu-boarde3s?id=K97o0jmgbknqs)

- 

  #### 减速电机

  数量：1

  用于给智能宠物喂食器提供转动能力。

- 

  #### 航顺HK32F030MF4P6或其他航顺主控芯片**M3** **内核****HK32F103XXA****家族**

  数量：1

  可以通过选择 ARM 微控制器提供的各种性能和功耗特性组合来尝试新概念并构建产品原型

  

  #### 重量传感器 TAL220 

  数量：1

  称重宠物食量

  

  #### 其他物料

  数量：若干

  制作喂食器结构

  

2）3月15-25日嵌入式开发、结构制作

3）3月25-30日前整体调试。
