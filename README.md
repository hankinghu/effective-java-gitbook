# 目录

* [第一章. 创建和销毁对象](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/README.md)
  * [01. 考虑使用静态工厂方法替代构造方法](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/01.-kao-lv-shi-yong-jing-tai-gong-chang-fang-fa-ti-dai-gou-zao-fang-fa.md)
  * [02. 当构造方法参数过多时使用builder模式](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/untitled.md)
  * [03. 使用私有构造方法或枚类实现Singleton属性](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/untitled-1.md)
  * [04. 使用私有构造方法执行非实例化](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/untitled-2.md)
  * [05. 依赖注入优于硬连接资源\(hardwiring resources\)](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/untitled-3.md)
  * [06. 避免创建不必要的对象](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/untitled-4.md)
  * [07. 消除过期的对象引用](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/07.-xiao-chu-guo-qi-de-dui-xiang-yin-yong.md)
  * [08. 避免使用Finalizer和Cleaner机制](di-yi-zhang-.-chuang-jian-he-xiao-hui-dui-xiang/08.-bi-mian-shi-yong-finalizer-he-cleaner-ji-zhi.md)
* [第二章.对象的公共方法](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/README.md)
  * [09. 使用try-with-resources语句替代try-finally语句](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/09.-shi-yong-trywithresources-yu-ju-ti-dai-tryfinally-yu-ju.md)
  * [10. 重写equals方法时遵守通用约定](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/10.-zhong-xie-equals-fang-fa-shi-zun-shou-tong-yong-yue-ding.md)
  * [11. 重写equals方法时同时也要重写hashcode方法](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/11.-zhong-xie-equals-fang-fa-shi-tong-shi-ye-yao-zhong-xie-hashcode-fang-fa.md)
  * [12. 始终重写 toString 方法](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/12.-shi-zhong-zhong-xie-tostring-fang-fa.md)
  * [13. 谨慎地重写 clone 方法](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/13.-jin-shen-di-zhong-xie-clone-fang-fa.md)
  * [14. 考虑实现Comparable接口](di-er-zhang-.-dui-xiang-de-gong-gong-fang-fa/14.-kao-lv-shi-xian-comparable-jie-kou.md)
* [第三章.类和接口](di-san-zhang-.-lei-he-jie-kou/README.md)
  * [15. 使类和成员的可访问性最小化](di-san-zhang-.-lei-he-jie-kou/15.-shi-lei-he-cheng-yuan-de-ke-fang-wen-xing-zui-xiao-hua.md)
  * [16. 在公共类中使用访问方法而不是公共属性](di-san-zhang-.-lei-he-jie-kou/16.-zai-gong-gong-lei-zhong-shi-yong-fang-wen-fang-fa-er-bu-shi-gong-gong-shu-xing.md)
  * [17. 最小化可变性](di-san-zhang-.-lei-he-jie-kou/17.-zui-xiao-hua-ke-bian-xing.md)
  * [18. 组合优于继承](di-san-zhang-.-lei-he-jie-kou/18.-zu-he-you-yu-ji-cheng.md)
  * [19. 要么设计继承并提供文档说明，要么禁用继承](di-san-zhang-.-lei-he-jie-kou/19.-yao-me-she-ji-ji-cheng-bing-ti-gong-wen-dang-shuo-ming-yao-me-jin-yong-ji-cheng.md)
  * [20. 接口优于抽象类](di-san-zhang-.-lei-he-jie-kou/20.-jie-kou-you-yu-chou-xiang-lei.md)
  * [21. 为后代设计接口](di-san-zhang-.-lei-he-jie-kou/21.-wei-hou-dai-she-ji-jie-kou.md)
  * [22. 接口仅用来定义类型](di-san-zhang-.-lei-he-jie-kou/22.-jie-kou-jin-yong-lai-ding-yi-lei-xing.md)
  * [23. 类层次结构优于标签类](di-san-zhang-.-lei-he-jie-kou/23.-lei-ceng-ci-jie-gou-you-yu-biao-qian-lei.md)
  * [24. 支持使用静态成员类而不是非静态类](di-san-zhang-.-lei-he-jie-kou/24.-zhi-chi-shi-yong-jing-tai-cheng-yuan-lei-er-bu-shi-fei-jing-tai-lei.md)
  * [25. 将源文件限制为单个顶级类](di-san-zhang-.-lei-he-jie-kou/25.-jiang-yuan-wen-jian-xian-zhi-wei-dan-ge-ding-ji-lei.md)
