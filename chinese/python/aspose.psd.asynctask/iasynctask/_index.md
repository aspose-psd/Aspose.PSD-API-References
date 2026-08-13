---
title: "IAsyncTask 类"
type: docs
weight: 40
url: /zh/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | 获取一个值，指示此任务当前是否正在运行。 |
| is_canceled | bool | r | 获取一个值，指示此任务是否已被取消。 |
| is_faulted | bool | r | 获取一个值，指示此任务是否已出现错误。 |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | 获取异步任务的进度。 |
| result | object | r | 获取此任务的结果。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | 中止此任务。<br/>            任务会立即完成，但可能无法释放内部的非托管资源。 |
| cancel() | 取消此任务。<br/>            通过受控停止算法，任务安全完成。 |
| run_async() | 运行此任务。 |


