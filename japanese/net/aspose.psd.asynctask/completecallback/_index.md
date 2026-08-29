---
title: "デリゲート CompleteCallback"
second_title: "Aspose.PSD for .NET API Reference"
description: "タスク完了イベントを受け取るコールバック関数"
type: docs
weight: 70
url: /ja/net/aspose.psd.asynctask/completecallback/
---
{{< psd/tize >}}
## CompleteCallback delegate

タスク完了イベントを受け取るコールバック関数。

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| task | IAsyncTask | 非同期タスクです。 |
| wasCancelled | Boolean | `true` に設定された場合 [キャンセルされました]。 |
| error | Exception | エラーです。 |

### 関連項目

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


