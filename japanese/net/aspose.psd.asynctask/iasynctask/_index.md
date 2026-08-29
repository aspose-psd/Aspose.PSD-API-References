---
title: "インターフェイス IAsyncTask"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.AsyncTask.IAsyncTask インターフェイス。非同期タスクです。"
type: docs
weight: 80
url: /ja/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

非同期タスクです。

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | タスクが完了した後に利用可能なタスクエラーを取得します。 |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | このタスクが現在実行中かどうかを示す値を取得します。 |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | このタスクがキャンセルされたかどうかを示す値を取得します。 |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | このタスクが障害状態かどうかを示す値を取得します。 |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | 非同期タスクの進捗を取得します。 |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | このタスクの結果を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | このタスクを中止します。タスクは直ちに完了しますが、内部のアンマネージドリソースが解放されないリスクがあります。 |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | このタスクをキャンセルします。アルゴリズムを制御的に停止させることで、タスクは安全に完了します。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | このタスクを実行します。 |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | このタスクを実行します。 |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 完了コールバックデリゲートを設定します。 |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | 進捗コールバックデリゲートを設定します。 |

### 関連項目

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


