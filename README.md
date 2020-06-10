# 开发文档  
## 添加依赖  
在项目的build.gradle中添加如下代码块  
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
  在app的build.gradle中添加如下代码块
  ```
  dependencies {
	        implementation 'com.github.AndroidBramble:UpdateApp:1.0'
	}
```
