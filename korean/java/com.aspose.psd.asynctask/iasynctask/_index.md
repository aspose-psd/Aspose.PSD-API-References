---
title: "IAsyncTask"
second_title: "Java용 Aspose.PSD API 참조"
description: "비동기 작업."
type: docs
weight: 16
url: /ko/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

비동기 작업.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [abort()](#abort--) | 이 작업을 중단합니다. |
| [cancel()](#cancel--) | 이 작업을 취소합니다. |
| [getError()](#getError--) | 작업이 완료된 후 사용할 수 있는 작업 오류를 가져옵니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 비동기 작업의 진행 이벤트 핸들러를 가져옵니다. |
| [getResult()](#getResult--) | 이 작업의 결과를 가져옵니다. |
| [isBusy()](#isBusy--) | 이 작업이 현재 실행 중인지 여부를 나타내는 값을 가져옵니다. |
| [isCanceled()](#isCanceled--) | 이 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다. |
| [isFaulted()](#isFaulted--) | 이 작업에 오류가 발생했는지 여부를 나타내는 값을 가져옵니다. |
| [runAsync()](#runAsync--) | 이 작업을 실행합니다. |
| [runAsync(int priority)](#runAsync-int-) | 이 작업을 실행합니다. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | 완료 콜백 대리자를 설정합니다. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 비동기 작업의 진행 이벤트 핸들러를 설정합니다. |
### abort() {#abort--}
```
public abstract void abort()
```


이 작업을 중단합니다. 작업이 즉시 완료되며 내부 비관리 리소스가 해제되지 않을 위험이 있습니다.

### cancel() {#cancel--}
```
public abstract void cancel()
```


이 작업을 취소합니다. 알고리즘을 제어된 방식으로 중지하여 작업이 안전하게 완료됩니다.

### getError() {#getError--}
```
public abstract Throwable getError()
```


작업이 완료된 후 사용할 수 있는 작업 오류를 가져옵니다.

값: 작업 오류.

**Returns:**
java.lang.Throwable - 작업이 완료된 후 사용할 수 있는 작업 오류.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


비동기 작업의 진행 이벤트 핸들러를 가져옵니다.

값: 비동기 작업의 진행 이벤트 핸들러.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


이 작업의 결과를 가져옵니다.

값: 이 작업의 결과.

**Returns:**
java.lang.Object - 이 작업의 결과.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


이 작업이 현재 실행 중인지 여부를 나타내는 값을 가져옵니다.

값: 이 작업이 현재 실행 중이면 true, 그렇지 않으면 false.

**Returns:**
boolean - 이 작업이 현재 실행 중인지 여부를 나타내는 값.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


이 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다.

값: 이 작업이 취소되었으면 true, 그렇지 않으면 false.

**Returns:**
boolean - 이 작업이 취소되었는지 여부를 나타내는 값.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


이 작업에 오류가 발생했는지 여부를 나타내는 값을 가져옵니다.

값: 이 작업에 오류가 발생했으면 true, 그렇지 않으면 false.

**Returns:**
boolean - 이 작업에 오류가 발생했는지 여부를 나타내는 값.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


이 작업을 실행합니다.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


이 작업을 실행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 우선순위 | int | 스레드 우선순위. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


완료 콜백 대리자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | 완료 콜백. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


비동기 작업의 진행 이벤트 핸들러를 설정합니다.

값: 비동기 작업의 진행 이벤트 핸들러.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 비동기 작업의 진행 이벤트 핸들러. |

