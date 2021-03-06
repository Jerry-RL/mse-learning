# 需求基础

## 需求工程 
* 概念：
  * 所有需求处理活动的总和。它手机信息、分析问题、整合观点、记录需求并验证其正确性，最终描述出软件被应用后与其环境互动形成的期望效应。
  
* 三个主要任务：
  * 需求工程必须说明软件系统将被应用环境极其目标，说明用来达成这些目标的软件功能，也即要同时说明软件需要“做什么”和“为什么”需要做。
  * 需求工程必须将目标和功能反映到软件系统当中，映射为**可行的软件行为**，并对软件行为进行准确的**规格说明**。
  * 现实世界是不断变化的世界，因此需求工程还需要妥善处理目标和功能随着时间演化的变动情况。
  
#### 需求工程的活动

```
|-需求工程
|---|-需求开发
|-------|-需求获取
|-------|-需求分析
|-------|-需求规格说明
|-------|-需求验证
|---|-需求管理
```
#### 需求开发过程模型

```
    -----------------------------------------
   ⬇️          ⬇️            ⬇️            ⬇️
需求获取----->需求分析----->需求规格说明----->需求验证
   ⬆️                        |              ⬆️
利益相关人问题域                |---->需求规格文档说明---一致的需求->
```

### 需求开发


#### 需求获取
+ 从人、文档或环境当中获取需求的过程
+ 要利用各种方法和技术来“发现”需求
+ 目标分析
  + （1）根据问题确定目标
  + （2）通过分析利害人确定目标

##### 需求获取的常见困难
* 用户和开发人员的背景不同，立场不同
* 普通用户缺乏概括性、综合性的表述能力
* 用户存在认知困难
* 用户越俎代庖
* 缺乏用户参与

##### 用户需求获取的方法
* 面谈
* 集体获取方法
* 头脑风暴
* 原型

##### 重新认识需求获取


#### 需求分析
* 通过建模来整合各种信息，以使得人们更好的理解问题
* 为问题定义出一个需求集合，这个集合能够为问题界定一个有效的解决方案
* 检查需求当中存在的作物、遗漏、不一致等各种缺陷，并加以修正
  
----
一、 边界分析
    * 定义项目的范围
    * 系统边界的定义保证系统能够和周围环境形成有效的互动
    * 系统用例图通常被用老定义系统的边界
二、需求建模
    * 建模是为展现和解释信息而进行的抽象描述活动
    * 常用的技术包括类图、顺序图、状态图等建模技术


#### 需求规格说明

* 在系统用户之间交流需求信息
* 要简洁、精确、一致和易于理解
  * 一、定制文档模板
  * 二、编写文档

#### 需求验证

* 需求规格说明文档至少要满足以下杰哥标准：
  * 文档内每条足球都正确、准确的反映了用户的意图
  * 文档记录的需求集在整体上具有完整性和一致性
  * 文档的组织方式和需求的书写方式具有可读性和可修改性
  
##### 验证的方法
* 同级评审
* 原型
* 模拟

### 需求管理

+ 保证需求作用的持续、稳定和有效发挥
  + 在需求开发活动之后，设计、测试、实现等后续的软件系统开发活动都需要以围绕需求开展工作
+ 进行变更控制
  + 纳入和实现合理的变更请求，拒绝不合理的变更请求，控制变更的成本和影响范围

### 实践项目-高校选课系统


## 需求基础

  

### 什么是需求
* IEEE对需求的定义为：
  * （1）用户未来解决问题或达到某些目标所需的条件或能力
  * （2）系统或系统部件为了满足合同、标准、规范或其它正式文档所规定的要求而需要具备条件或能力
  * （3）对（1）或（2）中的一个条件或一种能力的一种文档化表述
  
#### 需求的表述
* 作为一种期望，需求通常被表述为“系统”、“在。。。时”，例如：RI
* RI: 系统应该允许顾客退回已经购买的产品

### 需求的层次
* 目标 - 业务需求 <-> 解决方案与系统特性
* 任务 - 用户需求 <-> 问题域知识
* 系统行为 - 系统级需求 <-> 需求分析模型

