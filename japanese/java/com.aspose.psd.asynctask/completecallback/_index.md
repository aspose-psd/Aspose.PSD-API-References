---
title: "CompleteCallback"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "タスク完了イベントを受け取るコールバック関数です。"
type: docs
weight: 15
url: /ja/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

タスク完了イベントを受け取るコールバック関数です。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | タスク完了イベントを受け取るコールバック関数です。 |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


タスク完了イベントを受け取るコールバック関数です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | 非同期タスクです。 |
| wasCancelled | boolean | true に設定された場合 [キャンセルされました]。 |
| エラー | java.lang.Throwable | エラーです。 |

