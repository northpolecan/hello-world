# 0. Java基础

## 0.1 基本名词和概念

**jre**：Java虚拟机、Java平台核心类和支持文件。不包含开发工具(编译器、调试器等)

**jdk**：Java开发工具包，它提供了Java的开发环境(提供了编译器javac等工具，用于将java文件编译为class文件)和运行环境(提 供了JVM

Runtime辅助包，用于解析class文件使其得到运行)，JDK包含JRE，jdk下bin目录中的一些文件：

- **java**：这个可执行程序其实就是JVM，运行Java程序，就是启动JVM，然后让JVM执行指定的编译后的代码；
- **javac**：这是Java的编译器，它用于把Java源码文件（以`.java`后缀结尾）编译为Java字节码文件（以`.class`后缀结尾）；
- **jar**：用于把一组`.class`文件打包成一个`.jar`文件，便于发布；
- **javadoc**：用于从Java源码中自动提取注释并生成文档；
- **jdb**：Java调试器，用于开发阶段的运行调试。

