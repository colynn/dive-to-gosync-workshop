# 深入Go并发编程研讨课

Go提供了我们便利的进行并发编程的工具、方法和同步原语，同时也提供给我们诸多的犯错的机会，也就是俗称的“坑”。即使是顶级Go开发的项目，比如Docker、Kubernetes、gRPC、etcd， 都是有经验丰富的Go开发专家锁开发，也踩过不少的并发的坑，而且依然源源不断的继续踩着,即便是标准库也是这样。

幸福总是建立在别人的痛苦之上。分析和总结并发编程中的陷阱，避免重复踩在别人的坑中，正式本次培训课的重要内容。只有深入了解并发原语的实现，全面了解它们的特性和限制场景，注意它们的局限和容易踩的坑，才能提高我们的并发编程的能力。通过了解和学习其他人的经验和贡献的项目和库，我们可以更好的扩展我们的视野，避免重复的造轮子，或者说我们可以制作更好的轮子。

语言的内存模型定义了对变量的读写的可见性，可以清晰而准确读写事件的`happen before`关系。对于我们，可以很好地分析和编排goroutine的运行，避免数据的竞争和不一致的问题。

通过本次课程，你可以:

- 了解基本同步原语的具体实现、hack同步原语进行扩展，了解它们的使用场景和坑，已经别人是怎么踩的
- 了解一些扩展的同步源于，对于标准库sync包的补充
- 对于规模很大的项目，分布式同步原语是必不可少的，带你了解便利的分布式同步原语
- atomic可以保证对数据操作的一致性，利用CAS可以设计lock-free的数据结构
- channel是Go语言进行并发编程的很好的工具，带你了解它的使用姿势
- 了解Go语言的内存模型


## 并发原语综述 (10分钟)

## 基本并发原语 (2小时)

## 扩展并发原语 (1小时)

## 原子操作 (半小时)

## 分布式并发原语 (1小时)

## channel (1小时)

## happenbefore (1小时)

## 习题 (半小时)