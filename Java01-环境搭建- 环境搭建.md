# Java01-环境搭建- 环境搭建

## Task1.安装JDK

#### 1.什么是JDK，什么又是JRE，JVM？他们之间是什么关系？

* **JVM**（Java Virtual Machine是Java虚拟机，负责执行Java程序的字节码。它是一个抽象的计算机，允许Java程序在不同的平台上运行。

* **JRE**（Java Runtime Environment）是Java运行环境，提供Java语言的标准类和API，如集合框架、输入输出、网络等。它允许用户在不安装开发工具的情况下运行Java程序。

* **JDK**（Java Development Kit）是Java开发工具包，包含JRE和各种开发工具，如Java编译器（javac）、Java文档生成器（javadoc）、调试工具等。JDK是开发者编写、编译和调试Java应用的环境，提供了开发Java程序所需的一切工具。

* JDK包含JRE，JRE包含JVM。

#### 1.为什么有了它们就能运行JAVA代码？

- Java程序首先由Java编译器（javac）编译成字节码（.class文件），该字节码与平台无关，可以在任何安装了JRE的机器上运行。JRE中的JVM会将字节码转换为特定平台的机器代码并执行，从而实现了Java的跨平台特性。

## **Task2.配置环境变量**

#### 2.你配置了什么环境变量？为什么配置了环境变量后，就能在命令行使用相关命令了？

* JAVA_HOME和PATH

  - JAVA_HOME指向JDK的安装目录，一些工具和应用程序使用这个变量来查找JDK的位置。

  - PATH包含可执行文件的路径。将JDK的bin目录添加到PATH中，可以在命令行中直接使用javac、java等命令，而无需指定完整路径。

* 配置环境变量后，操作系统会在执行命令时查找PATH中指定的目录，如果找到相应的可执行文件，就可以运行这些命令。

## **Task3.编译和运行**

#### 3.截图

![](C:\Users\30522\Pictures\Screenshots\屏幕截图 2024-10-20 142407.png)

#### 4.在编译和运行过程中涉及的文件和这些文件的作用

* **源文件（.java）**：包含Java源代码，使用文本编辑器编写。

- **字节码文件（.class）**：由Java编译器（javac）将源文件编译生成，包含平台无关的字节码，JVM可执行。
- **JDK**
- **JRE**
- **JAR文件（.jar）**：将多个字节码文件和资源打包成一个文件，方便分发和部署。

* **配置文件**（如.properties）：存储应用程序的配置信息，供程序在运行时读取。

## **Task4.IDE的安装和使用**

![](C:\Users\30522\Pictures\Screenshots\屏幕截图 2024-10-20 164239.png)