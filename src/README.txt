＃此文件夹仅在openCV 实现时使用＃

开发环境：

IDE: X-CODE 5.0
OS : OSX 10.9.3
openCV 版本：openCV2.4.9

X-code openCV 开发环境配置参照：http://blog.sciencenet.cn/blog-702148-657754.html

源代码介绍：
1，calibration.cpp
	负责相机标定。输入一组含有棋盘的图像（大于10张），输出相机内参数矩阵。
2，stero.cpp
    负责3纬场景重建。输入一组左右摄像头拍的对应图片（大于10张），输出视差。
	
源码参考：learning openCV 第11，12章示例代码实现。
　　
