<h1><a id="user-content-android-学习资料收集" class="anchor" href="#android-学习资料收集" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Android 高仿qq及微信底部菜单的几种实现方式 </h1>

<p>整理底部菜单</p>
<p>根据 http://www.apkbus.com/blog-703583-63612.html</p><p>整理而来</p>
<div>
	<h3>1.侧滑菜单+底部导航</h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215155908133?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/HuTianQi/QQ" target="_blank">https://github.com/HuTianQi/QQ</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br></div>
<h3>2.Fragment+PopupWindow仿QQ空间最新版底部菜单栏</h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215145241154?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/YeXiaoChao/Yc_ui_fragment_qzone" target="_blank">https://github.com/YeXiaoChao/Yc_ui_fragment_qzone</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br></div>
	<h3>3.FragmentTabHost实现qq底部Tab实践的效果图(或RadioGroup和ViewPager)</h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215150224486?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/gdutxiaoxu/QQBottomTab" target="_blank">https://github.com/gdutxiaoxu/QQBottomTab</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br>

	<h3>4.仿QQ底部Tab切换带数字提示的RadioButton，支持自定义提示数字背景颜色、字体大小、字体颜色</h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215151718125?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/goodfree/BadgeRadioButton" target="_blank">https://github.com/goodfree/BadgeRadioButton</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br>
		<h3>5.极其简便的快速实现滑动隐藏标题栏和导航栏(类似知乎)</h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215152045105?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/githubwing/ByeBurger" target="_blank">https://github.com/githubwing/ByeBurger</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br>

		<h3>6.采用悬浮按钮的方式 </h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215152252960?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/aurelhubert/ahbottomnavigation" target="_blank">https://github.com/aurelhubert/ahbottomnavigation</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br>

	<h3>7.BottomNavigationView根据Google guideLine设计</h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215152615528?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br><span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="https://github.com/armcha/LuseenBottomNavigation/blob/master/ScreenShots/screen4.png"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/armcha/LuseenBottomNavigation" target="_blank">https://github.com/armcha/LuseenBottomNavigation</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br>

		
		<h3>8.模拟新材质设计底部导航模式的自定义视图组件。 </h3>
	<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;">看效果：<span class="Apple-converted-space">&nbsp;</span><br style="box-sizing: border-box;"><img title="" style="border: currentColor; border-image: none; max-width: 100%; box-sizing: border-box;" alt="这里写图片描述" src="http://img.blog.csdn.net/20161215152734594?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxNDcyNzcwOQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast"></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'>GitHub地址：<a style="color: rgb(51, 102, 153); text-decoration: none; box-sizing: border-box;" href="https://github.com/roughike/BottomBar" target="_blank">https://github.com/roughike/BottomBar</a></p><p style='font: 14px/26px "microsoft yahei"; margin: 0px 0px 1.1em; text-align: left; color: rgb(51, 51, 51); text-transform: none; text-indent: 0px; letter-spacing: normal; word-spacing: 0px; white-space: normal; box-sizing: border-box; widows: 1; font-size-adjust: none; font-stretch: normal; background-color: rgb(255, 255, 255); -webkit-text-stroke-width: 0px;'><br>
