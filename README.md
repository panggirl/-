# Kotlin 的使用记录
* set.javaClass 等同于Java的getClass
* @ JvmOverloads 这个指示编译器生成 Java 重载函数，从最后一个开始省略每个参数。(具体见 [Kotlin实战] 的第三章 3.2 让函数更好调用-重载函数默认值)
* 修改文件类各，要改变包含 Kotlin 顶层函数的生成的类的名称，需要为这个文件添加 @JvmName("newName") 的注解，将其放到这个文件的开头，位于包名的前面

