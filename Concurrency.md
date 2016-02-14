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

# Concurrency

高并发属于高性能的范畴，高性能是什么？下载一个日本的成人武打片，男主人公就是高性能服务器，
也能并发服务好几个客户，那个频率那个幅度，那就是传说中的高性能！过来人都知道，然并卵。

> 备注：高性能高并发，然并卵。

我们做为服务器作者，还是要关注高并发的，为了装更好的B，造出服务更好的B的服务器，
我们就是岛国武打片的导演，不知道高并发也是不行的。SRS2单核，又怎么样？能同时让7500个客户爽，
在流媒体里面你找不到第二个，那个性能是可以优化的，前提得知道这些是怎么回事，
这篇文章就详细分析流服务器的并发问题。

2016.2
