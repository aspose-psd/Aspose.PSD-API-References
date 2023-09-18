---
title: IAsyncTask
second_title: Aspose.PSD for Java API Reference
description: The asynchronous task.
type: docs
weight: 16
url: /java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

The asynchronous task.
## Methods

| Method | Description |
| --- | --- |
| [abort()](#abort--) | Aborts this task. |
| [cancel()](#cancel--) | Cancels this task. |
| [getError()](#getError--) | Gets the task error which is available after the task is completed. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets the progress event handler of the asynchronous task. |
| [getResult()](#getResult--) | Gets the result of this task. |
| [isBusy()](#isBusy--) | Gets a value indicating whether this task is currently running. |
| [isCanceled()](#isCanceled--) | Gets a value indicating whether this task was canceled. |
| [isFaulted()](#isFaulted--) | Gets a value indicating whether this task was faulted. |
| [runAsync()](#runAsync--) | Runs this task. |
| [runAsync(int priority)](#runAsync-int-) | Runs this task. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Sets the complete callback delegate. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Sets the progress event handler of the asynchronous task. |
### abort() {#abort--}
```
public abstract void abort()
```


Aborts this task. The task is completed immediately, with the risk of not freeing internal unmanaged resources.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Cancels this task. The task is completed safely by the controlled stopping of the algorithm.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Gets the task error which is available after the task is completed.

Value: The task error.

**Returns:**
java.lang.Throwable - the task error which is available after the task is completed.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Gets the progress event handler of the asynchronous task.

Value: The progress event handler of the asynchronous task.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Gets the result of this task.

Value: The result of this task.

**Returns:**
java.lang.Object - the result of this task.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Gets a value indicating whether this task is currently running.

Value:  true  if this task is currently running; otherwise,  false .

**Returns:**
boolean - a value indicating whether this task is currently running.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Gets a value indicating whether this task was canceled.

Value:  true  if this task was canceled; otherwise,  false .

**Returns:**
boolean - a value indicating whether this task was canceled.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Gets a value indicating whether this task was faulted.

Value:  true  if this task was faulted; otherwise,  false .

**Returns:**
boolean - a value indicating whether this task was faulted.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Runs this task.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Runs this task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| priority | int | The thread priority. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Sets the complete callback delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | The complete callback. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Sets the progress event handler of the asynchronous task.

Value: The progress event handler of the asynchronous task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | the progress event handler of the asynchronous task. |

