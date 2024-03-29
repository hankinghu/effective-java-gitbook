# 目录

* [x] 第一章. 创建和销毁对象
  * 01. 考虑使用静态工厂方法替代构造方法
  * 02. 当构造方法参数过多时使用builder模式
  * 03. 使用私有构造方法或枚类实现Singleton属性
  * 04. 使用私有构造方法执行非实例化
  * 05. 依赖注入优于硬连接资源\(hardwiring resources\)
  * 06. 避免创建不必要的对象
  * 07. 消除过期的对象引用
  * 08. 避免使用Finalizer和Cleaner机制
* [ ] 第二章.对象的公共方法
  * 09. 使用try-with-resources语句替代try-finally语句
  * 10. 重写equals方法时遵守通用约定
  * 11. 重写equals方法时同时也要重写hashcode方法
  * 12. 始终重写 toString 方法
  * 13. 谨慎地重写 clone 方法
  * 14. 考虑实现Comparable接口
* [ ] 第三章.类和接口
  * 15. 使类和成员的可访问性最小化
  * 16. 在公共类中使用访问方法而不是公共属性
  * 17. 最小化可变性
  * 18. 组合优于继承
  * 19. 要么设计继承并提供文档说明，要么禁用继承
  * 20. 接口优于抽象类
  * 21. 为后代设计接口
  * 22. 接口仅用来定义类型
  * 23. 类层次结构优于标签类
  * 24. 支持使用静态成员类而不是非静态类
  * 25. 将源文件限制为单个顶级类
* [ ] 第四章. 泛型
  * 26. 不要使用原始类型
  * 27. 消除非检查警告
  * 28. 列表优于数组
  * 29. 优先考虑泛型
  * 30. 优先使用泛型方法
  * 31. 使用限定通配符来增加API的灵活性
  * 32. 合理地结合泛型和可变参数
  * 33. 优先考虑类型安全的异构容器
* [ ] 第五章. 枚举和注解
  * 34. 使用枚举类型替代整型常量
  * 35. 使用实例属性替代序数
  * 36. 使用EnumSet替代位属性
  * 37. 使用EnumMap替代序数索引
  * 38. 使用接口模拟可扩展的枚举
  * 39. 注解优于命名模式
  * 40. 始终使用Override注解
  * 41. 使用标记接口定义类型
  * 42. lambda表达式优于匿名类
* [ ] 第六章. Lambdas 表达式和流
  * 42. lambda表达式优于匿名类
  * 43. 方法引用优于lambda表达式
  * 44. 优先使用标准的函数式接口
  * 45. 明智审慎地使用Stream
  * 46. 优先考虑流中无副作用的函数
  * 47. 优先使用Collection而不是Stream来作为方法的返回类型
  * 48. 谨慎使用流并行
* [ ] 第七章. 方法
  * 49. 检查参数有效性
  * 50. 必要时进行防御性拷贝
  * 51. 仔细设计方法签名
  * 52. 明智审慎地使用重载
  * 53. 明智审慎地使用可变参数
  * 54. 返回空的数组或集合，不要返回 null
  * 55. 明智审慎地返回 Optional
  * 56. 为所有已公开的 API 元素编写文档注释
* [ ] 第八章. 通用编程
  * 57. 最小化局部变量的作用域
  * 58. for-each 循环优于传统 for 循环
  * 59. 了解并使用库
  * 60. 若需要精确答案就应避免使用 float 和 double 类型
  * 61. 基本数据类型优于包装类
  * 62. 当使用其他类型更合适时应避免使用字符串
  * 63. 当心字符串连接引起的性能问题
  * 64. 通过接口引用对象
  * 65. 接口优于反射
  * 66. 明智审慎地本地方法
  * 67. 明智审慎地进行优化
  * 68. 遵守被广泛认可的命名约定
* [ ] 第九章. 异常
  * 69. 只针对异常的情况下才使用异常
  * 70. 对可恢复的情况使用受检异常，对编程错误使用运行时异常
  * 71. 避免不必要的使用受检异常
  * 72. 优先使用标准的异常
  * 73. 抛出与抽象对应的异常
  * 74. 每个方法抛出的异常都需要创建文档
  * 75. 在细节消息中包含失败一捕获信息
  * 76. 保持失败原子性
  * 77. 不要忽略异常
* [ ] 第十章. 并发
  * 78. 同步访问共享的可变数据
  * 79. 避免过度同步
  * 80. executor 、task 和 stream 优先于线程
  * 81. 并发工具优于 wait 和 notify
  * 82. 文档应包含线程安全属性
  * 83. 明智审慎的使用延迟初始化
  * 84. 不要依赖线程调度器
* [ ] 第十一章. 序列化
  * 85. 优先选择 Java 序列化的替代方案
  * 86. 非常谨慎地实现 Serializable
  * 87. 考虑使用自定义的序列化形式
  * 88. 保护性的编写 readObject 方法
  * 89. 对于实例控制，枚举类型优于 readResolve
  * 90. 考虑用序列化代理代替序列化实例

