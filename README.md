# CoolView
一些炫酷的自定义控件（Some cool custom controls），逐步完善中...


app功能演示:
-------
![image](https://github.com/wangfeng19930909/CoolView/blob/master/screenshot/video.gif)


控件分类：
-------

1.可拓展可收缩的ExpandTextView

2.高仿ios的底部多类型菜单AlertView

3.不可滑动的viewPager

4.自己动手实现圆形，圆角图片

5.表情键盘

6.第三方分享底部dialog自定义

7.点赞效果

8.加载框自定义

9.水印背景生成

10.自定义switchButton开关按钮


使用步骤
=================================== 

step1:
-------

在gradle中直接引用

在你项目根目录的build.gradle中添加

	allprojects {
	
		repositories {
		
		...
		
		maven { url 'https://jitpack.io' }
		
		}
		
	}
   
step2:
-------

在module下的build.gradle中添加：

		dependencies {
		
	        	implementation 'com.github.wangfeng19930909:CoolView:1.0.0'
		
		}
		
step3:
-------

按照demo工程进行快捷的使用

本人会坚持在这个项目上实践最新的技术，也会争取拓展更多的阅读内容，欢迎各位关注！ 注意：本项目还在测试阶段，发现 bug 或有好的建议欢迎issue、email(wangfengkxhp@foxmail.com),如果感觉对你有帮助也欢迎点个 star、fork，本项目仅做学习交流使用，请勿用于其他用途,如若发现资源存在侵权，请第一时间联系删除。

 


MIT License
=================================== 
Copyright 2017, wangfeng19930909

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
