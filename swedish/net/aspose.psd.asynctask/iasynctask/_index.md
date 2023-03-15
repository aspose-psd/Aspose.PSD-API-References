---
title: Interface IAsyncTask
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.AsyncTask.IAsyncTask gränssnitt. Den asynkrona uppgiften.
type: docs
weight: 80
url: /sv/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

Den asynkrona uppgiften.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Hämtar uppgiftsfelet som är tillgängligt efter att uppgiften är klar. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Får ett värde som anger om denna uppgift körs för närvarande. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Får ett värde som anger om denna uppgift avbröts. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Får ett värde som indikerar om denna uppgift var felaktig. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Hämtar förloppet för den asynkrona uppgiften. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Får resultatet av denna uppgift. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Avbryter denna uppgift. Uppgiften slutförs omedelbart, med risk för att inte frigöra interna ohanterade resurser. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Avbryter den här uppgiften. Uppgiften slutförs på ett säkert sätt genom kontrollerat stopp av algoritmen. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Kör den här uppgiften. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Kör den här uppgiften. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Ställer in hela återuppringningsdelegaten. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Ställer in förloppsåteruppringningsdelegat. |

### Se även

* namnutrymme [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* hopsättning [Aspose.PSD](../../)


