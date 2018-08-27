## 如何使用它

> Step 1.先在 build.gradle(Project:XXXX) 的 repositories 添加:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
> Step 2. 然后在 build.gradle(Module:app) 的 dependencies 添加:

	dependencies {
	       //基础工具库
          implementation 'com.github.zhangi789:CircleImageView:1.0'
	}

Usage
-----
```xml
  <com.custom.cn.CircleImageView
        android:id="@+id/profile_image"
        android:layout_width="96dp"
        android:layout_height="96dp"
        android:layout_centerInParent="true"
        android:src="@mipmap/pic11"
        app:civ_border_color="#d93cf1"
        app:civ_border_overlay="false"
        app:civ_border_width="1dp" />
## Demo介绍

 


| 头像 
| ----------
| <img src="screenshot/QQ图片20180827181118.jpg">|

