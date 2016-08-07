Unity3D VR By Used Google CardBoard SDK 
=======================================
#注意
IOS编译所需的Assets/Plugins/iOS/libgvrunity.a文件应超出100M无法上传，给出百度云的链接: http://pan.baidu.com/s/1bo6PQSf 密码: g6qi
#Demos
##1.全景照片观看
原理很简单，建一个材质，添上图片，再给个球加上材质就行。VR相机放球内部。<br>
有的版本从内部看不到图片，解决方法是把材质上的shader复制一遍，更改渲染方式为双面即可。