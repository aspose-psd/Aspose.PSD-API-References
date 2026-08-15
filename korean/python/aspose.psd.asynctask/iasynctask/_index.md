---
title: "IAsyncTask 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| is_busy | bool | r | 이 작업이 현재 실행 중인지 여부를 나타내는 값을 가져옵니다. |
| is_canceled | bool | r | 이 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다. |
| is_faulted | bool | r | 이 작업이 오류가 발생했는지 여부를 나타내는 값을 가져옵니다. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | 비동기 작업의 진행률을 가져옵니다. |
| result | object | r | 이 작업의 결과를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| abort() | 이 작업을 중단합니다.<br/>            작업이 즉시 완료되며, 내부 비관리 리소스를 해제하지 않을 위험이 있습니다. |
| cancel() | 이 작업을 취소합니다.<br/>            알고리즘을 제어된 방식으로 중지하여 작업이 안전하게 완료됩니다. |
| run_async() | 이 작업을 실행합니다. |


