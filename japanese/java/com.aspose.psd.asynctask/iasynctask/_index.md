---
title: "IAsyncTask"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "非同期タスクです。"
type: docs
weight: 16
url: /ja/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

非同期タスクです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [abort()](#abort--) | このタスクを中止します。 |
| [cancel()](#cancel--) | このタスクをキャンセルします。 |
| [getError()](#getError--) | タスクが完了した後に利用可能なタスクエラーを取得します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 非同期タスクの進捗イベントハンドラを取得します。 |
| [getResult()](#getResult--) | このタスクの結果を取得します。 |
| [isBusy()](#isBusy--) | このタスクが現在実行中かどうかを示す値を取得します。 |
| [isCanceled()](#isCanceled--) | このタスクがキャンセルされたかどうかを示す値を取得します。 |
| [isFaulted()](#isFaulted--) | このタスクがエラー状態かどうかを示す値を取得します。 |
| [runAsync()](#runAsync--) | このタスクを実行します。 |
| [runAsync(int priority)](#runAsync-int-) | このタスクを実行します。 |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | 完了コールバックデリゲートを設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 非同期タスクの進捗イベントハンドラを設定します。 |
### abort() {#abort--}
```
public abstract void abort()
```


このタスクを中止します。タスクは直ちに完了しますが、内部のアンマネージリソースが解放されないリスクがあります。

### cancel() {#cancel--}
```
public abstract void cancel()
```


このタスクをキャンセルします。アルゴリズムを制御された停止によりタスクは安全に完了します。

### getError() {#getError--}
```
public abstract Throwable getError()
```


タスクが完了した後に利用可能なタスクエラーを取得します。

値: タスクエラー。

**Returns:**
java.lang.Throwable - タスクが完了した後に利用可能なタスクエラー。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


非同期タスクの進捗イベントハンドラを取得します。

値: 非同期タスクの進捗イベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


このタスクの結果を取得します。

値: このタスクの結果。

**Returns:**
java.lang.Object - このタスクの結果。
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


このタスクが現在実行中かどうかを示す値を取得します。

値: このタスクが現在実行中の場合は true、そうでない場合は false。

**Returns:**
boolean - このタスクが現在実行中かどうかを示す値。
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


このタスクがキャンセルされたかどうかを示す値を取得します。

値: このタスクがキャンセルされた場合は true、そうでない場合は false。

**Returns:**
boolean - このタスクがキャンセルされたかどうかを示す値。
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


このタスクがエラー状態かどうかを示す値を取得します。

値: このタスクがエラー状態の場合は true、そうでない場合は false。

**Returns:**
boolean - このタスクがエラー状態かどうかを示す値。
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


このタスクを実行します。

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


このタスクを実行します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 優先度 | int | スレッドの優先度。 |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


完了コールバックデリゲートを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | 完全なコールバック。 |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


非同期タスクの進捗イベントハンドラを設定します。

値: 非同期タスクの進捗イベントハンドラ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 非同期タスクの進行イベントハンドラ。 |

