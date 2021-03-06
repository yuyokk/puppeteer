<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [LoadingFailedEvent](./puppeteer.protocol.network.loadingfailedevent.md)

## Protocol.Network.LoadingFailedEvent interface

Fired when HTTP request has failed to load.

<b>Signature:</b>

```typescript
export interface LoadingFailedEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [blockedReason](./puppeteer.protocol.network.loadingfailedevent.blockedreason.md) | [BlockedReason](./puppeteer.protocol.network.blockedreason.md) | The reason why loading was blocked, if any. |
|  [canceled](./puppeteer.protocol.network.loadingfailedevent.canceled.md) | boolean | True if loading was canceled. |
|  [errorText](./puppeteer.protocol.network.loadingfailedevent.errortext.md) | string | User friendly error message. |
|  [requestId](./puppeteer.protocol.network.loadingfailedevent.requestid.md) | [RequestId](./puppeteer.protocol.network.requestid.md) | Request identifier. |
|  [timestamp](./puppeteer.protocol.network.loadingfailedevent.timestamp.md) | [MonotonicTime](./puppeteer.protocol.network.monotonictime.md) | Timestamp. |
|  [type](./puppeteer.protocol.network.loadingfailedevent.type.md) | [ResourceType](./puppeteer.protocol.network.resourcetype.md) | Resource type. |

