---
lang: en
title: 'API docs: boot.lifecycleobserverbooter'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.boot.lifecycleobserverbooter.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/boot](./boot.md) &gt; [LifeCycleObserverBooter](./boot.lifecycleobserverbooter.md)

## LifeCycleObserverBooter class

A class that extends BaseArtifactBooter to boot the 'LifeCycleObserver' artifact type.

Supported phases: configure, discover, load

<b>Signature:</b>

```typescript
export declare class LifeCycleObserverBooter extends BaseArtifactBooter 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(app, projectRoot, observerConfig)](./boot.lifecycleobserverbooter._constructor_.md) |  | Constructs a new instance of the <code>LifeCycleObserverBooter</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [app](./boot.lifecycleobserverbooter.app.md) |  | <code>Application</code> |  |
|  [observerConfig](./boot.lifecycleobserverbooter.observerconfig.md) |  | <code>ArtifactOptions</code> |  |
|  [observers](./boot.lifecycleobserverbooter.observers.md) |  | <code>LifeCycleObserverClass[]</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [load()](./boot.lifecycleobserverbooter.load.md) |  | Uses super method to get a list of Artifact classes. Boot each file by creating a DataSourceConstructor and binding it to the application class. |

