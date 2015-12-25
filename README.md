# AtoZLauncher
改自android4.4原生launcher3。已经添加服务器编译中间插件，可直接通过Eclipse编译，不必再配置编译环境。修改原生launcher的workspace改成12*12布局，上滑出现atoz应用列表可直接拖入workspace，删除原生的AppsCustomizeTabHost，可参考本程序，自定义apptabhost或者widgethost，原生的PageViewIcon未做修改，新建AtoZPageViewIcon，细节有所改动，长按拖动原理一样，在launcher文件中各个生命周期中对atoz的相关功能有所增加。
在主Activity中添加权限：<category android:name="android.intent.category.LAUNCHER" />
再声明：<uses-sdk android:minSdkVersion="17" android:targetSdkVersion="20"></uses-sdk>即可使用
初步测试：设置Widget报错
