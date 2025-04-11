```markdown
# Understanding the Basics of React

This document provides a basic overview of React, a popular JavaScript library for building user interfaces.

## What is React?

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It allows developers to create complex UIs from small and isolated pieces of code called "components".

## Key Concepts

*   **Components:** Reusable and independent pieces of UI. Components can be as simple as a button or as complex as an entire application.
*   **JSX:** A syntax extension to JavaScript that allows you to write HTML-like structures in your JavaScript code.
*   **Virtual DOM:** A lightweight copy of the actual DOM. React uses the virtual DOM to efficiently update the actual DOM only when necessary.
*   **Props:** Input data passed from a parent component to a child component. Props are read-only.
*   **State:** Data that is managed within a component and can change over time. Changes in state trigger re-renders of the component.
*   **Lifecycle Methods:** Special methods that are called at different stages of a component's lifecycle (e.g., when the component is mounted, updated, or unmounted).

## Example

Here's a simple example of a React component:

```javascript
import React from 'react';

function MyComponent(props) {
  return (
    <h1>Hello, {props.name}!</h1>
  );
}

export default MyComponent;
```

This component takes a `name` prop and displays a greeting.

## Further Learning

*   [React Official Documentation](https://reactjs.org/)
*   [Create React App](https://create-react-app.dev/)

This is just a brief introduction. React has a lot more to offer, so explore the documentation and build your own components!
```

```zh
# 理解 React 的基础知识

本文档提供了 React 的基本概述，React 是一个流行的 JavaScript 库，用于构建用户界面。

## 什么是 React？

React 是一个声明式的、高效的、灵活的 JavaScript 库，用于构建用户界面。 它允许开发人员从称为“组件”的小而独立的 pieces of code 创建复杂的 UI。

## 关键概念

*   **组件 (Components):** 可重用和独立的 UI 片段。 组件可以像按钮一样简单，也可以像整个应用程序一样复杂。
*   **JSX:** JavaScript 的语法扩展，允许你在 JavaScript 代码中编写类似 HTML 的结构。
*   **虚拟 DOM (Virtual DOM):** 实际 DOM 的轻量级副本。 React 使用虚拟 DOM 来仅在必要时有效地更新实际 DOM。
*   **Props:** 从父组件传递到子组件的输入数据。 Props 是只读的。
*   **State:** 在组件内部管理并可以随时间变化的数据。 State 的更改会触发组件的重新渲染。
*   **生命周期方法 (Lifecycle Methods):** 在组件生命周期的不同阶段调用的特殊方法（例如，当组件挂载、更新或卸载时）。

## 示例

这是一个简单的 React 组件示例：

```javascript
import React from 'react';

function MyComponent(props) {
  return (
    <h1>Hello, {props.name}!</h1>
  );
}

export default MyComponent;
```

此组件接受一个 `name` prop 并显示一条问候语。

## 进一步学习

*   [React Official Documentation](https://reactjs.org/)
*   [Create React App](https://create-react-app.dev/)

这只是一个简短的介绍。 React 还有很多东西可以提供，所以探索文档并构建你自己的组件！
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._