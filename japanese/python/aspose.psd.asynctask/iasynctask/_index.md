---
title: "IAsyncTask クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| is_busy | bool | r | このタスクが現在実行中かどうかを示す値を取得します。 |
| is_canceled | bool | r | このタスクがキャンセルされたかどうかを示す値を取得します。 |
| is_faulted | bool | r | このタスクがエラー状態かどうかを示す値を取得します。 |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | 非同期タスクの進捗を取得します。 |
| result | object | r | このタスクの結果を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| abort() | このタスクを中止します。<br/>            タスクは直ちに完了しますが、内部のアンマネージドリソースが解放されないリスクがあります。 |
| cancel() | このタスクをキャンセルします。<br/>            アルゴリズムを制御された停止により、タスクは安全に完了します。 |
| run_async() | このタスクを実行します。 |


