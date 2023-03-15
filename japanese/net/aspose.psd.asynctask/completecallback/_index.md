---
title: Delegate CompleteCallback
second_title: Aspose.PSD for .NET API リファレンス
description: タスク完了イベントを受け取るコールバック関数.
type: docs
weight: 70
url: /ja/net/aspose.psd.asynctask/completecallback/
---
## CompleteCallback delegate

タスク完了イベントを受け取るコールバック関数.

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| task | IAsyncTask | 非同期タスク。 |
| wasCancelled | Boolean | に設定した場合`真実` 【キャンセルしました】。 |
| error | Exception | エラー。 |

### 関連項目

* interface [IAsyncTask](../iasynctask/)
* 名前空間 [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* 組み立て [Aspose.PSD](../../)


