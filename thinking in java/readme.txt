⑤：在某些编程环境里，程序会在屏幕上一切而过，甚至没机会看到结果。可将下面这段代码置于main()的
末尾，用它暂停输出：
try {
Thread.currentThread().sleep(5 * 1000);
} catch(InterruptedException e) {}
}
它的作用是暂停输出5 秒钟。