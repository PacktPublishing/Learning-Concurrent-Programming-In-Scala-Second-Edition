#Learning Concurrent Programming in Scala - Second Edition
This is the code repository for [Learning Concurrent Programming in Scala - Second Edition](https://www.packtpub.com/application-development/learning-concurrent-programming-scala-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786466891), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
The Scala 2.12 series targets Java 8 and requires it for execution. It starts by introducing you to the foundations of concurrent programming on the JVM, outlining the basics of the Java Memory Model, and then shows some of the classic building blocks of concurrency, such as the atomic variables, thread pools, and concurrent data structures, along with the caveats of traditional concurrency.

##Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code files are arranged in the file structure as: 

Chapter02/learning-examples-master.zip\learning-examples-master\src\main\scala\org\learningconcurrency

Chapters 1 and 10 do not have any code

The code will look like the following:
```
package org

package object learningconcurrency {
  def log(msg: String): Unit =
  println(s"${Thread.currentThread.getName}: $msg")
}
```

The program that you use to write code is entirely up to you, and you can choose anything, such as Vim, Emacs, Sublime Text, Eclipse, IntelliJ IDEA, Notepad++, or some other text editor.

There is an important caveat when running the examples in this book using an IDE: editors such as Eclipse and IntelliJ IDEA run the program inside a separate JVM process. As mentioned in the previous section, certain concurrent computations continue executing after the main execution stops. To make sure that they always complete, you will sometimes need to add the sleep statements at the end of the main execution, which slow down the main execution. In most of the examples in this book, the sleep statements are already added for you, but in some programs, you might have to add them yourself.

##Related Products
* [Mastering Scala Machine Learning](https://www.packtpub.com/big-data-and-business-intelligence/mastering-scala-machine-learning?utm_source=github&utm_medium=repository&utm_campaign=9781785880889)

* [Scala for Data Science](https://www.packtpub.com/big-data-and-business-intelligence/scala-data-science?utm_source=github&utm_medium=repository&utm_campaign=9781785281372)

* [Learn Scala Programming Language From Scratch [Video]](https://www.packtpub.com/application-development/learn-scala-programming-language-scratch-video?utm_source=github&utm_medium=repository&utm_campaign=9781787126299)

###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
