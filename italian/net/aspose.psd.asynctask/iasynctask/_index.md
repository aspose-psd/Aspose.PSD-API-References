---
title: Interface IAsyncTask
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.AsyncTask.IAsyncTask interfaccia. Lattività asincrona.
type: docs
weight: 80
url: /it/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

L'attività asincrona.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Ottiene l'errore dell'attività che è disponibile dopo che l'attività è stata completata. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Ottiene un valore che indica se questa attività è attualmente in esecuzione. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Ottiene un valore che indica se questa attività è stata annullata. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Ottiene un valore che indica se questa attività è stata errata. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Ottiene l'avanzamento dell'attività asincrona. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Ottiene il risultato di questa attività. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Interrompe questa attività. L'attività viene completata immediatamente, con il rischio di non liberare risorse interne non gestite. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Annulla questa attività. L'attività viene completata in modo sicuro dall'arresto controllato dell'algoritmo. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Esegue questa attività. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Esegue questa attività. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Imposta il delegato di richiamata completo. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Imposta il delegato di callback di avanzamento. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assemblea [Aspose.PSD](../../)


