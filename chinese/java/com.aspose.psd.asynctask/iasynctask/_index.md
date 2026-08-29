---
title: "IAsyncTask"
second_title: "Aspose.PSD 的 Java API 参考"
description: "异步任务。"
type: docs
weight: 16
url: /zh/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

异步任务。
## Methods

| Method | 描述 |
| --- | --- |
| [abort()](#abort--) | 中止此任务。 |
| [cancel()](#cancel--) | 取消此任务。 |
| [getError()](#getError--) | 获取任务错误，该错误在任务完成后可用。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取异步任务的进度事件处理程序。 |
| [getResult()](#getResult--) | 获取此任务的结果。 |
| [isBusy()](#isBusy--) | 获取指示此任务当前是否正在运行的值。 |
| [isCanceled()](#isCanceled--) | 获取指示此任务是否已被取消的值。 |
| [isFaulted()](#isFaulted--) | 获取指示此任务是否已出现错误的值。 |
| [runAsync()](#runAsync--) | 运行此任务。 |
| [runAsync(int priority)](#runAsync-int-) | 运行此任务。 |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | 设置完成回调委托。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 设置异步任务的进度事件处理程序。 |
### abort() {#abort--}
```
public abstract void abort()
```


中止此任务。任务会立即完成，但可能不会释放内部非托管资源。

### cancel() {#cancel--}
```
public abstract void cancel()
```


取消此任务。任务通过受控停止算法安全完成。

### getError() {#getError--}
```
public abstract Throwable getError()
```


获取任务错误，该错误在任务完成后可用。

值：任务错误。

**Returns:**
java.lang.Throwable - 任务完成后可用的任务错误。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


获取异步任务的进度事件处理程序。

值：异步任务的进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


获取此任务的结果。

值：此任务的结果。

**Returns:**
java.lang.Object - 此任务的结果。
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


获取指示此任务当前是否正在运行的值。

值：  true  如果此任务当前正在运行；否则，  false 。

**Returns:**
boolean - 指示此任务当前是否正在运行的值。
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


获取指示此任务是否已被取消的值。

值：  true  如果此任务已被取消；否则，  false 。

**Returns:**
boolean - 指示此任务是否已被取消的值。
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


获取指示此任务是否已出现错误的值。

值：  true  如果此任务出现错误；否则，  false 。

**Returns:**
boolean - 指示此任务是否出现错误的值。
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


运行此任务。

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


运行此任务。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 优先级 | int | 线程的优先级。 |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


设置完成回调委托。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | 完成回调。 |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


设置异步任务的进度事件处理程序。

值：异步任务的进度事件处理程序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 异步任务的进度事件处理程序。 |

