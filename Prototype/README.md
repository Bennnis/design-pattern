### 原型模式
* 解决问题：“某些结构复杂的对象”的创建工作；由于需求的变化，这些对象经常面临着剧烈的变化，但是他们却拥有比较稳定一致的接口。
* 优点：简化对象的创建过程，拓展性强，方便快捷的为所有子类添加了统一的公用方法，减少内存消耗，公用一个prototype
* 缺点：上面的任意方法和属性都影响着所有的子类，若原型上有一个array，一个子对象改变了这个array，那其他子对象访问到的这个array都被改变了。
* **应用场景：**
* 复杂的对象创建，但是差异性很小，大多数属性都想同的情况，可通过克隆prototype来进行创建，更加方便和快捷