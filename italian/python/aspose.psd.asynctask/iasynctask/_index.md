---
title: "IAsyncTask Classe"
type: docs
weight: 40
url: /it/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Restituisce un valore che indica se questa attività è attualmente in esecuzione. |
| is_canceled | bool | r | Restituisce un valore che indica se questa attività è stata annullata. |
| is_faulted | bool | r | Restituisce un valore che indica se questa attività ha riscontrato un errore. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Restituisce lo stato di avanzamento dell'attività asincrona. |
| result | object | r | Restituisce il risultato di questa attività. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Interrompe questa attività.<br/>            L'attività viene completata immediatamente, con il rischio di non liberare le risorse non gestite interne. |
| cancel() | Annulla questa attività.<br/>            L'attività viene completata in modo sicuro mediante l'arresto controllato dell'algoritmo. |
| run_async() | Esegue questa attività. |


