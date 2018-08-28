## 效果图

<img src="https://github.com/zhangi789/CircleImageView/blob/master/screenshot/QQ.jpg" width="40%" height="40%" div align=center>





## CircleImageView
圆角图片 适用范围（个人中心-图片上传）


## tip
欢迎朋友们多多star支持


## 集成AS

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

## Usage
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

