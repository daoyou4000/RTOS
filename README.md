# RTOS
In thie repository start re-studying the RTOS 
##
- 在实时系统中，任务切换是会保存所有的寄存器。
- 硬件中断时，硬件会保存 R0,R1,R2 入栈， 软件保存一些有用的寄存器。 流程是保护现场 -> 处理中断 -> 恢复现场
- 函数调用，R0，R1, R2 无需保存，处理被调用函数。
