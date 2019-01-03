
## 设计模式

  - 工厂模式 ()
  - 单例模式（single）
  - 观察者模式（订阅/发布, 事件系统）
  - 门面模式 (face,静态代理)
  - 依赖注入 (依赖容器（DI）注册)

## 数据库

 - 三范式

  - 1.必须建立主键，并且要求每一个字段都是原子不可分的
  - 2.要求所非主键字段依赖主键，不能产生部分依赖
  - 3.所有非主键不能与主键产生之间传递依赖

- 优化

  - 1.建表阶段，合理规划字段值类型，表大小，
  - 2.缓存

  - myisam

- 排序算法

 - 快速排序 ：
  - 1.从数据中，选一个作为基准数，一般为第一个或者最后一个
  - 2.扫描数列，以基准元素为比较对象，把数列分成两个区。
    规则是：小的移动到基准元素前面，大的移到后面，相等的前后都可以。
    分区完成之后，基准元素就处于数列的中间位置。
 - 冒泡排序
   - 1.每次比较，较大的数往下沉，较小的往上冒
 - 插入排序
   - 1.将需要排序的数，与前面已经排好序的数据从后往前进行比较，使其插入到相应的位置
 - 选择排序
   - 1.每次都选择最小的元素，往前排
 - 合并排序


