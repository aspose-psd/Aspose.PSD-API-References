---
title: "IAsyncTask-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| is_busy | bool | r | Hämtar ett värde som indikerar om denna uppgift för närvarande körs. |
| is_canceled | bool | r | Hämtar ett värde som indikerar om denna uppgift avbröts. |
| is_faulted | bool | r | Hämtar ett värde som indikerar om denna uppgift misslyckades. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Hämtar framstegen för den asynkrona uppgiften. |
| result | object | r | Hämtar resultatet av denna uppgift. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| abort() | Avbryter denna uppgift.<br/>            Uppgiften avslutas omedelbart, med risken att interna ohanterade resurser inte frigörs. |
| cancel() | Avbryter denna uppgift.<br/>            Uppgiften avslutas säkert genom att algoritmen stoppas kontrollerat. |
| run_async() | Kör den här uppgiften. |


