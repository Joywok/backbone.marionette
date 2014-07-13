<h1 align="center">Backbone.Marionette</h1>
<p align="center">
  <img title="backbone marionette" src='http://marionettejs.com/downloads/marionette-gh-banner.svg' />
</p>
<p align="center"> Make your Backbone.js apps dance!</p>
<p align="center"> 让你的Backbone.js应用舞动起来！</p>
<p align="center">
  <a title='Build Status' href="https://travis-ci.org/marionettejs/backbone.marionette">
    <img src='https://secure.travis-ci.org/marionettejs/backbone.marionette.svg?branch=master' />
  </a>
  <a href='https://coveralls.io/r/marionettejs/backbone.marionette'>
    <img src='https://img.shields.io/coveralls/marionettejs/backbone.marionette.svg' alt='Coverage Status' />
  </a>
</p>

## About Marionette

Backbone.Marionette is a composite application library for Backbone.js that
aims to simplify the construction of large scale JavaScript applications.
It is a collection of common design and implementation patterns found in
applications.

## 关于 Marionette

Backbone.Marioneete是Backbone.js的复合应用程序库，旨在简化大型JavaScript应用的建设，是一组在应用中常见的设计与实现模式集合。

### App Architecture On Backbone's Building Blocks
### 基于Backbone模块的应用程序架构

Backbone provides a great set of building blocks for our JavaScript
applications. It gives us the core constructs that are needed to build
small apps, organize jQuery DOM events, or create single page apps that
support mobile devices and large scale enterprise needs. But Backbone is
not a complete framework. It's a set of building blocks. It leaves
much of the application design, architecture and scalability to the
developer, including memory management, view management, and more.

Backbone为我们的JavaScript应用程序提供了大量的模块。它为我们生成小型应用程序，管理jQuery DOM事件，甚至创建一个支持移动端设备并且能够支持大型企业需求的单页面应用程序提供了核心框架。但是，Backbone并不是一个完整的框架。它还只是一套模块。它给开发人员留下了大量的应用程序的设计、架构方式以及可扩展性缺项，包括内存管理、视图管理等等。

Marionette brings an application architecture to Backbone, along with
built in view management and memory management. It's designed to be a
lightweight and flexible library of tools that sits on top of Backbone,
providing the framework for building a scalable application.

Marionette为Backbone提供了包含视图管理和内存管理的应用程序架构方式。Marionette是基于Backbone的轻巧灵活的工具库，为构建一个可扩展的应用程序提供框架。

Like Backbone itself, you're not required to use all of Marionette just
because you want to use some of it. You can pick and choose which features
you want to use. This allows you to work with other Backbone
frameworks and plugins easily. It also means that you are not required
to engage in an all-or-nothing migration to begin using Marionette.

就像Backbone本身，你如果只需要使用一部分Marionette的功能，则不需要使用它的所有功能。你可以挑选你需要的特性来使用，这也使得你很容易同时集成其他Backbone框架和插件。这也意味着，你在准备使用Marionette框架前，不必纠结是全部使用还是完全不用。

### Chat with us
### 联系我们

Find us [on gitter](https://gitter.im/marionettejs/backbone.marionette) or on IRC in the FreeNode.net [#marionette channel](http://freenode.net).

We're happy to discuss design patterns and learn how you're using Marionette.

使用 [gitter](https://gitter.im/marionettejs/backbone.marionette) 或IRC客户端，在FreeNode.net [#marionette](http://freenode.net) 频道中可以找到我们。

我们很高兴与你一起讨论设计模式，我们也想了解你是如何使用Marionette的。

### Key Benefits
### 优势

* Scalable: applications are built in modules, and with event-driven architecture
* Sensible defaults: Underscore templates are used for view rendering
* Easily modifiable: make it work with your application's specific needs
* Reduce boilerplate for views, with specialized view types
* Build on a modular architecture with an `Application` and modules that attach to it
* Compose your application's visuals at runtime, with the `Region` and `LayoutView` objects
* Nested views and layouts within visual regions
* Built-in memory management and zombie-killing in views, regions and layoutViews
* Event-driven architecture with `Backbone.Wreqr.EventAggregator`
* Flexible, "as-needed" architecture allowing you to pick and choose what you need
* And much, much more

* 扩展性：应用程序由模块构建，拥有事件驱动架构
* 预设行为（模板技术）：视图通过Underscore模板进行渲染
* 容易实现：轻松实现应用程序中的特性需求
* 提供专用的视图类型，减少视图模板
* 提供 `Application` 和 `modules` 组件，来创建模块化的体系结构
* 提供 `Region ` 和 `LayoutView` 对象，在运行时展示应用视觉效果
* 在可视区嵌套视图和布局
* 内置内存管理，清理views、regions、layoutViews中的僵尸进程
* 通过 `Backbone.Wreqr.EventAggregator` 实现事件驱动体系架构
* 灵活的、“按需加载”的架构使得你真的可以按需加载
* 还有好多、好多


## Source Code and Downloads

You can download the latest builds directly from the "lib" folder above.
For more information about the files in this folder, or to obtain an archive
containing all Marionette dependencies (including Underscore, Backbone, etc.),
please visit [the downloads section on the website](http://marionettejs.com#download).

#### [MarionetteJS.com](http://marionettejs.com#download)

### Available Packages

Marionette is available via bower, npm, and component.io. There are other channels that are maintained by the community.

##### [Available Packages](https://github.com/marionettejs/backbone.marionette/wiki/Available-packages)

## Release Notes And Upgrade Guide

**Changelog**: For change logs and release notes, see the
[changelog](changelog.md) file.

**Upgrade Guide**: Be sure to read [the upgrade guide](upgradeGuide.md)
for information on upgrading to the latest version of Marionette.

## Documentation

All of the documentation for Marionette can be found at

##### [marionettejs.com/docs/current](http://marionettejs.com/docs/current)

### Annotated Source Code

The source code for Marionette is heavily documented.
You can read the annotations for all the details of how Marionette works, and advice on which methods to override.

##### [View the annotated source code](http://marionettejs.com/annotated-src/backbone.marionette)

## Compatibility and Requirements

MarionetteJS currently works with the following libraries:

* [jQuery](http://jquery.com) v1.8+
* [Underscore](http://underscorejs.org) v1.4.4 - 1.6.0
* [Backbone](http://backbonejs.org) v1.0.0 - 1.1.2 are preferred. v0.9.9 and v0.9.10 should work still
* [Backbone.Wreqr](https://github.com/marionettejs/backbone.wreqr) Comes automatically with the bundled build.
* [Backbone.BabySitter](https://github.com/marionettejs/backbone.babysitter) Comes automatically with the bundled build.

Marionette has not been tested against any other versions of these
libraries. You may or may not have success if you use a version other
than what it listed here.


## How to Contribute

If you would like to contribute to Marionette's source code, please read
the [guidelines for pull requests and contributions](CONTRIBUTING.md).
Following these guidelines will help make your contributions easier to
bring into the next release.

### [Github Issues](//github.com/marionettejs/backbone.marionette/issues)

Report issues with Marionette, submit pull requests to fix problems, or to
create summarized and documented feature requests (preferably with pull
requests that implement the feature).
