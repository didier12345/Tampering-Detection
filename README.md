# Tampering-Detection
使用方法：
1.先将除app1.mlap以外的其它m函数导入进matlab的函数路径中，若不会导入，可依次运行每个函数即可。
2.成功导入函数后，运行app1.mlap即可使用该软件

软件用法：
1.两个loding既是载入图片
2.linewidth设置选框线宽
3.directions旋转小波变换方向（默认transverse即可）
4.threshold设置判断阈值。对于篡改较大的图像，可以设置在0.3——0.5，对于篡改较小的图像，可以设置在0.2——0.3，
  随着threshold的减小，可能出现将噪声判定为篡改的情况
  
运行环境
matlab2018
