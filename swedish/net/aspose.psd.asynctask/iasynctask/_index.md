---
title: "Gränssnitt IAsyncTask"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.AsyncTask.IAsyncTask-gränssnitt. Den asynkrona uppgiften"
type: docs
weight: 80
url: /sv/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

Den asynkrona uppgiften.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Hämtar uppgiftsfelet som är tillgängligt efter att uppgiften har slutförts. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Hämtar ett värde som indikerar om denna uppgift för närvarande körs. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Hämtar ett värde som indikerar om denna uppgift avbröts. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Hämtar ett värde som indikerar om denna uppgift misslyckades. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Hämtar framsteget för den asynkrona uppgiften. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Hämtar resultatet av denna uppgift. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Avbryter denna uppgift. Uppgiften avslutas omedelbart, med risken att interna ohanterade resurser inte frigörs. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Avbryter denna uppgift. Uppgiften avslutas säkert genom kontrollerad stoppning av algoritmen. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Kör denna uppgift. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Kör denna uppgift. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Ställer in den kompletta återanropsdelegaten. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Ställer in återanropsdelegaten för framsteg. |

### Se även

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


