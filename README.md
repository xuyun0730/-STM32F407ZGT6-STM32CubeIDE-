# -STM32F407ZGT6-STM32CubeIDE-
由于本人使用的需求和工程之间的一个使用，针对反客官方提供的Keil工程进行了一个移植，并且配置了部分测试功能代码

在使用之前请详细看好 用前面需知 与 注意事项 

本人使用的STM32CubeIDE Version: 1.17.0（确保使用版本不低于该版本）

压缩包内部有关于示例代码的一个版本过程与添加功能，一般为了可移植性高，针对一些相关功能进行了独立包装，
如果有涉及到在系统生成文件里面书写的，也会与一个可替换的txt文件用于直接跟换，如果有好的一些建议，可以在CSDN联系我，
CSDN ID:绪韵

硬件io配对
spi-lcd：

	SPI SCK		SPI-SCL		PB3
	SPI MOSI	SPI-SDA		PB5
	LCD CS				PD11
	LCD DC				PD12
	LCD BL				PD13

 usart：RX:接收(Receive) TX:发送（Transmit）
 
    PA2     ------> USART2_TX   TTL-RX
    PA3     ------> USART2_RX   TTL-TX


