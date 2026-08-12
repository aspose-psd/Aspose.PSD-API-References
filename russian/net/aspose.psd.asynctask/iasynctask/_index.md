---
title: "Интерфейс IAsyncTask"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Интерфейс Aspose.PSD.AsyncTask.IAsyncTask. Асинхронная задача"
type: docs
weight: 80
url: /ru/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

Асинхронная задача.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Возвращает ошибку задачи, доступную после её завершения. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Возвращает значение, указывающее, выполняется ли эта задача в данный момент. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Возвращает значение, указывающее, была ли эта задача отменена. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Возвращает значение, указывающее, завершилась ли эта задача с ошибкой. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Возвращает прогресс асинхронной задачи. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Получает результат этой задачи. |

## Методы

| Имя | Описание |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Прерывает эту задачу. Задача завершается немедленно, с риском не освобождения внутренних неуправляемых ресурсов. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Отменяет эту задачу. Задача завершается безопасно за счёт контролируемой остановки алгоритма. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Запускает эту задачу. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Запускает эту задачу. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Устанавливает делегат обратного вызова завершения. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Устанавливает делегат обратного вызова прогресса. |

### См. также

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


