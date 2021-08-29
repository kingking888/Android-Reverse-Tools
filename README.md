### 博客地址

https://m0untainshley.github.io/2021/08/29/Android%E9%80%86%E5%90%91%E5%B8%B8%E7%94%A8%E7%9A%84%E5%B7%A5%E5%85%B7%E6%B1%87%E6%80%BB/

### JDK环境

- JDK
  - 由于逆向过程中很多的软件是使用java进行开发或者依赖于java运行环境的，因此JDK的安装是必要的
  - JDK下载地址：https://repo.huaweicloud.com/java/jdk/

### 反编译工具

- AndroidKiller
  - 对APK进行反编译
  - 需要配置JDK环境

- Android官网逆向助手少月版V2018
  - 对APK进行编译、反编译和签名等操作，功能比较多

- jadx
  - 对APK进行反编译
  - 项目地址：https://github.com/skylot/jadx

### 调试工具

- IDA Pro7
  - 动态调试工具
  - 特点：调试so文件比较方便

- IDEA
  - 用来对smali代码进行调试，需要添加smali插件
  - 插件下载地址如下，下载后自行查找IDEA插件安装教程即可
    - https://bitbucket.org/JesusFreke/smali/downloads/
    - https://github.com/JesusFreke/smalidea

- JEB
  - 需要配置JDK环境
  - 特点：调试smali代码比较方便

### 辅助工具

- Android Helper
  - 检测apk的一些信息

- PKID查壳
  - 识别apk的加壳程序，有exe和jar包两种

- 模拟器

  - 雷电模拟器
    - 官网下载
    - 特点
      - **修改apk后无需签名，支持覆盖安装**
      - **动态调试稳定**
      - 安装慢
  - 夜神模拟器
    - 官网下载
    - 特点
      - **安装快**
      - **支持xposed**
      - adb调试端口为127.0.0.1:62001，jeb附加的时候经常找不到模拟器，需要手动adb connect一下
  - 逍遥模拟器
    - 官网下载
    - 特点
      - **安装块**
      - **支持xposed**
      - adb调试端口为127.0.0.1:21503，jeb附加的时候经常找不到模拟器，需要手动adb connect一下

### 抓包工具

- Burp Suite
  - 自行下载并搜索抓包教程
- Fiddler
  - 自行下载并搜索抓包教程
- HTTP Debugger Pro
  - 自行下载并搜索抓包教程

### 项目上传

所有文件已上传至https://github.com/M0untainShley/Android-Reverse-Tools
