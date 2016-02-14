```
Creative Commons Legal Code

Attribution-ShareAlike 3.0 Unported

    CREATIVE COMMONS CORPORATION IS NOT A LAW FIRM AND DOES NOT PROVIDE
    LEGAL SERVICES. DISTRIBUTION OF THIS LICENSE DOES NOT CREATE AN
    ATTORNEY-CLIENT RELATIONSHIP. CREATIVE COMMONS PROVIDES THIS
    INFORMATION ON AN "AS-IS" BASIS. CREATIVE COMMONS MAKES NO WARRANTIES
    REGARDING THE INFORMATION PROVIDED, AND DISCLAIMS LIABILITY FOR
    DAMAGES RESULTING FROM ITS USE.
```

# Preface

我在微信里也就那么随便一说，我用手指头和脚趾头数了下，2016年13个月正好可以写个流媒体B篇，
也就是十三篇；说者无意，听着有心，非要我把这个B篇给装下去；我是写过书的人，深知道书是不能写的，
尤其是有内涵的书是不能写的，因为没有读者啊，都喜欢看芈月传，有什么内涵？

```
将士们，我承诺你们，写完这行代码，我就赏你一个鼓励师。。。
```

我其实不过是连续白天黑夜写了一个春节的代码，把HLS+写出来了，觉得无聊而已，吹出去的牛就像波出去的水，
只要硬着头皮写B篇了。这个前言其实叫Preface，绝对正宗的英文，我特地翻了翻我买的《OOAD》原版。
刚刚说到是不能写书的，我也没有打算写书，也就是吹牛装B而已；我也不能吹太深了，太深我们盛老板会打死我，
也不能吹太浅了，太浅了看微信文章的会骂死我，所以人是很难做的。

嗯，考虑良久，这个《流服务器B篇》，英文名叫《SRSB》，中文名叫《流服务器十三篇》，
必须得让读者有一点点收获，但是不能收获太大了。

盛老板是谁？我们公司幕后的最大老板，家里有产黄金的韭菜，他特有钱，不要说我们公司只做七牛那样的伪CDN，
我告诉你们，我们盛老板已经在和三大运营商谈收购，他割一年的黄金韭菜，就可以把三大运营商全部买下来，
把其他业务通通停掉，只留服务器机房和带宽，然后安装上SRS做我们自己的CDN。哈哈哈，怕了吧~

我如何让大家有点点收获呢？流服务器是服务器的一种，在互联网上只有两种提供内容的服务器，一个叫nginx，
也就是web或文件服务器；一种叫srs，叫做流媒体服务器。大牛肯定会说，shit胡说八道，其实还有好多——
是啊，还有好多，但是牛逼的只有这两种服务器。哈哈哈，服了吧~

我如何让大家有点收获呢？因为我是SRS作者啊，SRS2.0代码我已经删除了，想看你也看不到了，但我可以分析，
你可以想象最牛逼的服务器应该是什么样子的。我们可以一起想象啊。。。

我如何让大家有点收获呢？上面两点其实都不靠谱，其实说真的，流服务器有几个问题需要解决的，不管是SRS，
还是nginx-rtmp，还是red5，还是秀场和游戏直播，还是其他的流媒体，是有几个问题需要解决，可惜目前，
国内普及基本流媒体的资料太少，只能靠自己摸索，所以有了我可乘之机，懂了吧？

要是你觉得没有什么逻辑，那就对了，装B是不需要逻辑的。我想到哪里就写哪里，大致这个大B分为一下十三篇：

1. Concurrentcy，懂么？并发呀，流服务器的并发，和一般WEB的并发是不一样的哦。

其他的我再说吧。你如果想知道点啥，也可以加我微信群，下面是二维码：

![Weixin](http://ossrs.net/srsb/weixin.png)

如果过期了，那就只能加我微信：winterserver，我再加你到群里吧。懂了吧？

Winlin 2016.2