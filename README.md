# youdao
1. 主要面对linux系统使用过程中查阅单词，原理当然也很简单，所以是自己使用啦
2. 尽量保证使用过程中不会出现严重错误（当然还需要之后使用的时候再看啦）
3. 主函数在参数获取时支持 -tbw ... 方式和 --web -t -b ... 方式获取, 使用前一种方法时参数长度限制为两个,即需要查询的内容必须在前两个参数中,
并且不能以-开头
4. 翻译句子的时候请使用引号将句子引用起来
5. 添加彩色输出~~~自己才会需要的吧

## 历史版本

+ 1.1.4 ==> 添加新选项, -a --all 输出所有可选输出
+ 1.1.5 ==> 允许不使用引号查询空格隔开的句子
+ 1.1.6 ==> 修改json获取异常处理
+ 1.1.7 ==> 网络连接验证机制导致返回数据被强制重定向问题判断
+ 2.0.0 ==> 添加本地数据库缓存数据，离线可用



> 装饰器果然还是方便诶~~然而应该会降低效率的吧....
