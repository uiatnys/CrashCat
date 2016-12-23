# CrashCat
## 一个用于捕获应用崩溃信息写入本地存储的工具类
## 使用方法:
### 1.build.gradle中加入: 
#### compile 'com.zhWang:crashcat:1.0.0'
### 2.继承于Application的子类中在onCreate内加入
#### CrashCat.getInstance(ApplicationContext, PathDirectory,PathName).start();
#### 例如:CrashCat.getInstance(getApplicationContext(), Environment.getExternalStorageDirectory(),"/Log.txt").start();
