---
title: "Clase IAsyncTask"
type: docs
weight: 40
url: /es/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_busy | bool | r | Obtiene un valor que indica si esta tarea está ejecutándose actualmente. |
| is_canceled | bool | r | Obtiene un valor que indica si esta tarea fue cancelada. |
| is_faulted | bool | r | Obtiene un valor que indica si esta tarea falló. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Obtiene el progreso de la tarea asíncrona. |
| result | object | r | Obtiene el resultado de esta tarea. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| abort() | Aborta esta tarea.<br/>            La tarea se completa inmediatamente, con el riesgo de no liberar recursos internos no administrados. |
| cancel() | Cancela esta tarea.<br/>            La tarea se completa de forma segura mediante la detención controlada del algoritmo. |
| run_async() | Ejecuta esta tarea. |


