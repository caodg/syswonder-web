# 矽望开源项目

## rcore

Rust实现的操作系统内核及基础构件。

## rvisor

Rust实现的Type-1虚拟机监视器（Hypervisor），采用基于基础构件的可重构设计思想，主要提供硬件资源虚拟化、GuestOS镜像安全隔离和原生任务执行的能力，既可以作为裸金属hypervisor使用，也可以作为RTOS内核使用。

## rlibos

Rust实现的库形态泛在操作系统实例, 设计思想来自[Unikernel](https://en.wikipedia.org/wiki/Unikernel)。