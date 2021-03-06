---
lang: en
title: 'API docs: core.createservicebinding'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/core
permalink: /doc/en/lb4/apidocs.core.createservicebinding.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/core](./core.md) &gt; [createServiceBinding](./core.createservicebinding.md)

## createServiceBinding() function

Create a service binding from a class or provider

<b>Signature:</b>

```typescript
export declare function createServiceBinding<S>(cls: Constructor<S | Provider<S>>, options?: ServiceOptions): Binding<S>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  cls | [Constructor](./context.constructor.md)<!-- -->&lt;S \| [Provider](./context.provider.md)<!-- -->&lt;S&gt;&gt; | Service class or provider |
|  options | [ServiceOptions](./core.serviceoptions.md) | Service options |

<b>Returns:</b>

[Binding](./context.binding.md)<!-- -->&lt;S&gt;


