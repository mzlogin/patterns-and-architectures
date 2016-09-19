# 模式与架构

生活里充满套路，代码里也一样，代码里的套路就是「模式与架构」。

小到各种设计模式，大到一个个庞大复杂系统的总体架构，无不是代码世界里的先贤大哲们在踏过无数的坑之后留下的套路。

## 设计模式

## 架构

### 原则、特性与结构

| 原则或特性 | 架构能够做什么                                                 |
|------------|----------------------------------------------------------------|
| 功能多样性 | 提供「足够好」的机制，利用简洁的表达来处理各种问题             |
| 概念完整性 | 提供单一的、最优的、无冗余的方式来表达一组类似问题的解决方案   |
| 修改独立性 | 保持它的元素的独立性，这样就能够让需要的修改最少，从而适应变化 |
| 自动传播   | 通过在模块之间传播数据或行为，保持一致性和正确性               |
| 可构建性   | 指导软件进行一致、正确的构建                                   |
| 增长适应性 | 考虑到可能的增长                                               |
| 熵增抵抗力 | 通过适应、限制和隔离变化的影响来保持有序                       |

*（表格来源：《架构之美》前言，表P-1：架构原则与特性）*

| 结构     | 结构能够做什么                                   |
|----------|--------------------------------------------------|
| 模块     | 将设计或实现决定隐藏在一个稳定的接口之后         |
| 依赖关系 | 按照一个模块使用另一个模块的功能的方式来组织模块 |
| 进程     | 封装并隔离一个模块的运行时状态                   |
| 数据访问 | 隔离数据，设置数据访问权限                       |

*（表格来源：《架构之美》前言，表P-2：架构结构）*

### 架构模式
