- 一些笔记
- 
进行大计算时先运行低精度版本进行参数优化

需要优化的参数：模拟时间、movie检测器的峰值

模拟时间对最后的结果有很大的影响，因为时间太短，场强没有衰减到0，最后的结果并不准确

Courant Stability 柯朗稳定性条件