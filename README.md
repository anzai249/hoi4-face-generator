# 钢铁雄心4大众脸生成器/Hearts of Iron IV Generic Face Generator
<img src="./images/27h.jpg" width="400px"></img>

*Results of 27 hours of training*
## 前言/Preface
我是中国人，我的英语不太好，下文中的错误还请大家指出，谢谢。

I'm from China and my English is not very good. Please point out the mistakes below, thank you.

这是一个基于lightweight-gan的钢铁雄心4大众脸生成AI。

This is an AI that can generate hoi4 generic faces, which is based on lightweight-gan.

lightweight-gan:https://github.com/lucidrains/lightweight-gan

训练时使用图片素材来自钢铁雄心4原版游戏和Kaiserreich Mod，共4000余张。

The images used for training are from Hearts of Iron IV Game and Kaiserreich Mod, about 4000 in total.
## 我为什么要训练这个AI？/Why did I train this AI?
在钢铁雄心4的mod制作过程中，大众脸绘制问题给mod制作者带来了很多的麻烦，所以我突发奇想，训练了这个AI，想为各位mod作者带来方便，提高制作效率。

The problem of generic face drawing has caused a lot of trouble for modders during the hoi4 mod making process. So in order to improve efficiency, bring convenience to all modders, I trained this AI.

<img src="./images/modernart.jpg" width="500px"></img>
## 用法/Usage
lightweight-gan的具体用法可以参考：

The specific usage of lightweight-gan can refer to:
```bash
https://github.com/lucidrains/lightweight-gan
```
如果你学会了lightweight-gan的用法，那你就可以去<a href="https://github.com/anzai249/hoi4_face_generator/releases">Release</a>页面下载模型文件，然后将其放到./models/hoi/中，之后在运行：

If you have already learned the usage of lightweight-gan, then you can go to the <a href="https://github.com/anzai249/hoi4_face_generator/releases">Release</a> page to download the model file, and then put it into ./models/hoi/ folder, and then:
```bash
$ lightweight_gan --name hoi --generate --generate-types ema
```
更多生成选项可以参照：

More generation options can refer to:
```bash
https://github.com/lucidrains/lightweight-gan#generating
```
因本人经济能力与时间不足，部分生成的图片质量不高，不过可使用图片修复AI或者Photoshop进行简单修理，省时省力。

Due to my lack of financial ability and time, some of the generated images are of low quality, but simple repairs can be made using image repair AI or Photoshop, which saves time and effort.
## Colab
为此我还做了个Colab笔记本。

I also created a Colab notebook for this.

 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18Bb1ibaotSXTgxlMzCaS9rcRzXfKYK7B?usp=sharing)
## 捐赠/Donation
这个项目花费了我许多时间和金钱，如果你感觉这个项目不错，可以给我买一杯咖啡，至为感谢。

This project cost me a lot of time and money, so if you like this project, please buy me a cup of coffee, thanks.

<img src="./images/wechat.png" width="300px"></img>

*WeChat*

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B0668ZJ)

*Ko-fi*
