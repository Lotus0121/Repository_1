# AUTOSAR
Test GitHub Flow
New a branch

NvM（非易失性存储器）

一、Watchdog 
定时器 监控系统是否正常运行 复位
设置看门狗模式 WdgIf_SetMode();
Fast|Low|Off
喂狗：任务绑定到喂狗操作，周期性调用WdgIf_Trigger();
SWC提供接口
二、《C接口与实现》
