---
title: "Interface IAsyncTask"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.AsyncTask.IAsyncTask interface. La tâche asynchrone"
type: docs
weight: 80
url: /fr/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

La tâche asynchrone.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Obtient l'erreur de la tâche qui est disponible après que la tâche soit terminée. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Obtient une valeur indiquant si cette tâche a été annulée. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Obtient une valeur indiquant si cette tâche a échoué. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Obtient la progression de la tâche asynchrone. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Obtient le résultat de cette tâche. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Interrompt cette tâche. La tâche est terminée immédiatement, avec le risque de ne pas libérer les ressources internes non gérées. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Annule cette tâche. La tâche est terminée en toute sécurité par l'arrêt contrôlé de l'algorithme. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Exécute cette tâche. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Exécute cette tâche. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Définit le délégué de rappel complet. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Définit le délégué de rappel de progression. |

### Voir aussi

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


