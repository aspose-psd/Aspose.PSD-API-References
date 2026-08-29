---
title: "Schnittstelle IAsyncTask"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.AsyncTask.IAsyncTask Schnittstelle. Die asynchrone Aufgabe"
type: docs
weight: 80
url: /de/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

Die asynchrone Aufgabe.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Gibt den Aufgabenfehler zurück, der nach Abschluss der Aufgabe verfügbar ist. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Gibt einen Wert zurück, der angibt, ob diese Aufgabe gerade ausgeführt wird. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Gibt einen Wert zurück, der angibt, ob diese Aufgabe abgebrochen wurde. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Gibt einen Wert zurück, der angibt, ob diese Aufgabe fehlerhaft war. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Gibt den Fortschritt der asynchronen Aufgabe zurück. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Gibt das Ergebnis dieser Aufgabe zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Bricht diese Aufgabe ab. Die Aufgabe wird sofort abgeschlossen, mit dem Risiko, interne nicht verwaltete Ressourcen nicht freizugeben. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Bricht diese Aufgabe ab. Die Aufgabe wird sicher abgeschlossen, indem der Algorithmus kontrolliert gestoppt wird. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Führt diese Aufgabe aus. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Führt diese Aufgabe aus. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Setzt den Callback-Delegaten für den Abschluss. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Setzt den Callback-Delegaten für den Fortschritt. |

### Siehe auch

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


