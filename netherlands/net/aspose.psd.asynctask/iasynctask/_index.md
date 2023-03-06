---
title: Interface IAsyncTask
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.AsyncTask.IAsyncTask koppel. De asynchrone taak.
type: docs
weight: 80
url: /nl/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

De asynchrone taak.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Krijgt de taakfout die beschikbaar is nadat de taak is voltooid. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Krijgt een waarde die aangeeft of deze taak momenteel wordt uitgevoerd. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Krijgt een waarde die aangeeft of deze taak is geannuleerd. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Krijgt een waarde die aangeeft of er een fout is opgetreden in deze taak. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Krijgt de voortgang van de asynchrone taak. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Krijgt het resultaat van deze taak. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Breekt deze taak af. De taak wordt onmiddellijk voltooid, met het risico dat interne onbeheerde bronnen niet worden vrijgemaakt. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Annuleert deze taak. De taak wordt veilig voltooid door het gecontroleerd stoppen van het algoritme. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Voert deze taak uit. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Voert deze taak uit. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Stelt de volledige callback gedelegeerde in. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Stelt de voortgang callback gedelegeerde in. |

### Zie ook

* naamruimte [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* montage [Aspose.PSD](../../)


