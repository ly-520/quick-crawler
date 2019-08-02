# quick-crawler
> java实现的爬虫框架

从头开始， 一步一步的实现一个可用的爬虫框架，每个地方加一个里程碑的tag，主要用于记录这个工程的诞生过程



## tag 记录列表

### 1. [v0.001](https://github.com/liuyueyi/quick-crawler/releases/tag/v0.001)

> 实现了一个最简单，最基础的爬虫, 处于能用的阶段


### 2. [v0.002](https://github.com/liuyueyi/quick-crawler/releases/tag/v0.002)

> 利用HttpClient来替代jdk的http请求；新增http参数配置


### 3. [v0.003](https://github.com/liuyueyi/quick-crawler/releases/tag/v0.003)

> 实现深度爬网页

- 支持正向、逆向链接过滤
- 在内存中保存爬取记录，用于去重过滤
- 提供爬取完成后的回调方法，用于结果处理