* [第四章. 泛型](di-si-zhang-.-fan-xing/README.md)
  * [26. 不要使用原始类型](di-si-zhang-.-fan-xing/26.-bu-yao-shi-yong-yuan-shi-lei-xing.md)
  * [27. 消除非检查警告](di-si-zhang-.-fan-xing/27.-xiao-chu-fei-jian-cha-jing-gao.md)
  * [28. 列表优于数组](di-si-zhang-.-fan-xing/28.-lie-biao-you-yu-shu-zu.md)
  * [29. 优先考虑泛型](di-si-zhang-.-fan-xing/29.-you-xian-kao-lv-fan-xing.md)
  * [30. 优先使用泛型方法](di-si-zhang-.-fan-xing/30.-you-xian-shi-yong-fan-xing-fang-fa.md)
  * [31. 使用限定通配符来增加API的灵活性](di-si-zhang-.-fan-xing/31.-shi-yong-xian-ding-tong-pei-fu-lai-zeng-jia-api-de-ling-huo-xing.md)
  * [32. 合理地结合泛型和可变参数](di-si-zhang-.-fan-xing/32.-he-li-di-jie-he-fan-xing-he-ke-bian-can-shu.md)
  * [33. 优先考虑类型安全的异构容器](di-si-zhang-.-fan-xing/33.-you-xian-kao-lv-lei-xing-an-quan-de-yi-gou-rong-qi.md)
* [第五章. 枚举和注解](di-wu-zhang-.-mei-ju-he-zhu-jie/README.md)
  * [34. 使用枚举类型替代整型常量](di-wu-zhang-.-mei-ju-he-zhu-jie/34.-shi-yong-mei-ju-lei-xing-ti-dai-zheng-xing-chang-liang.md)
  * [35. 使用实例属性替代序数](di-wu-zhang-.-mei-ju-he-zhu-jie/35.-shi-yong-shi-li-shu-xing-ti-dai-xu-shu.md)
  * [36. 使用EnumSet替代位属性](di-wu-zhang-.-mei-ju-he-zhu-jie/36.-shi-yong-enumset-ti-dai-wei-shu-xing.md)
  * [37. 使用EnumMap替代序数索引](di-wu-zhang-.-mei-ju-he-zhu-jie/37.-shi-yong-enummap-ti-dai-xu-shu-suo-yin.md)
  * [38. 使用接口模拟可扩展的枚举](di-wu-zhang-.-mei-ju-he-zhu-jie/38.-shi-yong-jie-kou-mo-ni-ke-kuo-zhan-de-mei-ju.md)
  * [39. 注解优于命名模式](di-wu-zhang-.-mei-ju-he-zhu-jie/39.-zhu-jie-you-yu-ming-ming-mo-shi.md)
  * [40. 始终使用Override注解](di-wu-zhang-.-mei-ju-he-zhu-jie/40.-shi-zhong-shi-yong-override-zhu-jie.md)
  * [41. 使用标记接口定义类型](di-wu-zhang-.-mei-ju-he-zhu-jie/41.-shi-yong-biao-ji-jie-kou-ding-yi-lei-xing.md)
  * [42. lambda表达式优于匿名类](di-wu-zhang-.-mei-ju-he-zhu-jie/42.-lambda-biao-da-shi-you-yu-ni-ming-lei.md)
* [第六章. Lambdas 表达式和流](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/README.md)
  * [42. lambda表达式优于匿名类](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/42.-lambda-biao-da-shi-you-yu-ni-ming-lei-1.md)
  * [43. 方法引用优于lambda表达式](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/43.-fang-fa-yin-yong-you-yu-lambda-biao-da-shi.md)
  * [44. 优先使用标准的函数式接口](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/44.-you-xian-shi-yong-biao-zhun-de-han-shu-shi-jie-kou.md)
  * [45. 明智审慎地使用Stream](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/45.-ming-zhi-shen-shen-di-shi-yong-stream.md)
  * [46. 优先考虑流中无副作用的函数](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/46.-you-xian-kao-lv-liu-zhong-wu-fu-zuo-yong-de-han-shu.md)
  * [47. 优先使用Collection而不是Stream来作为方法的返回类型](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/47.-you-xian-shi-yong-collection-er-bu-shi-stream-lai-zuo-wei-fang-fa-de-fan-hui-lei-xing.md)
  * [48. 谨慎使用流并行](di-liu-zhang-.-lambdas-biao-da-shi-he-liu/48.-jin-shen-shi-yong-liu-bing-hang.md)