#### 业务需求
* 系统建立的战略出发点，表现为高层次的目标（objective），它描述了组织为什么要开发系统
* 为了满足用户的业务需求，需求工程师需要描述系统高层次的 解决 方案，定义系统应该具备的特性（feature）
* 参与各方必须要对高层次的解决方案达成一致，以建立一个沟通的前景（vision）
* 特性说明了系统为用户提供的各项功能，它限定了系统的范围（scope）
-案例

#### 用户需求
* 执行实际工作的用户对系统所能完成的具体任务的期望，描述了系统能够帮助用户做些什么
  * 直接用户
  * 间接用户
* 对所有的用户需求，都应该有充分的问题域知识作为背景支持
* 特性
  * 模糊、不清晰
  * 多特性混杂
  * 多逻辑混杂

##### 补充问题域知识

#### 系统需求

* 用户对系统行为的期望，每个系统需求都反映来一次外界 与系统的交互行为，活着系统的一个实现细节
* 描述开发人员需要实现什么
* 将用户需求转化为系统需求的过程是一个复杂的过程
  * 首先需要分析问题领域及其特性，从中发现问题域和计算机系统的共享知识，建立系统的知识模型
  * 然后将用户需求部署到系统模型当中，即定义系列的系统行为，让他们联合起来实现用户需求，每一个系统行为即为一个系统需求
  * 该过程就是需求过程当中最为重要的需求分析活动，又称建模与分析活动



### 问题域、需求、规格说明

#### 需求
* 是一种期望
* 源自现实又高于现实
* 需求是多变和可调整 的，项目可以依据实际情况调整需求的实现进度

#### 问题域
* 现实世界运行规律的一种反映
* 需求的产生地，也是需求的解决地
* 最终的软件产品要在现实中部署，它能够部分影响问题域，但不能任意改变现实
  * 软件开发必须尊重问题域，不能因为技术原因妄自修改现实世界的实际情况

#### 规格说明
* 软件产品的方案描述，它以软件产品的运行机制为主要内容
* 他不是需求但实现需求，不是问题域但与问题域互动
* 规格说明要以关注对外交互的方式描述软件解决方案，它既需要从软件产品的角度而不是用户的角度进行描述，又不能太多地设计软件产品的内部构造机制

## 需求分类


### 需求谱系
```
|-需求
|--|-项目需求
|--|-过程需求
|--|-系统需求
|--|----|-软件需求
|--|----|-硬件需求
|--|----|-其它需求
|-不切实际的期望
```
### 需求的分类IEEE
* 功能需求
* 性能需求
* 质量属性
* 对外接口
* 约束
  
### 功能需求

* 最常见、最主要和最重要的需求
* 能够为用户带来业务价值的系统行为
* 最需要按照三个抽象层次进行开展
* 软件产品产生价值的基础

### 性能需求
* 需要 进行专门模拟和测试
  * 速度（speed），系统完成任务的时间，例如PR1
    * PR1：
  * 容量 (Capacity)，系统所能存储的数据量
    * PR2: 
  * 吞吐量（throughput），系统连续的时间内完成的食物数量
    * PR3:
  * 负载（Load），系统可以承载的 并发工作量
    * PR4:
  * 实时性（time-crical），严格的实时要求
    * PR5:

### 质量需求
### 对外接口
* 解系统和其它系统的软硬件接口
  * 接口的用途
  * 接口的输入输出
  * 数据格式
  * 命令格式
  * 异常处理要求
* 用户界面
  
### 约束
* 总体上限制了开发人员设计和构建系统时的选择范围
  * 系统开发即运行的环境
    * 包括目标机器、操作系统、网络环境、编程语言、数据库管理系统等
    * CI：
  * 问题域内的相关标准
    * 包括法律法规、行业规定、企业规律等
  * 商业规则
    * 用户在任务执行中一些潜在规则也会限制人员设计和构建系统的选择范围

### 数据需求
* 功能需求的补充
* 数据需求是需要在数据库、文件或其它介质中存储的数据描述，通常包括下列内容：
    * 各个功能使用的数据信息
    * 使用频率
    * 可访问性要求
    * 数据实体及其关系 
    * 完整性约束
    * 数据保持要求