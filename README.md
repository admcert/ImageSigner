# ImageSigner

4.在哪弄
   
   github 开源地址:https://github.com/matrixcascade/ImageSigner  (编译环境 visual studio 2010+ Qt4.8.6)

  Release 版本下载: https://github.com/matrixcascade/ImageSigner/tree/master/Win32/Release

  Release 版本+Qt4.8.6 运行库:https://pan.baidu.com/s/1Uf3lNE2zC9fhBV6A5P3EdA

5.注意
1.算法使用的是基2FFT,因此图像的长度和宽度必须是以2为基数的指数,如256 ,512 ,1024,2048....
2.签名图长宽必须是源图长宽的一半,这个和频域共轭对称性相关
3.水印图尽量使用右下角部分,因为图像的重要频率主要在低频部分(左上角),高频(右下角)不容易对源图造成太大干扰
4.power越大,图像抗攻击能力越强,与此同时的,对源图的影响也越大
