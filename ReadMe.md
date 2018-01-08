# 创建Ionic cordova Ng4项目
## 1.工作环境准备

- 安装JAVA JDK
- 安装node.js
- 安装Android SDK并配置环境
- 安装nodeJS（自带npm）

- 配置cnpm （使用淘宝镜像取代npm）

- 安装cordova最新版和ionic最新版

 1. cnpm install –g ionic@latest
 2. cnpm install –g ionic@latest 
## 2创项目


1. ionic start projectName tutorial --v3（V3对应装的ionic版本3）
2. 然后cd到你的app目录下，执行 cnpm install
3. ionic cordova platform add android/ios
4. ionic cordova build android/ios
5. 使用android Studio 或者xcode打开项目编译并安装到手机上即可

## 3.调试

1. 先安装浏览器环境 

	ionic cordova platform add browser
2. 运行浏览器调试

	ionic cordova run browser