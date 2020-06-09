# UpdateApp
应用自更新工具
1.在项目的build.gradle中添加如下代码块，便于直接依赖github上的代码，如果项目中已经添加则不需要
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  2.在App的build.gradle中添加如下代码块
  dependencies {
	        implementation 'com.github.AndroidBramble:UpdateApp:1.0'
	}
  
