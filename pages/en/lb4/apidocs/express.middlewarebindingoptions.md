---
lang: en
title: 'API docs: express.middlewarebindingoptions'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/express
permalink: /doc/en/lb4/apidocs.express.middlewarebindingoptions.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/express](./express.md) &gt; [MiddlewareBindingOptions](./express.middlewarebindingoptions.md)

## MiddlewareBindingOptions interface

Options to bind middleware as a request context based interceptor within an `InvokeMiddleware` action of the sequence.

<b>Signature:</b>

```typescript
export interface MiddlewareBindingOptions extends BaseMiddlewareBindingOptions<MiddlewareContext> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [chain](./express.middlewarebindingoptions.chain.md) | string | Name of the middleware extension point. Default to <code>DEFAULT_MIDDLEWARE_CHAIN</code>. |

