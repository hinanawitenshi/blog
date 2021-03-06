---
title: 软件团队管理基础
date: 2018-03-18
tags:
    - 中文
    - software engineering
---

### 1. 简述瀑布模型、增量模型、螺旋模型（含原型方法）的优缺点。

<table>
  <thead>
    <tr>
      <td style="width:10%">-</td>
      <td style="width:30%">瀑布模型</td>
      <td style="width:30%">增量模型</td>
      <td style="width:30%">螺旋模型</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>优点</td>
      <td>
        <ul style="padding:0.5em;">
          <li>降低软件开发的复杂程度，提高软件开发过程的透明性，提高软件开发过程的可管理性；</li>
          <li>推迟软件实现，强调在软件实现之前的分析和设计工作；</li>
          <li>以项目的阶段评审和文档控制为手段有效地对整个开发过程进行指导，保证了阶段之间的正确衔接，能够及时发现并纠正开发过程中存在的缺陷，使产品达到预期的质量要求。</li>
        </ul>
      </td>
      <td>
        <ul style="padding:0.5em;">
          <li>增强客户对系统的信心；</li>
          <li>降低系统失败风险；</li>
          <li>提高系统可靠性；</li>
          <li>提高系统的稳定性和可维护性。</li>
        </ul>
      </td>
      <td>
        引入了明确的风险管理，能够有效控制风险，适合于大型软件开发。
      </td>
    </tr>
    <tr>
      <td>缺点</td>
      <td>
        <ul style="padding:0.5em;">
          <li>强调过程活动的线性顺序；</li>
          <li>缺乏灵活性，特别是无法解决软件需求不明确的问题；</li>
          <li>风险控制能力较弱；</li>
          <li>文档驱动，文档数目过多会极大地增加系统的工作量。</li>
        </ul>
      </td>
      <td>
        <ul style="padding:0.5em;">
          <li>增量力度难以选择；</li>
          <li>确定所有的基本业务服务比较困难。</li>
        </ul>
      </td>
      <td>
        模型系统复杂，加上严密的风险管理成本较高。
      </td>
    </tr>
  </tbody>
</table>

### 2. 简述UP的三大特点，其中哪些内容体现了用户驱动的开发，哪些内容体现风险驱动的开发？

- 迭代和增量(Iterative and incremental)

  精化、构建和产品交付阶段被分成一系列迭代过程，每个迭代过程的结果就是一个在过去结果基础上的增量。

- 以构架为中心(Architecture-centric)

  构架是项目团队工作的中心，UP支持复数个构架模型。

- 风险关注(Risk-focused)

  UP要求项目团队时刻关注在项目生命周期中最主要的风险，在开发过程中时刻关注这些风险的控制。

迭代和增量体现了用户驱动的开发，风险关注体现了风险驱动的开发。

### 3. UP四个阶段的划分准则是什么？关键的里程碑是什么？

UP的软件生命周期被分为四个顺序的阶段：初始阶段(Inception)、精化阶段(Elaboration)、构建阶段(Construction)、产品交付阶段(Transition)；划分准则是不同的阶段性目标和软件生命周期。

- 初始阶段的里程碑使一些重要的文档，包括项目构想、原始用例模型、原始业务风险评估、一个或多个原型、原始业务案例等；
- 精化阶段的里程碑包括风险分析文档、软件体系结构基线、项目计划、可执行的进化原型、初始版本的用户手册等；
- 构建阶段的里程碑包括可以运行的软件产品、完整的用户手册等；
- 交付阶段的里程碑则是确定最终目标是否实现，是否应该开始下一个版本的开发周期等。

### 4. IT项目管理中，“工期、质量、范围/内容”三个元素中，在合同固定的条件下，为什么说”范围/内容”是项目团队易于控制的？

工期、质量可能受到外界不可控因素的影响，例如客户需求变更、软件团队人事变动等，而范围/内容是由项目团队自己制定和掌握，相对而言易于控制。

### 5. 为什么说，UP为企业按固定节奏生产、固定周期发布软件产品提供了依据？

UP通过迭代增量建模思想提高了风险控制能力，既严格按照时间顺序进行开发作业，同时能够管控各种可能的风险，使得开发周期得到非常有效的控制，企业能够在这种模型下精确控制开发周期，实现按固定节奏生产、固定周期发布软件产品。

### 6. 项目管理应用

本团队拟实现一个基于微信小程序的扫码点餐软件，以亲身体验软件工程在实际中的应用。

在整个过程中，使用看板作为团队协作的重要工具，对生产过程进行基于过程开发模型的阶段划分，看板如下所示：

![](/assets/images/kanban.png)
