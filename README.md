# capture_for_oneframe
不利用任何第三方库，进行摄像头设备的初始化吗，预览(子线程进行），更新（回调函数监控子线程的预览，并获取到当前帧的数据）,获取数据图像的宽高，格式，停止摄像头预览（这种情况下，还可以直接在此预览，不需要初始），和停止释放摄像头设备资源（此时是真正的退出摄像头，在此预览需要重启设备，那么需要重新初始化设备）
