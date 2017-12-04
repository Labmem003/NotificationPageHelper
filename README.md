# NotificationPageHelper
[![](https://jitpack.io/v/Labmem003/NotificationPageHelper.svg)](https://jitpack.io/#Labmem003/NotificationPageHelper)

通知栏权限设置页面跳转器，根据不同 api 版本和机型跳转到最深可以到的设置页


### 下载安装
Step 1. Add the JitPack repository to your build file

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.Labmem003:NotificationPageHelper:1.0.1'
	}
  
  ### 使用
  NotificationPageHelper.open(Context context);
