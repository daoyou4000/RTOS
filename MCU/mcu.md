## Fundamental Knowledge

### CPU 内存，虚拟内存，磁盘/硬盘的关系
CPU -> Cache -> 内存 -> 硬盘
### CPU 架构
输入设备， 输出设备， 存储器，运算器，控制器。
### ARM 架构
- JTAG                  连接CPU 可以和CPU 通讯
- Voltage regulator     连接CPU

- AHB :SRAM, FLASH 
- APB: GPIO, CAN, PWM, SPI.
### bps bits per second， 波特率是什么，为什么双方波特率要相同 
- 每秒钟可以传送的二进制数，衡量穿行数据快慢的重要指标。
- 双方必须约定相同的波特率才能译码。
- 
### ARM 和DSP 区别
- DSP 是采用的哈佛结构，数据和指令分开，运算能力强， 有专门指令集。
- ARM 是RISC指令集，偏重控制统筹。

### ROM 和 RAM 区别
- RAM 随机存储器，掉电丢失， 内存。
- ROM 只读，掉电不丢失。
