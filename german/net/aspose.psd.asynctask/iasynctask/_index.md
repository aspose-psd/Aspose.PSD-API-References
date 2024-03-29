---
title: Interface IAsyncTask
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.AsyncTask.IAsyncTask koppel. Die asynchrone Aufgabe.
type: docs
weight: 80
url: /de/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

Die asynchrone Aufgabe.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Ruft den Aufgabenfehler ab, der verfügbar ist, nachdem die Aufgabe abgeschlossen ist. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Ruft einen Wert ab, der angibt, ob diese Aufgabe derzeit ausgeführt wird. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Ruft einen Wert ab, der angibt, ob diese Aufgabe abgebrochen wurde. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Ruft einen Wert ab, der angibt, ob diese Aufgabe fehlerhaft war. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Ruft den Fortschritt der asynchronen Aufgabe ab. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Ruft das Ergebnis dieser Aufgabe ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Bricht diese Aufgabe ab. Die Aufgabe wird sofort abgeschlossen, wobei das Risiko besteht, dass interne, nicht verwaltete Ressourcen nicht freigegeben werden. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Bricht diese Aufgabe ab. Die Aufgabe wird durch das kontrollierte Stoppen des Algorithmus sicher abgeschlossen. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Führt diese Aufgabe aus. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Führt diese Aufgabe aus. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Legt den vollständigen Callback-Delegaten fest. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Legt den Fortschritts-Callback-Delegaten fest. |

### Siehe auch

* namensraum [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* Montage [Aspose.PSD](../../)


