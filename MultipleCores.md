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

# Multiple Cores

多核(Multiple Cores)属于高性能的范畴，高性能是什么？下载一个日本的成人武打片，男主人公就是高性能服务器，
也能并发服务好几个客户，那个频率那个幅度，那就是传说中的高性能！过来人都知道，然并卵。

> 备注：高性能多核，然并卵。

多核性能基本上等于单核性能的叠加，不过在一些问题上还是有区别的，譬如进程间通信、进程负载均衡、软中断等。
虽然SRS是单进程单线程即单核能力，本人早在SRS之前就实现过多核流服务器，让我给你吹一下牛B。

2016.3
