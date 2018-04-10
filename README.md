# QRCode
二维码扫描


Step 1：Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://www.jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
	         compile 'com.github.changshuai7:QRCode:1.0.0'
	}


原项目以及文档地址：https://github.com/bingoogolapple/BGAQRCode-Android</br>
本项目基于BGAQRCode-Android-1.2.1的版本剥离了ZBar，做了代码精简，使用更简洁。
