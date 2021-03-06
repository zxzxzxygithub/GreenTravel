# 绿色出行
Flutter 仿滴滴出行App  
地图：采用高德地图，仅简单完成了部分功能，基础地图，地址检索，逆地理编码。  
界面：仿滴滴主界面，地图中心请求动效果，服务tabs展开效果，地址检索界面，城市列表界面。  
项目结构：详见作者另外一个完整项目[flutter_wanandroid](https://github.com/Sky24n/flutter_wanandroid)   
目前本项目仅部分开源～  
已开源内容：  
1、Dart汉字转拼音库 [lpinyin](https://github.com/flutterchina/lpinyin)  
2、城市列表，索引&悬停效果 [AzListView](https://github.com/flutterchina/azlistview)  
3、也许是目前最好用的Sp工具类 [SpUtil](https://github.com/Sky24n/flustars)  
4、也许是目前最好用的屏幕工具类 [ScreenUtil](https://github.com/Sky24n/flustars)  
5、闪屏页  
6、国际化

### SpUtil  
// 异步等待Sp初始化完成  
await SpUtil.getInstance();   
// 同步获取数据  
SpUtil.putString('key', value); 
SpUtil.getString('key', defValue: ''); 
SpUtil.getInt('key', defValue: 0);  
  
### ScreenUtil  
// 如果设计稿尺寸默认配置一致，无需该设置。  配置设计稿尺寸 默认 360.0 / 640.0 / 3.0  
setDesignWHD(_designW,_designH,_designD);  

// 不依赖context  
// 屏幕宽  
double screenWidth = ScreenUtil.getInstance().screenWidth;  
// 根据屏幕宽适配后尺寸  
double adapterW100 = ScreenUtil.getInstance().getWidth(100);  

// 依赖context  
// 屏幕宽  
double screenWidth = ScreenUtil.getScreenW(context);  
// 根据屏幕宽适配后尺寸  
double adapterW100 = ScreenUtil.getScaleW(context, 100);  


## Screenshot
### 引导页
<img src="https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/guide.gif" width="240">  
   
### 启动页
<img src="https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/splash.gif" width="240">   

### 主界面
<img src="https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/home.gif" width="240">   

### 首页地图
<img src="https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/home_map.gif" width="240">   

### 地址检索
<img src="https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/select_location.gif" width="240">   

### 城市列表
<img src="https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/citylist.gif" width="240">   

### 关于作者
GitHub : [Sky24n](https://github.com/Sky24n)  
简书 &nbsp;&nbsp;&nbsp;&nbsp;: [Sky24n](https://github.com/Sky24n)  
掘金 &nbsp;&nbsp;&nbsp;&nbsp;: [Sky24n](https://github.com/Sky24n)  
Pub &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: [Sky24n](https://pub.flutter-io.cn/packages?q=email%3A863764940%40qq.com)    
Email &nbsp;&nbsp;: 863764940@qq.com  

### 关于App
GitHub : [GreenTravel](https://github.com/Sky24n/GreenTravel)  
安卓Apk : [点击下载 v0.0.1](https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppStore/green_travel_a.apk)  
Android扫码下载APK:  
  ![绿色出行](https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/qrcode.png)  
Android扫码下载APK(二)：  
速度较快，但有次数限制，若无法下载，请通过上面两种方式下载。   
  ![绿色出行](https://raw.githubusercontent.com/Sky24n/LDocuments/master/AppImgs/green_travel/qr.png)  
