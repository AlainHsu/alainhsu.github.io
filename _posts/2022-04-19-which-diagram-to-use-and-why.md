---
layout: article
title: UML - 如何选用 UML 图?【译】
key: which-diagram-to-use-and-why
author: Alain Hsu
show_author_profile: true
sharing: true
tags: ["UML"]
---

最近在写文档，需要用到比较复杂的 UML 图，翻译一篇 [draw.io](https://app.diagrams.net/) 官网上的博客复习一下。<!--more-->

> 原文: [https://drawio-app.com/uml-diagrams/](https://drawio-app.com/uml-diagrams/)

<div style="margin: 0 auto;" align="justify" markdown="1">

## 前言

统一建模语言（UML）是一种为系统和软件进行说明和可视化的一种图表符号（语言）。它在软件开发中是最流行的图表形式之一，并于 1997 年被采纳成为了 ISO 规范。之后又更新了一些额外的 UML 图类用以支持新的编程技术。

[图表通常比文字更快也更便于理解](https://drawio-app.com/why-are-diagrams-so-powerful/)，相比于成百上万行的代码中的注释，它们更适用于对系统进行文档说明，虽然注释也同样重要！图表可以在许多情况下为你和你的公司发挥作用，比如...

- [接纳新同事或者团队成员](https://drawio-app.com/better-onboarding-with-diagrams/)
- 调试问题
- 为新的开发或者流程做计划
- 优化现有的系统和程序
- 审计流程和申请认证评估

另外，当你想开发新的功能的时候 - 你还能通过 UML 图表提前发现许多可能潜在的阻碍开发或者测试的问题。

UML 图分两种主要类别和 14 种不同的类型，每种类型都适用于不同的情况。

- **结构图** （Structure diagrams）：表示系统中各部件之间的静态关系
- **关系图** （Behavior diagrams）：表示系统中各部件如何相互影响，系统如何变化，如何随时间变化

## UML 图的分类

<div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/10/UMLdiagrams.png" alt="topo" width="800px" class="shadow rounded">
</div>

<center>
<a href="https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=UMLdiagrams.html#Uhttps%3A%2F%2Fdrive.google.com%2Fa%2Fseibert-media.net%2Fuc%3Fid%3D1bdRCmgdZbsgC6oe95k810S85eJmIUr9a%26export%3Ddownload">在 draw.io 中打开</a>
</center>

## 常用的 UML 图

有一些 UML 图在软件开发和系统建模（包括 IT 基础设施和商业系统）中应用很广泛。前三种你最需要了解的 UML 图是例图，类图（如何你是程序员的话）以及时序图。

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
.column {
  float: left;
  width: 33.33%;
  padding: 12px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>
<div class="row">
  <div class="column">
    <h3>例图</h3>
    <p>例图（Use case diagrams）用于查看系统或程序的需求。</p>
    <p>它用来表示函数，功能或交互者以及它们之间的关系。</p>
    <center><a href="https://drawio-app.com/uml-use-case-diagrams-with-draw-io/">draw.io 中的例图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/10/UseCase-HabitTrackingApp.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
  <div class="column">
    <h3>类图</h3>
    <p>面向对象编程语言基于类和它们之间的关系。类图（Class diagrams）则用于可视化的表示这些关系。</p>
    <p>类包含属性（类的数据）和行为（成员函数），它们之间的关系用连接线表示。</p>
    <center><a href="https://drawio-app.com/uml-class-diagrams-in-draw-io/">draw.io 中的类图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/01/Class-Diagram-Habit-Tracker-app.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
    <div class="column">
    <h3>时序图</h3>
    <p>时序图（Sequence diagrams）用于可视化程序，逻辑处理和 IT 基础设施中的交互动作。它描述了交互者和实体（例如数据库或其他外部接口）之间按时间或次序发生的交互动作（消息）。</p>
    <center><a href="https://drawio-app.com/create-uml-sequence-diagrams-in-draw-io/">draw.io 中的时序图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/01/drawioUMLsequenceDiagram-checkin.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
</div>
<div class="row">
  <div class="column">
    <h3>活动图</h3>
    <p>活动图（Activity diagrams）对用户和系统在遵循流程时的行为进行建模。活动图类似流程图或者工作流图，在形状上有一些小的区别。</p>
    <center><a href="https://drawio-app.com/create-uml-activity-diagrams-in-draw-io/">draw.io 中的活动图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/01/ActivityDiagram-HabitTrackerApp.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
  <div class="column">
    <h3>状态图</h3>
    <p>状态图（State diagrams）在编程中用来描述系统可能处于的各种不同状态。它不局限于编程中 - 因为所有系统和流程都会有状态需要被描述。状态图比起活动图或者时序图来说更简单快捷，但是可表达的信息相对较少。</p>
    <p>状态图表示从状态之间的切换，以及什么触发了状态改变。</p>
    <center><a href="https://drawio-app.com/uml-state-diagrams-with-draw-io/">draw.io 中的状态图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/09/UML-state-diagram-Habit-Tracker-example.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
    <div class="column">
    <h3>交互概述图</h3>
    <p>交互概述图（Interaction overview diagrams）合并了活动图和时序图，每个活动都被单独划分开来，所以更便于编程。</p>
    <center><a href="https://drawio-app.com/uml-state-diagrams-with-draw-io/">draw.io 中的交互概述图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2018/04/Interaction-Overview-Habit-Tracker.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
</div>
<div class="row">
  <div class="column">
    <h3>通信图</h3>
    <p>通信图（Communication diagrams）又称协作图。和例图类似，详细描述信息如何被传递。不过通常时序图会更常用，因为时序图的可视化更清晰也有拥有更丰富的符号注释。</p>
    <center><a href="https://drawio-app.com/uml-communication-diagrams/">draw.io 中的通信图</a></center>
    <div align="center">
<img src="https://drawio-app.com/wp-content/uploads/2019/09/UML-communication-habitCheckin.png" alt="topo" width="800px" class="shadow rounded">
    </div>
  </div>
 </div> 
</body>
</html>

## 其他用于更大，更复杂或者特殊系统的 UML 图

下面 8 种UML 图用于特定环境，通常是拥有许多控件的庞大的系统。

<h3>时间图</h3>

时间图（Timing diagrams）一种特殊类型的时序图，它遵循对象随时间推移的行为。常用在嵌入式系统设计中，例如洗衣机的编程控制软件。

<h3>对象关系图</h3>

对象关系图（Object diagrams）是类图的一种特殊形式。它们将更抽象的类图可视化，就好像它们已经实例化一样，并帮助软件开发人员检查它们的抽象结构在实践中是否有效。

<h3>组件图</h3>

组件图（Component diagrams）用于描述多个组件在复杂的系统中关系以及它们之间如何通过接口通信。简单或者直观的系统通常不需要用到组件图。

<h3>部署图</h3>

部署图（Deployment diagrams）是另一种为大型复杂系统设计的特殊图表，其中软件部署在多个系统只上。如今，像 [Amazon Web Services（AWS）](https://drawio-app.com/document-your-aws-architecture-with-cloudcraft-and-draw-io/) 和 [Google Cloud Platform（GCP）](https://drawio-app.com/updated-google-cloud-platform-icons-and-templates/) 这样的网络服务都有自己的符号 - 可以在它们的 draw.io 符号库中找到这些符号。

<h3>包图</h3>

包图（Package diagrams）用于描述系统的依赖关系，并且主要在具有大型代码库时使用。包图可以包含例图用来描述系统的功能，并且能够可视化软件系统中的层级结构。

<h3>综合架构图</h3>

当你的复杂软件系统拥有许多的用户用例时，综合架构图（Composite structure diagrams）能够可视化程序运行时的情况。它描述了类的内部结构以及和其他类部件的关系。

<h3>配置文件图</h3>

使用配置文件图（Profile diagrams），您可以扩展和自定义 UML，以便在具有构造型、标记值和约束的特定域（例如，航空航天、医疗保健、金融）或平台（J2EE、.NET）中使用。同样，这种类型的图表通常用于对极其庞大和复杂的系统进行建模。