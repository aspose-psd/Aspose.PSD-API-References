---
title: Interface IAsyncTask
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.AsyncTask.IAsyncTask interface. The asynchronous task
type: docs
weight: 80
url: /net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

The asynchronous task.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Gets the task error which is available after the task is completed. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Gets a value indicating whether this task is currently running. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Gets a value indicating whether this task was canceled. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Gets a value indicating whether this task was faulted. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Gets the progress of the asynchronous task. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Gets the result of this task. |

## Methods

| Name | Description |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Aborts this task. The task is completed immediately, with the risk of not freeing internal unmanaged resources. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Cancels this task. The task is completed safely by the controlled stopping of the algorithm. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Runs this task. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Runs this task. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Sets the complete callback delegate. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Sets the progress callback delegate. |

### See Also

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


