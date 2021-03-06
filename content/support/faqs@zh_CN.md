---
$title: 常见问题解答
---

[TOC]

## Accelerated Mobile Pages 概览

### 什么是 Accelerated Mobile Pages 项目？

Accelerated Mobile Pages (AMP) 项目是一个开放源代码计划，是发布商和技术公司围绕面向所有各方（发布商、消费者平台、创建者和用户）优化整个移动内容生态系统的迫切需求展开讨论后得出的结果。

目前，我们希望内容能够飞快加载并可轻松浏览。但现实情况是，内容可能需要好几秒才能完成加载，或者加载缓慢的网页因为用户放弃浏览而根本没有完成加载。Accelerated Mobile Pages 是几乎瞬间就能完成加载的网页，让我们离面向所有用户打造更好的移动网页这一目标又近了一步。

### Accelerated Mobile Pages 有哪些优势？

速度至关重要，而瞬间完成加载则是理想状态。研究表明，跳出率与网页加载速度密切相关：网页加载速度越慢，跳出率越高。使用 AMP 格式能够大幅提高内容的吸引力，促使用户浏览更多内容并与之互动。不过，该项目并不只是关注速度和性能。我们还希望推广增强型分发，以便发布商能够充分发挥开放式网络的潜力，使内容能够在各种平台和应用中快速呈现出来，从而通过广告和订阅获得更高收入。

### Accelerated Mobile Pages 的运作方式是怎样的？

除了拥有数量有限的一些获准使用的技术功能（由开放源代码 AMP 规范定义和约束）之外，Accelerated Mobile Pages 与任何其他 HTML 网页并无二致。就像所有网页一样，Accelerated Mobile Pages 能够在所有新型浏览器或应用网络视图中加载。

AMP 文件能够充分利用各种将速度放在首位的技术和架构方式，以便为用户提供更快的加载体验。AMP 开发者可以使用非常丰富而且还在不断发展的网络组件库。借助该组件库，AMP 开发者能够嵌入富媒体对象（例如视频和社交信息）、展示广告或收集分析数据。我们的目标不是使内容具有一致的外观和风格，而是在网页之间打造更为常见的技术核心，以便缩短加载时间。

此外，AMP 文件可以缓存在云端，以便缩短内容呈现到用户的移动设备上所用的时间。通过使用 AMP 格式，内容制作者可将 AMP 文件中的内容设计为可由第三方缓存。在这种框架下，发布商可以继续掌控自己的内容，而平台可以轻松缓存或镜像内容，从而以最快的速度为用户提供内容。Google 提供了可供所有人免费使用的缓存服务，并且所有 AMP 都将由 [Google AMP 缓存服务](https://developers.google.com/amp/cache/)进行缓存。其他公司也可以打造自己的 AMP 缓存服务。

总而言之，我们的目标是将有限的技术功能与围绕缓存构建的分发系统相结合，借此提高网页性能并使发布商能够发展更多受众。

### Accelerated Mobile Pages 项目为何采用开放源代码方式？

参与该项目的公司希望针对各个环节优化移动网页，而不是仅仅针对一个平台、一组技术或一组发布商进行优化。通过使该项目采用开放源代码方式，所有人都可以就如何加快移动网页速度分享和贡献自己的想法和代码。我们才刚刚踏上这一征程，并真诚希望其他发布商和技术公司与我们携手同行。

### 谁可以使用 Accelerated Mobile Pages？

该项目面向生态系统中的所有参与方（发布商、消费者平台和创建者）开放。要了解使用 AMP 的部分公司和网站，请前往[“Who”页面](/who)。

### 使用 Accelerated Mobile Pages 的结果是什么？

通过使用 AMP 格式，内容制作者可将 AMP 文件中的内容设计为可供第三方抓取、编入索引/展示（遵循漫游器排除协议）和缓存。

### 哪种内容最适合使用 Accelerated Mobile Pages？

我们的目标是让网上发布的所有内容（从新闻报道到视频，从博客到照片以及 GIF）都能使用 Accelerated Mobile Pages。

### 作为发布商，对我的内容采用 Accelerated Mobile Pages 会增加工作量吗？

简言之，会增加，但不会增加很多。由于“AMP HTML”完全是在现有网络技术基础上打造出来的，因此开发流程与发布商如今已在使用的流程完全相同。发布商可以通过 GitHub 熟悉 AMP HTML 规范。已经习惯使用当前流程的发布商很快就能掌握相关技巧。

### 发布商如何将内容添加到 AMP HTML 中？

发布商和内容管理系统 (CMS) 提供商可以将 AMP HTML 与其 CMS 相集成，以生成 AMP 内容。Automattic 已经发布了 [WordPress AMP 插件](https://wordpress.org/plugins/amp/)，我们希望所有内容管理系统都能添加对 AMP HTML 网页的支持。

## 平台和技术公司参与

### 消费者平台如何参与 Accelerated Mobile Pages 项目？

该项目面向所有人开放，并且现有成员都非常乐意就该计划与消费者平台合作。Google 已经开放其缓存服务以供所有人免费使用，想要在自己的环境中展示 AMP 内容的消费者平台也可以使用该缓存服务。请通过 [Github](https://github.com/ampproject/amphtml/issues/new) 与我们联系，我们会尽快解答您的问题。

### 广告或技术供应商如何参与 Accelerated Mobile Pages 项目？

请查看[贡献指南](https://github.com/ampproject/amphtml/tree/master/3p#ads)，并通过 [Github](https://github.com/ampproject/amphtml/issues/new) 与我们联系。

## 发布商获利

### Accelerated Mobile Pages 如何处理广告？

Accelerated Mobile Pages 项目的一个目标是采用以用户为中心的方法，同时确保发布商能够在移动网页上通过广告获利。因此，我们的目标是在 Accelerated Mobile Pages 中为各种各样的广告格式、广告网络以及相关技术提供支持。作为其中的一部分，参与该项目的相关方还将参与编写可持续广告做法，以确保 AMP 文件中的广告能够快速安全地呈现给用户、极具吸引力且效果卓著。

### 发布商能销售自己的广告资源吗？

能。就像使用现有网站一样，发布商可以掌控自己的广告资源及其销售方式。

### Accelerated Mobile Pages 如何处理订阅和付费墙？

支持订阅和付费墙是 Accelerated Mobile Pages 项目的一个核心目标。AMP 目前支持灵活的访问框架，借助该框架，发布商可以掌控订阅者、按使用量付费的用户以及匿名用户的文档阅览体验。

### 这种 AMP 格式如何处理分析事务？

确保发布商能够获得可靠的分析数据是该项目的一个核心设计目标。演示版本中对分析功能的支持非常有限，而相应规范有望支持收集分析信息，并在不影响 AMP 文件速度或大小的情况下集成第三方系统。一些分析服务提供商正在[参与](https://www.ampproject.org/who/#analytics)该项目。

### 从衡量角度而言，相应流量会计入发布商的统计数据吗？

会。AMP 文件与您网站上的其他内容一样 - 这个空间由发布商支配。

### 如何参与该项目？

欢迎有意参与该项目的个人和公司填写 [Github](https://github.com/ampproject/amphtml/issues/new)，我们会将您添加到分发列表中，并在后续有任何新的消息时及时通知您。
