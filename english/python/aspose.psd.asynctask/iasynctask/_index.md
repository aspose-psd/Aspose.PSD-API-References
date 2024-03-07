---
title: IAsyncTask Class
type: docs
weight: 40
url: /python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.1.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Gets a value indicating whether this task is currently running. |
| is_canceled | bool | r | Gets a value indicating whether this task was canceled. |
| is_faulted | bool | r | Gets a value indicating whether this task was faulted. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Gets the progress of the asynchronous task. |
| result | object | r | Gets the result of this task. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Aborts this task.<br/>            The task is completed immediately, with the risk of not freeing internal unmanaged resources. |
| cancel() | Cancels this task.<br/>            The task is completed safely by the controlled stopping of the algorithm. |
| run_async() | Runs this task. |


