# [CH32X035](https://github.com/SoCXin/CH32X035)

* [WCH](http://www.wch.cn/)：[RISC-V](https://github.com/SoCXin/RISC-V)
* [L1R1](https://github.com/SoCXin/Level): 48 MHz

## [简介](https://github.com/SoCXin/CH32X035/wiki)

[CH32X035](https://www.wch.cn/products/CH32X035.html)系列是基于青稞V4C内核设计的工业级微控制器。CH32X035内置USB和PD PHY，支持USB Host主机和USB Device设备功能、USB PD及Type-C快充功能，内置可编程协议I/O控制器，提供了OPA运放、CMP电压比较器、USART串口、I2C、SPI、定时器、12位ADC、Touchkey等丰富外设资源。

``` mermaid
gantt
    title CH32X035 EVT
    dateFormat  YYYY-MM-DD
    section Mainline Release
    v1.9           :a1, 2025-03-11, 2025-04-19
```

### 关键特性

* RISC-V4C处理器，最高48MHz，支持单周期乘法和硬件除法
* 20KB SRAM，65KB Flash
* 多种低功耗模式：睡眠/停止/待机
* 上/下电复位、可编程电压监测器
* 8路通用DMA控制器
* 可编程协议I/O控制器PIOC
* 多组运放OPA/PGA/电压比较器
* 多组模拟电压比较器CMP
* 多路外部12位ADC转换通道
* 多路TouchKey通道检测
* 2个16位高级定时器
* 1个16位通用定时器
* 2个看门狗定时器（独立和窗口）
* 1个系统时基定时器
* 多组USART串口：支持LIN和ISO7816
* 1个I2C接口：支持SMBus/PMBus
* 1个SPI接口
* USB2.0全速控制器及PHY
* USB PD和Type-C控制器及PHY
* 快速GPIO端口，支持24个外部中断
* 96位芯片唯一ID
* 串行2线调试接口SDI
* 封装形式：LQFP64M、LQFP48、QFN28、QSOP28、QFN20、TSSOP20

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)
* [mounriver](http://www.mounriver.com/download)

## [选型建议](https://github.com/SoCXin)

[CH32X035](https://github.com/SoCXin/CH32X035) 拥有4个高速UART，支持5v供电

