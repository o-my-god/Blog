软件开发知识汇总
========

### 订阅
点击本页面右上角的 Watch 在弹出框中点击 Watching 订阅本博客，这样本博客的所有文章更新和评论都会在github首页出现。

当前互联网上的知识太多，并且杂乱，此博客对软件开发经典文章进行汇总分类，帮助开发者可以快速的学习。

## Posts
* [性能调优相关文章](#性能调优相关文章)<br>
     * [性能监视跟踪工具](#性能监视跟踪工具)<br>
     * [性能调优知识](#性能调优知识)<br>
* [网络服务器编程](#网络服务器编程)<br>
     * [不为人知的网络编程](#不为人知的网络编程)<br>
     * [高性能网络编程](#高性能网络编程)<br>
     * [从根上了解高并发](#从根上了解高并发)<br>
* [操作系统相关知识](#操作系统相关知识)<br>
     * [内存](#内存)<br>
* [中间件相关知识](#中间件相关知识)<br>
     * [redis](#redis)<br>
* [分布式相关知识](#分布式相关知识)<br>

### 网络服务开发三俩儿事系列

- [什么是并发](https://github.com/o-my-god/Blog/wiki/什么是并发)

- [为什么使用并发](https://github.com/o-my-god/Blog/wiki/为什么使用并发)

- [并发的基本挑战](https://github.com/o-my-god/Blog/wiki/并发的基本挑战)

- [并发问题的根源](https://github.com/o-my-god/Blog/wiki/并发问题的根源)

- [并发与操作系统](https://github.com/o-my-god/Blog/wiki/并发和操作系统)

- [如何评估锁的实现](https://github.com/o-my-god/Blog/wiki/如何评估锁的实现)

### 性能调优相关文章
**brendan gregg大神Linux观测工具**
![brendan gregg大神Linux观测工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_observability_tools.png "brendan gregg大神Linux观测工具")
**brendan gregg大神Linux观测工具**
![brendan gregg大神Linux基准测试工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_benchmarking_tools.png)
**brendan gregg大神Linux调优工具**
![brendan gregg大神Linux调优工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_tuning_tools.png)
**brendan gregg大神sar工具**
![brendan gregg大神Linux调优工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_observability_sar.png)
**iperf3性能测试工具**
![iperf3性能测试工具](https://github.com/o-my-god/Blog/blob/master/resource/iperf3.png)

#### 性能监视、跟踪工具
- [uptime系统负载监测] https://linux.cn/article-2334-1.html 
- [top、htop、mpstat CPU使用率监测] https://linuxconfig.org/how-to-check-and-monitor-cpu-utilization-on-linux
- [使用 ftrace 跟踪内核] https://linux.cn/article-9838-1.html
- [深入探究Linux Kprobe机制] https://mp.weixin.qq.com/s/5OKwGxwh6qwui7JdaJ82VA
- [这才是kprobe工作的本质] https://mp.weixin.qq.com/s/ATzNIVLv2cr1wxLUZBxlhw
- [内核调测工具kprobe之实践篇] https://mp.weixin.qq.com/s/aKO5mli6RW74h5VaiZlaWQ
- [perf工具使用] https://segmentfault.com/a/1190000021465563
- [redhat系统调优手册] https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/monitoring_and_managing_system_status_and_performance/getting-started-with-perf_monitoring-and-managing-system-status-and-performance
#### 性能调优知识
- [CPU Utilization is Wrong] http://www.brendangregg.com/blog/2017-05-09/cpu-utilization-is-wrong.html
- [The PMCs of EC2: Measuring IPC] http://www.brendangregg.com/blog/2017-05-04/the-pmcs-of-ec2.html
- [Off-CPU Analysis] http://www.brendangregg.com/offcpuanalysis.html
- [利用perf功能检测false sharing问题] https://easyperf.net/blog/2019/12/17/Detecting-false-sharing-using-perf
- [使用 perf 进行性能分析时如何获取准确的调用栈] https://gaomf.cn/2019/10/30/perf_stack_traceback/
- [Run Queue Latency案例] https://mp.weixin.qq.com/s/AzcB1DwqRCoiofOOI88T9Q
- [理解 %IOWAIT (%WIO)] https://www.linuxprobe.com/understand-iowait.html
- [Iowait的成因、对系统影响及对策] https://cloud.tencent.com/developer/article/1071025
- [perf sched for Linux CPU scheduler analysis] http://www.brendangregg.com/blog/2017-03-16/perf-sched.html
- [perf example] http://www.brendangregg.com/perf.html#SchedulerAnalysis
- [context switch耗时测量方法] https://www.usenix.org/legacy/events/expcs07/papers/2-li.pdf
- [思科路由v4、v6协议栈性能对比测试] https://www.cisco.com/c/dam/en_us/solutions/industries/docs/gov/performance-comparisons.pdf
- [宋宝华：谈一谈Linux让实时/高性能任务独占CPU的事] https://mp.weixin.qq.com/s/_NwWD5CM1tda6lJXYFjnSQ
- [为了追求更快，CPU、内存、I/O都做了哪些努力？] https://mp.weixin.qq.com/s/oxwRX642qXpakyUSFHN4Nw
- [Socket缓存是如何影响TCP性能的？] https://zhuanlan.zhihu.com/p/237610474?utm_source=wechat_session
- [Thinking Clearly about Performance-Improving the performance of complex software is difficult, but understanding some fundamental principles can make it easier.]
  https://queue.acm.org/detail.cfm?id=1854041
#### 性能优化方法
- [linux内核percpu变量的实现] https://mp.weixin.qq.com/s/CwBmsJcKYEI6wejqollbpg
- [Dropbox 高吞吐量低延迟 Web 服务器优化之法] https://www.infoq.cn/article/optimizing-web-servers-for-high-throughput-and-l
- [C10M性能问题] https://my.oschina.net/u/572632/blog/666522
- [Monitoring and Tuning the Linux Networking Stack: Receiving Data] https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/
- [Optimizing Applications for NUMA] https://software.intel.com/content/www/us/en/develop/articles/optimizing-applications-for-numa.html
### 网络服务器编程
#### 不为人知的网络编程
- [不为人知的网络编程(一)：浅析TCP协议中的疑难杂症(上篇)] http://www.52im.net/thread-1003-1-1.html
- [不为人知的网络编程(二)：浅析TCP协议中的疑难杂症(下篇)] http://www.52im.net/thread-1004-1-1.html
- [不为人知的网络编程(三)：关闭TCP连接时为什么会TIME_WAIT、CLOSE_WAIT] http://www.52im.net/thread-1007-1-1.html
- [不为人知的网络编程(四)：深入研究分析TCP的异常关闭] http://www.52im.net/thread-1014-1-1.html
- [不为人知的网络编程(五)：UDP的连接性和负载均衡] http://www.52im.net/thread-1018-1-1.html
- [不为人知的网络编程(六)：深入地理解UDP协议并用好它] http://www.52im.net/thread-1024-1-1.html
- [不为人知的网络编程(七)：如何让不可靠的UDP变的可靠？] http://www.52im.net/thread-1293-1-1.html
- [不为人知的网络编程(八)：从数据传输层深度解密HTTP] http://www.52im.net/thread-2456-1-1.html
- [不为人知的网络编程(九)：理论联系实际，全方位深入理解DNS] http://www.52im.net/thread-2740-1-1.html
- [不为人知的网络编程(十)：深入操作系统，从内核理解网络包的接收过程(Linux篇)] http://www.52im.net/thread-3247-1-1.html
- [不为人知的网络编程(十一)：从底层入手，深度分析TCP连接耗时的秘密] http://www.52im.net/thread-3265-1-1.html

#### 高性能网络编程
- [高性能网络编程(一)：单台服务器并发TCP连接数到底可以有多少] http://www.52im.net/thread-561-1-1.html
- [高性能网络编程(二)：上一个10年，著名的C10K并发连接问题] http://www.52im.net/thread-566-1-1.html
- [高性能网络编程(三)：下一个10年，是时候考虑C10M并发问题了] http://www.52im.net/thread-568-1-1.html
- [高性能网络编程(四)：从C10K到C10M高性能网络应用的理论探索] http://www.52im.net/thread-578-1-1.html
- [高性能网络编程(五)：一文读懂高性能网络编程中的I/O模型] http://www.52im.net/thread-1935-1-1.html
- [高性能网络编程(六)：一文读懂高性能网络编程中的线程模型] http://www.52im.net/thread-1939-1-1.html
- [高性能网络编程(七)：到底什么是高并发？一文即懂！] http://www.52im.net/thread-3120-1-1.html
- [高性能网络编程经典：《The C10K problem(英文)》[附件下载]] http://www.52im.net/thread-560-1-1.html

#### 从根上了解高并发
- [从根上理解高性能、高并发(一)：深入计算机底层，理解线程与线程池] http://www.52im.net/thread-3272-1-1.html
- [从根上理解高性能、高并发(二)：深入操作系统，理解I/O与零拷贝技术] http://www.52im.net/thread-3280-1-1.html
- [从根上理解高性能、高并发(三)：深入操作系统，彻底理解I/O多路复用] http://www.52im.net/thread-3287-1-1.html
- [从根上理解高性能、高并发(四)：深入操作系统，彻底理解同步与异步] http://www.52im.net/thread-3296-1-1.html
- [从根上理解高性能、高并发(五)：深入操作系统，理解高并发中的协程] http://www.52im.net/thread-3306-1-1.html
- [从根上理解高性能、高并发(六)：通俗易懂，高性能服务器到底是如何实现的] http://www.52im.net/thread-3315-1-1.html

### 操作系统相关知识
#### 内存
- [带你深入理解内存对齐最底层原理] https://mp.weixin.qq.com/s/F0NTfz-3x3UxQeF-GSavRg
- [Linux页框分配器之内存碎片化整理] https://mp.weixin.qq.com/s/BmCSg0R8yZcOYnDUQw44pw
- [操作系统内存管理，搞懂这8个问题就够了] https://mp.weixin.qq.com/s/oQbX8XpBDnTmIk9L7UveyA
- [(Mis)Understanding the NUMA Memory System Performance of Multithreaded Workloads] https://www.cse.wustl.edu/~angelee/cse539/papers/numa.pdf

#### 中断
- [CPU明明8个核，网卡为啥拼命折腾一号核？] https://mp.weixin.qq.com/s/Xf3sbkJFWDQ7bzhKFEmkzA

#### 网络
- [Queueing in the Linux Network Stack] https://www.linuxjournal.com/content/queueing-linux-network-stack
- [Controlling Queue Delay-A modern AQM is just one piece of the solution to bufferbloat.]
  https://queue.acm.org/detail.cfm?id=2209336
- [Epoll is fundamentally broken] https://kernel.taobao.org/2019/12/epoll-is-fundamentally-broken/
- [网络 IO 演变发展过程和模型介绍] https://mp.weixin.qq.com/s/EDzFOo3gcivOe_RgipkTkQ
- [全网惊群本质最透彻的分析] https://zhuanlan.zhihu.com/p/351065391

### 中间件相关知识
#### redis
- [Redis persistence demystified] http://oldblog.antirez.com/post/redis-persistence-demystified.html

### 分布式相关知识
- [distributed systems for fun and profit] http://book.mixu.net/distsys/single-page.html
- [system models for distributed systems] https://www.uio.no/studier/emner/matnat/ifi/INF5040/h11/lectures/SystemModels.pdf
- [FAILURE MODES IN DISTRIBUTED SYSTEMS] https://alvaro-videla.com/2013/12/failure-modes-in-distributed-systems.html
- [如何优雅的重试] https://mp.weixin.qq.com/s/6IkTnUbBlHjM3GM_bT35tA

## 关于作者
- QQ：740016830
