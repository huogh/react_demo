# 要点
打造好的产品，以产品驱动研发。
App、Web驱动api。
App、Web要对用户体验要精雕细琢。每一个功能，都要充分讨论、思考。要站在用户的角度，去考量每一个功能是否确实有必要？要以什么样的体验来表达这个功能。

后台api，要确保稳定、高效。

# 代码规范和代码review

iOS、Android、api、web前端、nodejs都要制定各自的代码规范。不能再随随便便了。

该有的注释要加上。

模块化、分层。不同逻辑的代码，要写到各自应该写的地方。

思考如何做code review。

# 版本

产品版本

app版本

网站版本

api版本

# 文档

app、web驱动api。在开会讨论达成一致的前提下，先出文档，然后在写api代码。

# 管理

实践敏捷管理Scrum

每一周或两周一次迭代。



# Scrum

## 产品backlog

> 产品backlog是Scrum的核心，也是一切的起源。从根本上说，它就是一个需求、或故事、或特性等组成的列表，按照重要性的级别进行了排序。
>
> 它里面包含的是客户想要的东西，并用客户的术语加以描述。
>
> 我们叫它**故事(story)**,或**backlog条目**。
>
> 放到共享目录里，Excel文档。
>
> 只描述业务目标，不要涉及技术细节

* ID(统一标识符)，一个自增的数字
* Name(名称)，简短的、描述性的故事名。
* Improtance（重要性），产品负责人评出的一个数值，指示这个故事有多重要。
* Initial estimate（初始估算），团队的初步估算，表示与其他故事相比，完成该故事所需的工作量。最小的单位是故事点（story point），一般大致相当于一个“理想的人天”。
* How to demo（如何做演示），它大略描述了这个故事应该如何在sprint演示上进行示范，本质就是一个简单的测试规范。
* Notes（注解），相关信息、解释说明和对其它资料的引用等等。


* Track（类别）：故事的大致分类

## 制定sprint计划

> Sprint计划会议非常关键，应该是Scrum中最重要的活动。
>
> 举办Sprint计划会议，是为了让团队获得足够的信息，能够在未来几个星期内不受干扰地工作，也是为了让产品负责人能够对此有充分的信心。

### 1 在spint计划会议之前，要确保产品backlog的井然有序。

* 产品backlog必须存在
* 对一个产品而言只能有一个产品backlog和一个产品负责人
* 所有重要的backlog条目都已经根据重要性被评过分
* 产品负责人应当**理解**每个故事的含义，他不需要知道每个故事具体是如何实现的，但是他要知道为什么这个故事会在这里。

### 2 怎样制定sprint计划

#### 2.1 为什么产品负责人必须参加

每个故事都有三个变量，它们两两之间都对彼此有着强烈依赖。

范围（scope）和重要性（importance）由产品负责人设置。

估算（estimate）有团队设置。

在sprint计划会议上，经过团队和产品负责人面对面的对话，这三个变量会逐步得到调整优化。

#### 2.2 为什么不能在质量上让步

质量分为：外部质量和内部质量。

外部质量：是系统用户可以感知的。

内部质量：一般是指用户看不到的要素，它们对系统的可维护性有深远影响。包括系统设计的一致性、测试覆盖率、代码可读性和重构等。

外部质量可以看作是范围的一部分。可以版本逐步优化。

内部质量不能打折扣。

#### 2.3 确定sprint长度

#### 2.4 确定sprint目标

#### 2.5 决定sprint要包含的故事

* 产品负责人怎么影响他们的决定
  * 重新设置优先级
  * 更改范围
  * 拆分故事
* 团队怎么决定把哪些故事放到sprint里面
  - 用本能反应来估算
  - 使用生产率计算来估算

工具

* 使用索引卡：将每一个故事写到纸质的索引卡上。在桌子上以重要性排开。
* 使用便利贴，对每一个故事进行任务拆分
* 用计划纸牌做时间估算

#### 2.6 定义“完成”

产品负责人和团队需要对“完成”有一致的定义。

#### 2.7 定下每日例会的时间和地点

## 怎样编写Sprint backlog

> 它应该在sprint计划会议之后，第一次每日例会之前完成。

## 2.8 怎样进行每日例会

确定是时间：9:45 - 10:00

每个人都要参与进来。

每个人讲自己昨天完成了什么任务、今天计划完成什么任务。相应的移动自己的任务便利贴，修改燃尽图。



## 2.9 怎样进行sprint演示

#### 为什么坚持所有的sprint都结束与演示

#### sprint演示检查列表

#### 处理“无法演示”的工作

## 2.10 怎样做sprint回顾

* Good：如果我们可以重做同一个sprint，哪些做饭可以保持
* Could have done better：如果我们可以重做同一个sprint，哪些做法需要改变
* Improvements：有关将来如何改进的具体想法

## 2.11 Sprints之间的休整时刻













