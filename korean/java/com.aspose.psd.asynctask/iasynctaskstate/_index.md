---
title: "IAsyncTaskState"
second_title: "Java용 Aspose.PSD API 참조"
description: "비동기 작업의 상태에 대한 접근을 제공합니다."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

비동기 작업의 상태에 대한 접근을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getProgress()](#getProgress--) | 비동기 작업의 진행률을 가져옵니다. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | 진행률 최대 값을 증가시킵니다. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | 비동기 작업의 진행률을 설정합니다. |
| [isCanceled()](#isCanceled--) | 비동기 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


비동기 작업의 진행률을 가져옵니다.

값: 비동기 작업의 진행률.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


진행률 최대 값을 증가시킵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 증가 값. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


비동기 작업의 진행률을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 진행 상태. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


비동기 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다.

값: 비동기 작업이 취소된 경우 true; 그렇지 않으면 false.

**Returns:**
boolean - 비동기 작업이 취소되었는지 여부를 나타내는 값.
