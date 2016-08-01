# Android酷炫自定义控件(View)汇总
这是我近期整理的比较酷炫并且我们会经常用到的custom view，也有一些不是custom view，但是也是android UI相关的，实现了酷炫UI效果的开源库，总结的项目最后维护时间一般不会超过6个月，会持续更新，如果觉的不错，欢迎star。其中大部分控件我也没有真正使用，只是感觉比较酷炫就收集过来了，所以如果描述有误的话，欢迎大家指正！

> 如果大家有好的UI相关开源项目推荐，欢迎提issue，也可以发起PR，我会认真审核后合并

目前主要包括：

// TODO 总结一份概览，因为图片太多，一下加载不完，不方便查看。另外，整理一份无图版，方便查看。最后，记得添加跳转锚点！如果有必要，最好再调整一下顺序

## 阅读器Read View

这一个分类，暂时叫做Read View，里面收集的都是一些方便阅读的自定义view，例如PDFView，代码高亮的CodeView，富文本阅读的RichText等。

### CodeView

CodeView 是一个能显示代码，并且能够进行代码高亮的一个控件。通过hightlight.js 渲染代码，可以自动识别主流的各种语言 比如java,c++,c#,python,bash,ruby等语言 并且有很多种主题风格，可以自由选择一种主题，然后将其显示。