* [第七章. 方法](di-qi-zhang-.-fang-fa/README.md)
  * [49. 检查参数有效性](di-qi-zhang-.-fang-fa/49.-jian-cha-can-shu-you-xiao-xing.md)
  * [50. 必要时进行防御性拷贝](di-qi-zhang-.-fang-fa/50.-bi-yao-shi-jin-hang-fang-yu-xing-kao-bei.md)
  * [51. 仔细设计方法签名](di-qi-zhang-.-fang-fa/51.-zai-xi-she-ji-fang-fa-qian-ming.md)
  * [52. 明智审慎地使用重载](di-qi-zhang-.-fang-fa/52.-ming-zhi-shen-shen-di-shi-yong-zhong-zai.md)
  * [53. 明智审慎地使用可变参数](di-qi-zhang-.-fang-fa/53.-ming-zhi-shen-shen-di-shi-yong-ke-bian-can-shu.md)
  * [54. 返回空的数组或集合，不要返回 null](di-qi-zhang-.-fang-fa/54.-fan-hui-kong-de-shu-zu-huo-ji-he-bu-yao-fan-hui-null.md)
  * [55. 明智审慎地返回 Optional](di-qi-zhang-.-fang-fa/55.-ming-zhi-shen-shen-di-fan-hui-optional.md)
  * [56. 为所有已公开的 API 元素编写文档注释](di-qi-zhang-.-fang-fa/56.-wei-suo-you-yi-gong-kai-de-api-yuan-su-bian-xie-wen-dang-zhu-shi.md)
* [第八章. 通用编程](di-ba-zhang-.-tong-yong-bian-cheng/README.md)
  * [57. 最小化局部变量的作用域](di-ba-zhang-.-tong-yong-bian-cheng/57.-zui-xiao-hua-ju-bu-bian-liang-de-zuo-yong-yu.md)
  * [58. for-each 循环优于传统 for 循环](di-ba-zhang-.-tong-yong-bian-cheng/58.-foreach-xun-huan-you-yu-chuan-tong-for-xun-huan.md)
  * [59. 了解并使用库](di-ba-zhang-.-tong-yong-bian-cheng/59.-le-jie-bing-shi-yong-ku.md)
  * [60. 若需要精确答案就应避免使用 float 和 double 类型](di-ba-zhang-.-tong-yong-bian-cheng/60.-ruo-xu-yao-jing-que-da-an-jiu-ying-bi-mian-shi-yong-float-he-double-lei-xing.md)
  * [61. 基本数据类型优于包装类](di-ba-zhang-.-tong-yong-bian-cheng/61.-ji-ben-shu-ju-lei-xing-you-yu-bao-zhuang-lei.md)
  * [62. 当使用其他类型更合适时应避免使用字符串](di-ba-zhang-.-tong-yong-bian-cheng/62.-dang-shi-yong-qi-ta-lei-xing-geng-he-kuo-shi-ying-bi-mian-shi-yong-zi-fu-chuan.md)
  * [63. 当心字符串连接引起的性能问题](di-ba-zhang-.-tong-yong-bian-cheng/63.-dang-xin-zi-fu-chuan-lian-jie-yin-qi-de-xing-neng-wen-ti.md)
  * [64. 通过接口引用对象](di-ba-zhang-.-tong-yong-bian-cheng/64.-tong-guo-jie-kou-yin-yong-dui-xiang.md)
  * [65. 接口优于反射](di-ba-zhang-.-tong-yong-bian-cheng/65.-jie-kou-you-yu-fan-she.md)
  * [66. 明智审慎地本地方法](di-ba-zhang-.-tong-yong-bian-cheng/66.-ming-zhi-shen-shen-di-ben-di-fang-fa.md)
  * [67. 明智审慎地进行优化](di-ba-zhang-.-tong-yong-bian-cheng/67.-ming-zhi-shen-shen-di-jin-hang-you-hua.md)
  * [68. 遵守被广泛认可的命名约定](di-ba-zhang-.-tong-yong-bian-cheng/68.-zun-shou-bei-guang-fan-ren-ke-de-ming-ming-yue-ding.md)
