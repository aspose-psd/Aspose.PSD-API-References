---
title: "CompleteCallback"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于接收任务完成事件的回调函数。"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

用于接收任务完成事件的回调函数。
## Methods

| Method | 描述 |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | 用于接收任务完成事件的回调函数。 |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


用于接收任务完成事件的回调函数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | 异步任务。 |
| wasCancelled | boolean | 如果设置为 true [已取消]。 |
| 错误 | java.lang.Throwable | 错误。 |

