---
title: "NeoForge 开发实战"
layout: landing
---

<div class="book-hero">

# NeoForge 26.1 开发实战 {anchor=false}

这里是基于 Minecraft 26.1 与 Java 25 的现代化模组开发指南。
从环境搭建到发布你的第一个模组，我们将一步步构建。

[{{< badge style="default" title="Minecraft" value="26.1" >}}](https://www.minecraft.net/)

[{{< badge style="default" title="NeoForge" value="26.1.x.x" >}}](https://neoforged.net/)

[{{< badge style="default" title="Java" value="JDK 25" >}}](https://jdk.java.net/)

{{<button href="/docs/">}}开始学习之旅{{</button>}}

</div>

{{% columns %}}
- ## 📘 这个教程包含什么
  - **Java 语言教学**：会教学基础的 Java 语法知识（类、接口、继承、泛型）。
  - **最新的技术栈**：完全基于 NeoForge 26.1.x.x 和 Java 25 编写。
  - **实战案例**：不只是 API 文档的翻译，而是通过构建一个实际的模组来教学。
  - **最佳实践**：包含项目结构管理、Git 工作流以及代码规范建议。

- ## ❌ 这个教程不包含什么
  - **Fabric/Forge 教程**：本教程专注于 NeoForge 加载器。
  - **过时的 API**：我们不会通过“兼容旧版”的方式写代码，一切向前看。
{{% /columns %}}


{{% columns %}}
- {{< card >}}
  ## ☕ 拥抱 Java 25
  利用 Record 类、更灵活的模式匹配 (Pattern Matching) 等现代 Java 特性，让模组代码更加简洁、优雅且高效。
  {{< /card >}}

- {{< card >}}
  ## 🛠️ 强大的构建系统
  深入理解 Gradle 构建脚本，学会管理依赖、多版本构建以及自动化发布流程，让开发环境坚如磐石。
  {{< /card >}}

- {{< card >}}
  ## 🧩 模块化设计
  学习如何利用 NeoForge 的 Event Bus（事件总线）和依赖注入思想，写出低耦合、高内聚的模组代码。
  {{< /card >}}
{{% /columns %}}

{{% columns %}}
- {{< card >}}
  ### 🌱 基础篇
  从**物品 (Items)**、**方块 (Blocks)** 到 **创造模式物品栏 (Creative Tabs)**。掌握注册表 (Registry) 的核心概念，让你的第一个物品出现在游戏中。
  {{< /card >}}

- {{< card >}}
  ### 🚀 进阶篇
  深入研究 **方块实体 (Block Entities)**、**自定义实体 (Entities)** 以及 **网络发包 (Networking)**。实现复杂的机器逻辑和玩家交互功能。
  {{< /card >}}

- {{< card >}}
  ### 🎨 高级篇
  探索 **渲染 (Rendering)**、**粒子效果 (Particles)** 以及 **WorldGen (世界生成)**。使用 **Mixin** 修改原版逻辑，创造独一无二的游戏体验。
  {{< /card >}}
{{% /columns %}}