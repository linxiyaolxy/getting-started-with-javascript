### 编程中为什么会有丰富化的数据格式？
在现实生活中，为了有效的交流我们要给事物一个名字，这样才能通过简洁的语言指向我们要表达的事物。这一点在程序中也是一样的，文件名、变量名、函数名、参数名。如果不使用名字，我们就很难快速的指向一个事物，进而每次要对这个事物进行呼唤、传播、操作的时候都会麻烦很多。而且，即便是没有给一个事物起名字，那些用来描述的它属性本身也是名字，如果一个名字都不使用我们就无法表达，更无法沟通了。

人的名字就是一个例子，比起说黑头发、180高、小眼睛、大鼻子来表述一个人，我们使用名字会更有效率。这样在沟通的过程中也会更有针对性，在计算机的世界里，命名更加有意义，因为比起使用内存地址，代码位置，机器语言通过名称调用更加快捷高效，而且在一个名称里面集成其他名称的函数、变量、方法越多，它越高效。

然而，名字虽然指向事物，但它并不等于事物。就拿人来说，人是一个非常具体的事物，如前面所说可能有黑头发、180高、小眼睛、大鼻子等等特性，这都是“人”这个事物实实在在的特质，是它们才将“人”同其他事物、其他人区分开来。而名字，仅仅是一个代号。它代表这个个体，但是并不等价于它。这在程序里也是一样的，一个变量名、函数名，它们只是指向了一个值、一段代码，具体的值和代码才是我们真正需要的东西。

所以，名字一定要和具体目标的特性相挂钩，这样才能明确指代关系。如人名，那么就要和这个人的长相、身高、国籍等等特性匹配起来，匹配的属性越多，他们的关联性也就越强。需要注意的是，一个人可以有几个名字，但是在实际使用名字的时候，一个名字只能是指定具体的一个人。在程序里，这个道理是一样的。一个值或者功能代码可以被不同的变量名或者函数名指向。但变量名、函数名在使用时只能指向一个具体的值或者功能代码。这样才能保证我们正确的使用函数和功能代码。

具体事物的特质，有他们自身的属性和他们与其他事物的关系。他们和事物的名称一起组成了关于该客观事物的完整数据。有了这些数据，我们才可以准确的指代和描述一个客观事物。在具体描述这些数据的时候我们可以有多种方式，语音的、文字描述的、图形图画还有通过编程语言来描述，不同的编程语言之间会有一些语句、语法、命名、定义规则等方面的不同，但所有的编程语言又都有一些相同的描述规则。

数据存储在计算机里面有两个特点，一个是要被使用，另一个是要占存储空间。针对这两点，自然而然就需要对不同的数据采用不同的存储方式。具体的就是为不同的数据使用不同的数据格式和对应的存储空间。使用不同的数据格式，就可以为不同类型的数据使用专门的数据处理方法，比如数值类型的数学运算、字符串类型的符号处理等等。同时，由于为不同的数据类型使用不同的数据格式，可以在很大程度上避免内存空间的浪费或者存储数据的丢失，这不但能节省本地的计算机资源，还能更有效的利用网络传输的带宽。 在js里常用的数据格式有数值、文本、字符串、数组、布尔、对象这些，其中除了数组根据数据个数相应变化空间占用的大小还有对象根据组成数据的个数和类型变化空间占用大小外，其他类型的数据占用的空间大小是固定。

为了做到这些，大部分的编程语言有一些相同的步骤。一般有三个步骤。第一个步骤，声明变量。这是给变量起名的过程，相当于告诉程序我准备要使用一个新的变量来存储数据，给这个变量起名XXX。第二步就是定义变量，这相当于告诉程序这个数据是什么类型，用什么数据格式，给他安排相对应的存储空间。第三步，则是为变量赋值，就是将具体的数据存到这个变量所指定的存储空间里。

这些步骤是在具体使用代码时完成的，对js来说，就是在node.js或者浏览器环境下执行代码完成的。在node.js环境下我们可以直接在终端里看到代码，但是在浏览器下我们只能去console后台看，这是他们不一样的地方。其他的执行代码的部分这是一样的，一样的数据类型和格式、一样的空间分配规则、一样的命名方式。

#### 静态网页地址

https://freedomsky11.github.io/library/