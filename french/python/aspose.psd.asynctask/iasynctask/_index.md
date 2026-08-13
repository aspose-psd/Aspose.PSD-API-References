---
title: "Classe IAsyncTask"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution. |
| is_canceled | bool | r | Obtient une valeur indiquant si cette tâche a été annulée. |
| is_faulted | bool | r | Obtient une valeur indiquant si cette tâche a échoué. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Obtient la progression de la tâche asynchrone. |
| result | object | r | Obtient le résultat de cette tâche. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Interrompt cette tâche.<br/>            La tâche est terminée immédiatement, avec le risque de ne pas libérer les ressources internes non gérées. |
| cancel() | Annule cette tâche.<br/>            La tâche est terminée en toute sécurité par l'arrêt contrôlé de l'algorithme. |
| run_async() | Exécute cette tâche. |


