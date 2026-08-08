---
title: "IAsyncTaskState"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "非同期タスクの状態へのアクセスを提供します。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

非同期タスクの状態へのアクセスを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getProgress()](#getProgress--) | 非同期タスクの進捗を取得します。 |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | 進捗の最大値を増加させます。 |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | 非同期タスクの進捗を設定します。 |
| [isCanceled()](#isCanceled--) | 非同期タスクがキャンセルされているかどうかを示す値を取得します。 |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


非同期タスクの進捗を取得します。

値: 非同期タスクの進捗。

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


進捗の最大値を増加させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 増加値。 |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


非同期タスクの進捗を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 進捗状態。 |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


非同期タスクがキャンセルされているかどうかを示す値を取得します。

値: 非同期タスクがキャンセルされている場合は true、そうでない場合は false。

**Returns:**
boolean - 非同期タスクがキャンセルされているかどうかを示す値。
