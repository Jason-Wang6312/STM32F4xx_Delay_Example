# STM32F4xx_Delay_Example

使用STM32F4的内核定时器SysTick，来实现精确延时函数Delay。适用于STM32F4全部芯片。

## 开发环境

* 固件库：STM32F4xx_DSP_StdPeriph_Lib_V1.8.0
* 编译器：ARMCC V5.06
* IDE：Keil uVision5
* 操作系统：Windows 10 专业版

## API

* void Delay_us(uint64_t nus)
* void Delay_ms(uint64_t nms)
* void Delay_s(uint64_t ns)

## 注意

为了保证程序的正常运行，HCLK时钟必须在1~250MHz之内。