项目地址：[https://github.com/Thereisnospon/CodeView](https://github.com/Thereisnospon/CodeView)

效果图：

![](https://camo.githubusercontent.com/e5410526007ee83dec13677be967a20dde52c113/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630363231313835333236353132) 
![](https://camo.githubusercontent.com/9ad566cb4deea6fdd94d7f3a31d25aed153f518f/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630363231313835343138313839)

### AndroidPdfViewer

一个android版本的PDF阅读渲染器，可以用来阅读PDF文档。

项目地址：[https://github.com/barteksc/AndroidPdfViewer](https://github.com/barteksc/AndroidPdfViewer)

效果图：

![](https://github.com/madongqiang2201/views/blob/master/imgs/pdfview.png)

### RichText

Android平台下的富文本解析器，支持HTML和Markdown。

项目地址：https://github.com/zzhoujay/RichText

效果图：

![](https://github.com/zzhoujay/RichText/raw/master/image/image.jpg)

### MarkdownView-Android

MarkdownView-Android是一个可以加载markdown或者普通文件并显示成html格式。

项目地址：[https://github.com/mukeshsolanki/MarkdownView-Android](https://github.com/mukeshsolanki/MarkdownView-Android)

效果图：

![](https://raw.githubusercontent.com/mukeshsolanki/MarkdownView-Android/master/Screenshots/demo.gif)

## 产品介绍页Introduction

这里主要介绍几种常见的产品引导介绍方式。

### GuideView

GuideView是一个遮罩式的导航页，能够快速为任何一个View创建一个遮罩层，支持单个页面，多个引导提示，支持为高亮区域设置不同的图形，支持引导动画，方便扩展。

项目地址：[https://github.com/binIoter/GuideView](https://github.com/binIoter/GuideView)

效果图：

![](https://github.com/binIoter/GuideView/raw/master/app/src/main/res/assets/review.gif)

### ShowcaseView

一个通过局部高亮达到突出重点，实现引导效果的控件。

项目地址：[https://github.com/amlcurran/ShowcaseView](https://github.com/amlcurran/ShowcaseView)

效果图：

![](https://github.com/amlcurran/ShowcaseView/raw/master/example@2x.png)  ![](https://github.com/amlcurran/ShowcaseView/raw/master/example2@2x.png)

### AppIntro

一个常规的viewpager产品介绍页。

项目地址：[https://github.com/PaoloRotolo/AppIntro](https://github.com/PaoloRotolo/AppIntro)

效果图：

![](https://github.com/PaoloRotolo/AppIntro/blob/master/art/intro.png)

## 卡片交互Card interaction

这里介绍几种卡片交互体验的控件。

### CardStackView

非常酷炫的卡片是交互控件。

项目地址：[https://github.com/loopeer/CardStackView](https://github.com/loopeer/CardStackView)

效果图：

![](https://github.com/loopeer/CardStackView/raw/master/screenshot/screenshot1.gif)  ![](https://github.com/loopeer/CardStackView/raw/master/screenshot/screenshot2.gif)

### android-card-slide-panel

就是“探探”app实现的那种交互体验，为此我还特意下了一个探探体验了一下，卡片上展示的全是美女！左右拖动操作页非常nice，探探这个产品交互简直无可挑剔。

项目地址：[https://github.com/xmuSistone/android-card-slide-panel](https://github.com/xmuSistone/android-card-slide-panel)

效果图：

![](https://github.com/xmuSistone/android-card-slide-panel/raw/master/capture03.gif)  ![](https://github.com/xmuSistone/android-card-slide-panel/raw/master/capture2.gif)

### ExpandingPager

一个比较常规的卡片式交互控件。

项目地址：[https://github.com/qs-lll/ExpandingPager](https://github.com/qs-lll/ExpandingPager)

效果图：![](https://github.com/qs-lll/ExpandingPager/raw/master/img/ExpandingPager.gif)  ![](https://github.com/qs-lll/ExpandingPager/raw/master/img/size1.png)



## 加载框LoadingView
主要介绍几种很漂亮的加载框，
### Android-SpinKit
基于非常火爆的css库SpinKit实现的android加载库，动画效果非常棒。

项目地址：[https://github.com/ybq/Android-SpinKit](https://github.com/ybq/Android-SpinKit)

效果图：

![](https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/screen.gif)

### LoadingDrawable
这个项目重要介绍一些酷炫的加载动画， 可以与任何View配合使用，作为加载动画或者Progressbar, 此外很适合与RecyclerRefreshLayout 配合使用作为刷新的loading 动画。

项目地址：[https://github.com/dinuscxj/LoadingDrawable](https://github.com/dinuscxj/LoadingDrawable)

效果图：

![](https://raw.githubusercontent.com/dinuscxj/LoadingDrawable/master/Preview/ShapeChangeDrawable.gif) ![](https://raw.githubusercontent.com/dinuscxj/LoadingDrawable/master/Preview/GoodsDrawable.gif)
![](https://raw.githubusercontent.com/dinuscxj/LoadingDrawable/master/Preview/SceneryDrawable.gif)

### LiquidButton
一个实现液体填充效果的加载提示view

项目地址：[https://github.com/yoruriko/LiquidButton](https://github.com/yoruriko/LiquidButton)

效果图：

![](https://camo.githubusercontent.com/6e51af802823444540390be079ecad75ef60019e/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3333303137342f73637265656e73686f74732f323639353630302f636f6d705f322e676966)

### LoadingView

哈哈，不多说，主要看动效，好看最重要。

项目地址：[https://github.com/ldoublem/LoadingView](https://github.com/ldoublem/LoadingView)

效果图：

![](https://github.com/ldoublem/LoadingView/raw/master/screen/%E6%95%88%E6%9E%9C.gif)

### MetaballLoading
一个有贝塞尔曲线动画的加载提示框

项目地址：[https://github.com/dodola/MetaballLoading](https://github.com/dodola/MetaballLoading)

效果图：

![](https://github.com/dodola/MetaballLoading/raw/master/metaball.gif)

## 提示框Dialog

提示框通常没有加载框那么酷炫的动效，一般以简洁为主要风格。

### material-dialogs

一个简单易用的material风格的dialog

项目地址：[https://github.com/afollestad/material-dialogs](https://github.com/afollestad/material-dialogs)

效果图：

![](https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/mddemoshowcase.png)

### sweet-alert-dialog

这个项目最后维护时间是两年前，现在可能都没人维护了，但是实现的效果还是挺好的

项目地址：[https://github.com/pedant/sweet-alert-dialog]](https://github.com/pedant/sweet-alert-dialog])

效果图：

![](https://github.com/pedant/sweet-alert-dialog/raw/master/change_type.gif)

## 指示器Indicator

指示器用来提示用户当前操作到了哪一步。

### StepView

提示操作步骤的巅峰之作，非常符合我的审美。

项目地址：[https://github.com/baoyachi/StepView](https://github.com/baoyachi/StepView)

效果图：

![](https://github.com/baoyachi/StepView/raw/master/art/snapshot.png) 

![](https://github.com/baoyachi/StepView/raw/master/art/vertical_stepview.gif)

### stepper-indicator

一个和StepView差不多效果的步骤指示器。

项目地址：[https://github.com/badoualy/stepper-indicator](https://github.com/badoualy/stepper-indicator)

效果图：

![](https://github.com/badoualy/stepper-indicator/raw/master/ART/screen.gif)

### SpringIndicator

一个切换使用了贝塞尔曲线的indicator，说实话作者给的示例图很丑，我不是很喜欢，但是我很喜欢贝塞尔曲线，所以这个也拿来放在这里，学习用，实际使用我还是会使用上面两个。

项目地址：[https://github.com/chenupt/SpringIndicator](https://github.com/chenupt/SpringIndicator)

效果图：

![](https://raw.githubusercontent.com/chenupt/SpringIndicator/master/img/si_1.0.0.gif)

## 贝塞尔曲线

贝塞尔曲线，原来不知道是什么东西，后来发现这个东西太神奇了，很多地方都有用，类似QQ未读消息，拖动消失那个效果，拖动到断裂之前，就是二阶贝塞尔曲线的效果，小面汇总了一个演示1-7阶贝塞尔曲线形成动画的库，和三个使用二阶贝塞尔曲线实现类似qq未读消息小红点拖动消失效果的控件。

### BezierMaker

这个开源库演示了1-7阶贝塞尔曲线的形成过程，让我们直观的看到1-7阶贝塞尔曲线的形成动画，相当牛逼

项目地址：[https://github.com/venshine/BezierMaker](https://github.com/venshine/BezierMaker)

效果图：

![](https://github.com/venshine/BezierMaker/raw/master/screenshot/2.gif)

### Bubble-Notification

一个模仿qq未读消息小红点拖动消失效果的控件。

项目地址：[https://github.com/dkmeteor/Bubble-Notification](https://github.com/dkmeteor/Bubble-Notification)

效果图：

![](https://github.com/dkmeteor/Bubble-Notification/raw/master/gif/list_demo2.gif)

### DraggableFlagView

另一个模仿qq未读消息小红点拖动消失效果的控件。

项目地址：[https://github.com/wangjiegulu/DraggableFlagView](https://github.com/wangjiegulu/DraggableFlagView)

效果图：

![](https://raw.githubusercontent.com/wangjiegulu/DraggableFlagView/master/screenshot/draggableflagview.gif)

### BezierDemo

又一个模仿qq未读消息小红点拖动消失效果的控件。

项目地址：[https://github.com/chenupt/BezierDemo](https://github.com/chenupt/BezierDemo)

效果图：

![](https://raw.githubusercontent.com/chenupt/BezierDemo/master/pic/bezier.gif)













