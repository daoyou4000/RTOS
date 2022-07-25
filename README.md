# RTOS
In thie repository start re-studying the RTOS 
## 几种切换
- 在实时系统中，任务切换是会保存所有的寄存器。
- 硬件中断时，硬件会保存 R0,R1,R2 入栈， 软件保存一些有用的寄存器。 流程是保护现场 -> 处理中断 -> 恢复现场
- 函数调用，R0，R1, R2 无需保存，处理被调用函数。

## RTOS 状态
- 运行态
- 就绪态
- 阻塞态
- 挂起态

 ## xxxFromISR
 
 - Cortex M 中断的是独立于任务的，它与系统的内核无关，当任务被中断打断时，仍然处于running的状态。
 - 为了防止访问时数据被修改使用 askENTER_CRITICAL() 和 taskEXIT_CRITICAL() 这两个调用， Disable 低于或者等于configMAX_SYSCALL_INTERRUPT_PRIORITY的任务中断
 - https://www.sohu.com/a/253256697_774177
 
 
