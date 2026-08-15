---
title: "IAsyncTask Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| is_busy | bool | r | Haalt een waarde op die aangeeft of deze taak momenteel wordt uitgevoerd. |
| is_canceled | bool | r | Haalt een waarde op die aangeeft of deze taak is geannuleerd. |
| is_faulted | bool | r | Haalt een waarde op die aangeeft of deze taak is mislukt. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Haalt de voortgang van de asynchrone taak op. |
| result | object | r | Haalt het resultaat van deze taak op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| abort() | Stopt deze taak af.<br/>            De taak wordt onmiddellijk voltooid, met het risico dat interne niet-beheerde bronnen niet worden vrijgegeven. |
| cancel() | Annuleert deze taak.<br/>            De taak wordt veilig voltooid door het gecontroleerd stoppen van het algoritme. |
| run_async() | Voert deze taak uit. |