* [第九章. 异常](di-jiu-zhang-.-yi-chang/README.md)
  * [69. 只针对异常的情况下才使用异常](di-jiu-zhang-.-yi-chang/69.-zhi-zhen-dui-yi-chang-de-qing-kuang-xia-cai-shi-yong-yi-chang.md)
  * [70. 对可恢复的情况使用受检异常，对编程错误使用运行时异常](di-jiu-zhang-.-yi-chang/70.-dui-ke-hui-fu-de-qing-kuang-shi-yong-shou-jian-yi-chang-dui-bian-cheng-cuo-wu-shi-yong-yun-hang.md)
  * [71. 避免不必要的使用受检异常](di-jiu-zhang-.-yi-chang/71.-bi-mian-bu-bi-yao-de-shi-yong-shou-jian-yi-chang.md)
  * [72. 优先使用标准的异常](di-jiu-zhang-.-yi-chang/72.-you-xian-shi-yong-biao-zhun-de-yi-chang.md)
  * [73. 抛出与抽象对应的异常](di-jiu-zhang-.-yi-chang/73.-pao-chu-yu-chou-xiang-dui-ying-de-yi-chang.md)
  * [74. 每个方法抛出的异常都需要创建文档](di-jiu-zhang-.-yi-chang/74.-mei-ge-fang-fa-pao-chu-de-yi-chang-du-xu-yao-chuang-jian-wen-dang.md)
  * [75. 在细节消息中包含失败一捕获信息](di-jiu-zhang-.-yi-chang/75.-zai-xi-jie-xiao-xi-zhong-bao-han-shi-bai-yi-bu-huo-xin-xi.md)
  * [76. 保持失败原子性](di-jiu-zhang-.-yi-chang/76.-bao-chi-shi-bai-yuan-zi-xing.md)
  * [77. 不要忽略异常](di-jiu-zhang-.-yi-chang/77.-bu-yao-hu-lve-yi-chang.md)
* [第十章. 并发](di-shi-zhang-.-bing-fa/README.md)
  * [78. 同步访问共享的可变数据](di-shi-zhang-.-bing-fa/78.-tong-bu-fang-wen-gong-xiang-de-ke-bian-shu-ju.md)
  * [79. 避免过度同步](di-shi-zhang-.-bing-fa/79.-bi-mian-guo-du-tong-bu.md)
  * [80. executor 、task 和 stream 优先于线程](di-shi-zhang-.-bing-fa/80.-executor-task-he-stream-you-xian-yu-xian-cheng.md)
  * [81. 并发工具优于 wait 和 notify](di-shi-zhang-.-bing-fa/81.-bing-fa-gong-ju-you-yu-wait-he-notify.md)
  * [82. 文档应包含线程安全属性](di-shi-zhang-.-bing-fa/82.-wen-dang-ying-bao-han-xian-cheng-an-quan-shu-xing.md)
  * [83. 明智审慎的使用延迟初始化](di-shi-zhang-.-bing-fa/83.-ming-zhi-shen-shen-de-shi-yong-yan-chi-chu-shi-hua.md)
  * [84. 不要依赖线程调度器](di-shi-zhang-.-bing-fa/84.-bu-yao-yi-lai-xian-cheng-tiao-du-qi.md)
* [第十一章. 序列化](di-shi-yi-zhang-.-xu-lie-hua/README.md)
  * [85. 优先选择 Java 序列化的替代方案](di-shi-yi-zhang-.-xu-lie-hua/85.-you-xian-xuan-ze-java-xu-lie-hua-de-ti-dai-fang-an.md)
  * [86. 非常谨慎地实现 Serializable](di-shi-yi-zhang-.-xu-lie-hua/86.-fei-chang-jin-shen-di-shi-xian-serializable.md)
  * [87. 考虑使用自定义的序列化形式](di-shi-yi-zhang-.-xu-lie-hua/87.-kao-lv-shi-yong-zi-ding-yi-de-xu-lie-hua-xing-shi.md)
  * [88. 保护性的编写 readObject 方法](di-shi-yi-zhang-.-xu-lie-hua/88.-bao-hu-xing-de-bian-xie-readobject-fang-fa.md)
  * [89. 对于实例控制，枚举类型优于 readResolve](di-shi-yi-zhang-.-xu-lie-hua/89.-dui-yu-shi-li-kong-zhi-mei-ju-lei-xing-you-yu-readresolve.md)
  * [90. 考虑用序列化代理代替序列化实例](di-shi-yi-zhang-.-xu-lie-hua/90.-kao-lv-yong-xu-lie-hua-dai-li-dai-ti-xu-lie-hua-shi-li.md)

