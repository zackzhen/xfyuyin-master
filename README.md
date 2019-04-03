# xfyuyin-master
讯飞语音开发库

方法调用

IFlyTTS.getInstance(this).playText("正在启动")

// 请替换您自己申请的ID。

private final String appId = ""

//build.gradle 配置

    sourceSets {

        main {

            jniLibs.srcDirs = ['libs']

        }

    }
    repositories{

        flatDir {

            dirs 'libs'

        }

    }