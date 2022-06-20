# project
50个小项目

demo1：动态添加类名实现点击效果\
![image](https://user-images.githubusercontent.com/83935370/173315323-20c0bb23-156f-4ddf-a68b-6bb7f8f2034c.png)\
demo2：进度条\
![](README_files/1.jpg)

demo3：transform: translateX(0)使用\
![](README_files/2.png)

demo5:\
修改图片颜色为黑白 (100% 灰度):style.filter\
让 DIV 元素半透明：style.opacity

demo6:box.getBoundingClientRect().top
给box设置右边400，然后单数的设置-400px，监听窗口滑动就变为0px

demo7：监听鼠标在图片上，使其宽度变为75%，另外一个变为25%

demo8：labels.forEach(label => {
				label.innerHTML = label.innerText
					.split('')
					.map((letter, idx) => `<span style="transition-delay:${idx * 50}ms">${letter}</span>`)
					.join('')
			})
遍历邮箱和密码的每个单词按时间添加一个动效

demo9：点击播放mp3，遍历所有暂停，然后给点击的btn播放对应的音频

demo10：jokeEl.innerHTML，接口获取数据后将其文本替换

