## 目标

当前社区有很多 React 源码分析文章，但不够成体系，内容质量也参差不齐。基于此原因，本书的意在打造一本成体系、好理解、高质量的React源码技术分析教程。为了达到这个目标，在行文上，本书会遵循：

1. 不预设观点——所有观点来自React核心团队成员在公开场合发表的内容。
2. Demo、引用资源辅助理解。
3. 保持更新——在React版本更新后会及时补充。当前版本`v16.13.1`

## 章节说明
你可以从侧边栏章节目录看到，我们并没有从如`ReactDOM.render`、`this.setState`或`hooks`等这样日常开发耳熟能详的`API`入手，而是从**理念**这样比较高的抽象层次开始，由理念推导出架构，再讲解架构的每个部分是如何互相配合完成UI渲染，最后讲具体的`API`是如何接入这套架构中的。

这就像我们想了解一颗炮仗是如何爆炸的，先了整个炮仗的结构，最后再了解如何把引线插在炮仗上不就轻而易举了么？

## TODO

### 第一章 准备工作

✅ React理念

✅ 老的React架构

✅ 新的React架构

:black_square_button: 源码的文件结构

:black_square_button: 深入理解JSX

### 第二章 渲染流程

:black_square_button: mount

:black_square_button: update

### 第三章 协调流程

:black_square_button: key

:black_square_button: 单一组件协调

:black_square_button: 多组件协调

### 第四章 调度流程