---
title: "IAsyncTaskState"
second_title: "Aspose.PSD 的 Java API 参考"
description: "提供对异步任务状态的访问。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

提供对异步任务状态的访问。
## Methods

| Method | 描述 |
| --- | --- |
| [getProgress()](#getProgress--) | 获取异步任务的进度。 |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | 递增进度的最大值。 |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | 设置异步任务的进度。 |
| [isCanceled()](#isCanceled--) | 获取指示异步任务是否已取消的值。 |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


获取异步任务的进度。

值：异步任务的进度。

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


递增进度的最大值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 增加值。 |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


设置异步任务的进度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 进度状态。 |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


获取指示异步任务是否已取消的值。

值：如果异步任务已取消则为 true；否则为 false。

**Returns:**
boolean - 指示异步任务是否已取消的值。
