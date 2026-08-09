---
title: "接口 IAsyncTask"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.AsyncTask.IAsyncTask 接口。异步任务。"
type: docs
weight: 80
url: /zh/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

异步任务。

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | 获取任务错误，该错误在任务完成后可用。 |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | 获取一个值，指示此任务当前是否正在运行。 |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | 获取一个值，指示此任务是否已被取消。 |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | 获取一个值，指示此任务是否已出现错误。 |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | 获取异步任务的进度。 |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | 获取此任务的结果。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | 中止此任务。任务会立即完成，但可能无法释放内部非托管资源。 |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | 取消此任务。任务通过受控停止算法安全完成。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | 运行此任务。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | 运行此任务。 |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 设置完成回调委托。 |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | 设置进度回调委托。 |

### 另请参阅

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


