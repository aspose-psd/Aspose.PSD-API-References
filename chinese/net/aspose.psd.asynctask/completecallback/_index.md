---
title: "委托 CompleteCallback"
second_title: "Aspose.PSD for .NET API 参考"
description: "用于接收任务完成事件的回调函数"
type: docs
weight: 70
url: /zh/net/aspose.psd.asynctask/completecallback/
---
{{< psd/tize >}}
## CompleteCallback delegate

用于接收任务完成事件的回调函数。

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| task | IAsyncTask | 异步任务。 |
| wasCancelled | 布尔 | 如果设置为 `true` [已取消]。 |
| error | 异常 | 错误。 |

### 另请参阅

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


