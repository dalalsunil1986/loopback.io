---
lang: en
title: 'API docs: service-proxy'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.service-proxy.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/service-proxy](./service-proxy.md)

## service-proxy package

[@loopback/service-proxy](https://github.com/strongloop/loopback-next/tree/master/packages/service-proxy)

## Classes

|  Class | Description |
|  --- | --- |
|  [ServiceMixinDoc](./service-proxy.servicemixindoc.md) | A dummy class created to generate the tsdoc for the members in service mixin. Please don't use it.<!-- -->The members are implemented in function <a href="#ServiceMixin">ServiceMixin</a> |
|  [ServiceProxyMetadata](./service-proxy.serviceproxymetadata.md) | Metadata for a service proxy |

## Functions

|  Function | Description |
|  --- | --- |
|  [getService(ds)](./service-proxy.getservice.md) | Get a service proxy from a LoopBack 3.x data source backed by service-oriented connectors such as <code>rest</code>, <code>soap</code>, and <code>grpc</code>. |
|  [ServiceMixin(superClass)](./service-proxy.servicemixin.md) | A mixin class for Application that creates a .serviceProvider() function to register a service automatically. Also overrides component function to allow it to register repositories automatically. |
|  [serviceProxy(dataSource)](./service-proxy.serviceproxy.md) |  |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [ApplicationWithServices](./service-proxy.applicationwithservices.md) | Interface for an Application mixed in with ServiceMixin |
|  [Class](./service-proxy.class.md) | Interface for classes with <code>new</code> operator. |
|  [GenericService](./service-proxy.genericservice.md) | A generic service interface with any number of methods that return a promise |

## Namespaces

|  Namespace | Description |
|  --- | --- |
|  [juggler](./service-proxy.juggler.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [SERVICE\_PROXY\_KEY](./service-proxy.service_proxy_key.md) |  |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [ServiceProxyDecorator](./service-proxy.serviceproxydecorator.md) | Type definition for decorators returned by <code>@serviceProxy</code> decorator factory |

