⑤：在某些编程环境里，程序会在屏幕上一切而过，甚至没机会看到结果。可将下面这段代码置于main()的
末尾，用它暂停输出：
try {
Thread.currentThread().sleep(5 * 1000);
} catch(InterruptedException e) {}
}
它的作用是暂停输出5 秒钟。

注释用法

下面这个简单的例子所示：
/** 一个类注释 */
public class docTest {
/** 一个变量注释 */
public int i;
/** 一个方法注释 */
public void f() {}
}
注意javadoc 只能为public（公共）和protected（受保护）成员处理注释文档。“private”（私有）和
“友好”（详见5 章）成员的注释会被忽略，