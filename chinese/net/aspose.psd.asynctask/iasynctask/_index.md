---
title: Interface IAsyncTask
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.AsyncTask.IAsyncTask 界面. 异步任务
type: docs
weight: 80
url: /zh/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

异步任务。

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | 获取任务错误，任务完成后可用。 |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | 获取指示此任务当前是否正在运行的值。 |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | 获取指示此任务是否已取消的值。 |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | 获取指示此任务是否出错的值。 |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | 获取异步任务的进度。 |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | 获取此任务的结果。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | 中止此任务。 任务立即完成，存在不释放内部非托管资源的风险。 |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | 取消此任务。 通过算法的受控停止安全完成任务。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | 运行此任务。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | 运行此任务。 |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 设置完整的回调委托。 |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | 设置进度回调委托。 |

### 也可以看看

* 命名空间 [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* 部件 [Aspose.PSD](../../)


