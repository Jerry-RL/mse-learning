# 需求文档化与验证
## 为什么文档化需求
teamwork and communication

## 用例文档

* 在用户的角度以用例文本为主描述软件系统与外界的交互
* 基本职责是吧问题域信息和需求传达给软件系统解决方案的设计者

## 软件需求规格说明文档
* 在软件产品的角度以系统级需求列表的方式描述如那件系统解决方案

|用例|系统规格 |
|-|-|
|侧重于交互流程|侧重于独立需求|
|以一次交互为基础|以一次交互中的软件系统处理细节为基础|

>  补充：练习、示例

## 文档化需求的注意事项

### 技术文档写作要点
* 简洁
* 精确
* 易读
  * 1、有效使用引言、目录、索引等能够增强文档易读性的方法
  * 2、使用系统化的方式组织内部信息，提供文档内容的可读性
* 易修改

### 系统化的方式
* 使用相同的语句格式来描述相似、关联的信息
* 使用列表或表格来组织独立、并列的信息
* 使用编号来表达繁杂信息之间的关系，包括顺序关系、嵌套关系和层次关系
  * 对图、表进行编号
  * 对文档的张杰进行编号
  * 对信息内容进行标识和编号

### 可修改性

### 需求书写要点
+  需求书写要点
   +  使用用户术语
   +  可验证
   +  可行性
+  需求规格说明文档书写要点
   +  充分利用标准的文档模板，保持所有内容位置得当
   +  保持文档内的需求集具完备性和一致性
   +  为需求划分优先级 


## 验证需求文档

###  验证需求的方法
* 评审 
* 开发系统测试用例
* 度量

### 评审的注意事项
+ 重视需求评审
+ 保证用户与客户参与 
+ 用户对场景与线索表现出了最大的兴趣
+ 使用检查列表

### 开发系统测试用例
+ 1）以需求为线索，开发测试用例套件
+ 2）使用测试技术确定输入/输出数据，开发测试用例 

### 测试用例套件

*  基于用例描述，可以为销售处理确定测试用例套件

### 建立测试用例

* 主要是基于过个的技术，设计测试场景的输入与输出数据

## 度量需求功能点

### 度量需求
+ 用例的数量
  + 平均每个用例中的场景数量
  + 平均用例行数
+ 软件需求数量
+ 非功能需求数量
+ 功能点数量

###  度量的意义

+ 如果平均的用例场景数量过低，那么就可能存在对异常流程考虑步骤的可能
+ 如果平均用例行数过大或者过小，那么可能对用例的细分粒度过大或者过小
+ 用例数量、软件需求数量和功能点数量应该是相对比例均衡的 ，如果三者之间有着非常大的差距 ，那么可能会有需求 的遗漏

### 功能点度量
* 用于估算和度量软件系统规模与复杂度的抽象单位
* 在需求开发阶段，估计代码行数误差较大，使用功能点来估算和度量 软件系统的规模与复杂度则有 较好的效果 

#### 功能点度量
+ 输入数量：一次 有意义的输入，需要程序 进行一次编程处理
+ 输出数量：系统需要对外展示的内容组，表现为屏幕界面、答应输出、错误提示等
+ 查询数量： 用户的“命令”输入，通常表现为鼠标点击和键盘输入
+ 逻辑文件数量： 系统内部的持久化数据，包括文件、数据表等
+ 对外接口数量： 与外部系统交换数据的软硬件通信接口
