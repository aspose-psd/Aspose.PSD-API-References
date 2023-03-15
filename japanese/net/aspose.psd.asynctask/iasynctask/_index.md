---
title: Interface IAsyncTask
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.AsyncTask.IAsyncTask インターフェース. 非同期タスク.
type: docs
weight: 80
url: /ja/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

非同期タスク.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | タスクの完了後に利用可能なタスク エラーを取得します。 |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | このタスクが現在実行中かどうかを示す値を取得します。 |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | このタスクがキャンセルされたかどうかを示す値を取得します。 |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | このタスクが失敗したかどうかを示す値を取得します。 |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | 非同期タスクの進行状況を取得します。 |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | このタスクの結果を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | このタスクを中止します。 タスクはすぐに完了しますが、管理されていない内部リソースを解放しないリスクがあります。 |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | このタスクをキャンセルします。 タスクは、アルゴリズムの制御された停止によって安全に完了します。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | このタスクを実行します。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | このタスクを実行します。 |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 完全なコールバック デリゲートを設定します。 |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | プログレス コールバック デリゲートを設定します。 |

### 関連項目

* 名前空間 [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* 組み立て [Aspose.PSD](../../)


