### 迭代器模式
* 解决问题：不同的方式来遍历整个整合对象。
* 优点： 它支持以不同的方式遍历一个聚合对象；迭代器简化了聚合类；在同一个聚合上可以有多个遍历；在迭代器模式中，增加新的聚合类和迭代器类都很方便，无须修改原有代码。
* 缺点：由于迭代器模式将存储数据和遍历数据的职责分离，增加新的聚合类需要对应增加新的迭代器类，类的个数成对增加，这在一定程度上增加了系统的复杂性。
* **应用场景：**
* 1. 迭代器
* 2. 对象内部元素的访问控制