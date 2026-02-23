#### virtio 前端驱动

1.  运行在虚拟机中
2.  针对不同类型的设备有不同的驱动程序，但是与后端驱动交互的接口都是统一的
3.  本文分析 virtio-net 模块，源码位于 `drivers/net/virtio_net.c`
