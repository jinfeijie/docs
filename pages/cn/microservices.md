---
title: 微服务
keywords: intro, microservices
tags: [intro, microservices]
sidebar: home_sidebar_cn
lang: cn
permalink: /cn/microservices.html
summary:
---

我们可以聊聊，软件开发的未来趋势。

时代瞬息万变，在一个商业业务核心中，我们正走向一个由技术来驱动的世界，而保持竞争的优势变得越来越困难。使用效率低的平台、流程、结构进行扩展，可能会使得组织的执行力大打折扣。过去十年的技术公司已经过些扩展的痛点，而且他们中的大多数都使用都相关的方式来迎接挑战。

现在是时候把这些成功的大公司竞争优势传播给其它人了，基于此，我们就引出来微服务，它是一条创建竞争力的路子。

### 什么是微服务

微服务是一种软件架构模式，用来把大而重的应用程序切成许多可管理的、可管理的独立服务，各服务之间的通信并不受不同语言的协议影响，每个服务只管做好一件事情。

下面是行业内的大佬对微服务的定义：

> 具有有限内容，松耦合的面向服务的体系结构（Loosely coupled service oriented architecture with a bounded context）<br/>
> <sub>[Adrian Cockcroft](https://www.linkedin.com/in/adriancockcroft)，亚马逊副总裁</sub>

<p/>

> 将单个应用作为一小组小服务进行开发的方法，每个服务只在自己的进程中运行，彼此之间通信机制也应该是轻量的。（An approach to developing a single application as a suite of small services, 
each running in its own process and communicating with lightweight mechanisms）<br/>
> <sub>[Martin Fowler](https://martinfowler.com/aboutMe.html)</sub>

其实微服务的概念并不是很新，它只是面向架构的重新设计，差不多像Unix进程与管道一样的。

微服务设计的理念：

- 各服务要小 - 单一的业务目标应该是要细粒度，就像Unix的"只做一件事并且要做好"理念。
- 组织文化要包含部署与测试的自动化，这个降低管理与操作的负担。
- 设计原则要包含失败与错误，就像抗脆弱的系统。

### 为什么要微服务

随着组织的扩大，使用的技术和员工的数量都在增加，管理单一代码实现的服务，只会变得越来越复杂。

Twitter过去有[失败鲸](https://www.theatlantic.com/technology/archive/2015/01/the-story-behind-twitters-fail-whale/384313/)的典故，
在国内我们可能没有这个概念，它其实是用户在加载Twitter时，如果负载发生异常，用户就会看到这只鲸，所以大家就称它为**失败鲸**。

当Twitter曾经有段时间是把用户与其他产品放在了一个大系统中，经常导致系统过载。而微服务使得Twitter把服务切成小块的服务，他们就能通过不同的团队来独立管理。
每一个团队负责众多微服务中的一个业务功能，这些功能可以独立于其它团队发布。

<div class="text-center">
    <img src="../images/micro-service-architecture.png" style="width: 100%; height: auto;" />
</div>

我们通过第一手的经验了解到微服务可以加快开发周期，改进生产力，它是天生的弹性系统。

下面是一些优势：

1. **调性开发更简单** - 团队各自围绕不同的业务需求，自己管理他们的服务。

2. **更易于理解** - 微服务通常要更小些，通常只有1000行代码（国外的项目真有那么小么），或更少。

3. **更适合频繁更新发布的系统** - 服务可以独立部署、扩展和管理。

4. **增强的容错与隔离** - separation of concerns minimises the impact of issues in one service from another.

5. **执行力更强** - 通过独立的开发、发布、管理微服务，团队可以更快交付业务需求。

6. **可复用的服务与快速原型** - 微服务中由生而来的Unix设计理念，可以允许大家复用现有服务和更快地在它这上构建全新的功能。

### 那什么是Micro?

Micro是一个微服务的生态系统，她专注于提供产品、服务、解决方案帮助现代软件驱动的企业革新。我们旨在能提供微服务方面有用的资源，让这门技术可以帮助企业实现他们的业务，从早期的原型转到大规模生产。

这个行业正发生根本性的改变，摩尔定律仍在发生影响，我们的计算机资源越来越强大。然而，我们仍没有完全释放这些能力。现存的工具与开发方式没能在新时代中游刃有余。开发者很难找到把大集成的软件代码转到新的高效的设计模式上。大多数公司都不可避免地摸到了大集成应用的天花板，他们需要进行大量的重构工作。像Netflix、Twitter、Gilt、Hailo，他们都建立了自己的微服务系统平台。

而我们的愿景是能提供一个让任何人都能使用的微服务基建模块。
