# 小组合作规范
## 丑话说在前面：请大家千万不要抄袭！包括代码和报告！！
### 还有，请严格遵守代码规范。
### 目录
- [什么是抄袭？](#抄袭)  
- [What is Plagiarism?](#抄袭2)
- [反抄袭声明（非常重要！！！）](#反抄袭2) 
- [Announcement Against Plagiarism （very important！！！）](#反抄袭3) 
- [小组内部反抄袭机制](#反抄袭1)  
- [Python 代码规范](#代码规范)

### 什么是抄袭？ <a name="抄袭"/>

1. 虽然标注了引用，但是直接复制粘贴原文 / 代码。引用 $\neq$ 原文搬运。**严厉禁止任何复制**。所有的文字及代码引用都要标注出处，而且引用只是间接引用，所有的文字及代码具体实现需要自己写。
2. 如果真的需要直接或间接引用代码，请务必写清楚出处。**严厉打击修改变量名 / 数值等自作聪明的把戏**。
3. 把中文等其他语言网络资源原文翻译成英文，然后放到报告上。
4. 复制粘贴往年作业或其他课程作业。
5. 最恶劣的情况：直接从各种来源复制粘贴，不进行任何说明。

### What is Plagiarism? <a name="抄袭2"/>

1. Directly copy from literatures / other people's code even with citation. Citation $\neq$ Copy. **Any form of directly copying is strictly prohibited**. All text and code references must be marked with the source, and the references are only indirect references. All text and code implementations need to be written by yourself.
2. If you really need to quote the code directly or indirectly, please be sure to state the source clearly. **Strictly crack down on clever tricks such as modifying variable names / values**.
3. Translate network resources in Chinese or other language into English. And then put it in the report.
4. Copy from the previous year's course projects or other course's projects.
5. The worst case: Copy and paste directly from various sources without any explanation.

### 反抄袭声明（非常重要！！！） <a name="反抄袭2"/>

本部分内容请每位同学认真阅读。若对本声明有任何疑问，请于确定正式进入小组前在微信群中询问。
本项目小组成员，应严格遵守诚信原则，保证自己上传的任何论文、报告、代码内容不存在抄袭作假现象。在存在组员出现以下违反反作弊声明的情况时，小组其余成员在集体协定后，有权利向课程老师及学校报告该组员的抄袭现象并将其移出小组，以维护自身合法成绩：
1. 任何违反项目目录中“什么是抄袭？”中内容的。
2. 小组内部反抄袭中被发现重复率严重过高、存在明显复制粘贴行为的。
3. 在课程项目提交后，被课程负责人发现存在抄袭行为的。
其余正常完成项目的小组成员，不为存在抄袭的组员付任何责任。
在不知情的情况下，其他小组成员修改存在抄袭行为组员的负责内容，如修正语法等问题、增删内容等，不为该抄袭组员的内容负任何责任。

在本项目中上传任何文件，即表明同意以上申明。请每位同学认真阅读，在对此没有疑问后再确定进入项目小组。

### Announcement Against Plagiarism （very important！！！） <a name="反抄袭3"/>

Please read this announcement carefully. If you have any doubt on this announcement, please ask in the Wechat group before joining this project group formally.
Members of this project group, should strictly follow principle of good faith, which means to guarantee everything uploaded such as paper, report and code do not exist any plagiarism. When one member in the group break the requirement of anncouncement in one of the following situations, the other group members have the right to report the plagiarism behaviour of that member to course teacher and university, and remove that person out of the project group after collective agreement to safeguard their legitimate grades:
1. Any behaviour against "What is plagiarism?" in the project dictory.
2. To be found existing plagiarism behaviours such as extremely high repetitive rate or copying in the group internal plagiarism check.
3. To be found existing plagiarism behaviours by the course teacher after uploading the project.

The other group members who finished their parts normally are not supposed to be responsible for whom plagirise in the project. 

If knowing nothing about one group member's plagrism behaviour, the other group members who help to modify that person's part such as fixing syntax errors, adding or deleting contents should not take any responsibility for the plagrism behaviour of that person.

Uploading any file in this project dictory means you have agreed with this announcement. Please read carefully, only join this project group after you don't have any doubt.


### 小组内部反抄袭机制 <a name="反抄袭1"/>

1. 用查重网站进行检查。
2. Git 的 commit 会精确记录每一处修改的作者及时间，且 commit 历史不可改动。任何有争议的地方都可通过查提交历史精准定位。


### Python 代码规范 <a name="代码规范"/>
1. 所有需要导入的 package 应该在文件的开头声明。
2. 所有需要设置的参数应该在 package 声明之后进行声明。
3. 代码缩进统一为**四个空格**。**不要混用 tab 和空格！**
4. 命名要尽量有明确含义，最好不要直接写 x, y, a, b 之类的变量。
5. 变量和函数的命名法采用 snake_case。 例子：this_is_a_variable / this_is_a_function
6. 类名采用 CapWords convention，例子：MyClass
6. 二元运算符（assignment (=), augmented assignment (+=, -= etc.), comparisons (==, <, >, !=, <>, <=, >=, in, not in, is, is not), Booleans (and, or, not)）**两端要有空格**。但是**不包括**函数的参数列表默认值。
```
# correct
i = i + 1
def some_fun(a=1):
    pass

# wrong
i=i+1
```
6. 定义类和函数时，**请写注释**。 除了少量含义一目了然的函数，如：```__str__``` 的注释可以省略，其他函数请至少写明函数的作用，输入参数的含义。定义类请写明类的作用及初始化参数有哪些。

```
def simple_subtraction(a, b=1):
    """
    A simple function to implement the operation of subtraction.

    Args:
      a: Minuend.\
      b: Subtrahend. Default: 1. 
    """
    operation_result = a - b

    # Return the result
    return operation_result
```
