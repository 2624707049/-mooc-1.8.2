中国大学mooc刷课脚本使用教程，喜欢就把右上角的Star点亮。

有领券需求的小伙伴来这里：http://www.zhongzhimao.com

有不懂的小伙伴可以关注我CSDN博客：听说你很会玩，https://blog.csdn.net/qq_44224698

刷课脚本代码实时更新哦！

使用教程：

由于之前的脚本被greasyfork删除，老用户如不能使用请去greasyfork搜索domooc然后重新安装，安装之前请备份好cdkey，方法见文档末尾

一、安装

1.打开[360极速浏览器](https://browser.360.cn/ee/)


2.	点击立即体验，然后你会下载一个.exe文件，下载完成后双击打开
安装完成后，用360极速浏览器打开[点击打开](https://ext.chrome.360.cn/webstore/search/Tampermonkey)

![image](https://img-blog.csdnimg.cn/20200315163309477.png)

3.	确认添加脚本

![image](https://img-blog.csdnimg.cn/20200315163341852.png)
![image](https://img-blog.csdnimg.cn/20200315163403821.png)

4.	打开[点击进入](https://greasyfork.org/zh-CN/scripts/399230)

 ![image](https://img-blog.csdnimg.cn/20200315163457108.png)
 ![image](https://img-blog.csdnimg.cn/20200315163509415.png)

安装完成后，打开[点击访问](https://www.icourse163.org) ，随意点开一门课的测验页面，如果出现下图右边的面板，即表示加载成功
![image](https://img-blog.csdnimg.cn/20200315163610366.png)

二、使用说明
1. 答题
1.1 有答案的测验会被标记为绿色，没有答案的被标记为红色，会一直显示为红色。
1.2 如果你是第一个进入这门课的人，右侧可能会显示暂无答案的提示，请稍等五分钟，然后刷新。
 

1.3 如果是才出的测验，可能题库没有更新，请点击如下按钮，稍等几分钟后刷新即可。
 
1.4 如果SPOC课程中没有源课程测验的答案，请先打开源课程的主页，进入测验页面，点击“无答案？点击获取”按钮，然后稍等几分钟即可。
 [image](https://img-blog.csdnimg.cn/20200315165513808.png)

1.5 进入一个被标记为绿色的测验后，你可以点击如下按钮获取答案
注意，作业题查看答案显示的是评分标准，有时候可能对答题毫无帮助，如遇这种情况不退还积分。
  
2.考试
考试答案获取速度较慢，建议考试出来24小时之后再进行考试，时间越久题库越完整考试的题准确率也越高。考试目前也只能做客观题。
3.刷课
3.1 点开一个视频，然后点击开启刷课按钮，即可连续播放视频，不会被视频中的题目暂停。
3.2 刷文档的时候不会翻页，但是后台会有记录，刷完之后会自动跳转到下一个内容。
3.3 刷课的自动讨论功能会自动复制粘贴讨论区最长的一条讨论
3.4 刷课的时候不可以将浏览器最小化、不可以切换出当前页面（如下图所示）

 ![image](https://img-blog.csdnimg.cn/20200315165715488.png)
 ![image](https://img-blog.csdnimg.cn/20200315170019380.png)
 
3.5 不建议设置倍速，因为老师后台能看到你的学习时长，后台记录的是你的实际播放时间，而不是视频的时长。
3.6 可以多开浏览器同时刷视频，只要不最小化、不切出视频页面就行。如果刷完后学习时长没有更新，可能是mooc网站的问题，可以等一天后再看。

 ![image](https://img-blog.csdnimg.cn/2020031517005750.png)
 
4.自定义设置
按如下方式打开tampermonkey的脚本编辑器

 ![image](https://img-blog.csdnimg.cn/20200315170121997.png)
 ![image](https://img-blog.csdnimg.cn/20200315170202561.png)
 
可以看到如下设置，你可以自行更改，更改完成后按ctrl+s保存即可
 
5.积分和cdkey
新用户自带50积分，使用完后需要捐赠获取积分才能继续答题，获取积分的方法如下：

 ![image](https://img-blog.csdnimg.cn/20200315170233349.png)
 
随后会跳转到支付页面，然后输入捐赠金额，点击确定
 
 
获取到二维码后会显示提示， 提示金额会在你输入的金额上有正负几分的偏差，请一定按照提示的金额支付，例如这里的5.02元
 
支付成功后会显示cdkey，将此cdkey复制粘贴（直接双击即可全部选中）输入刚才的输入框
 
设置好cdkey后，按F5刷新页面，右侧面板会显示还剩多少积分，此后使用会优先扣除cdkey的积分
 
积分与cdkey绑定，你可以将此cdkey分享给同学，然后按上述方法设置好cdkey即可共享积分。
强烈建议将cdkey用QQ收藏/微信收藏保存，以免重装插件/更换浏览器/重装系统/换电脑后丢失，使用QQ收藏保存的方法如下：

 
 
 
 
脚本不能打开时如何查看cdkey？
1.	按照 “使用说明-4. 自定义设置” 打开油猴脚本编辑器
2.	选择存储，然后会显示如下界面，然后可将cdkey按前述方法保存到QQ收藏，安装新脚本后按 “使用说明-5. 积分与cdkey” 重新设置cdkey
 
 最后记得把右上角的star点亮哦！！！感谢
