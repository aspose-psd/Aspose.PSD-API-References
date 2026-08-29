---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD 的 Java API 参考"
description: "此类表示图像加载/保存/导出操作进度的信息，可在外部应用程序中用于向最终用户显示转换进度"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

此类表示图像加载/保存/导出操作进度的信息，可在外部应用程序中用于向最终用户显示转换进度。
## Methods

| Method | 描述 |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | 添加进度事件处理程序。 |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取事件的描述 |
| [getEventType()](#getEventType--) | 获取事件的类型。 |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | 获取最新的进度事件处理程序。 |
| [getMaxValue()](#getMaxValue--) | 获取上限进度值。 |
| [getValue()](#getValue--) | 获取当前进度值。 |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 指示进度。 |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | 指示进度。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | 上限进度值。 |
| [setValue_internalized(int value)](#setValue-internalized-int-) | 当前进度值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


添加进度事件处理程序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 进度事件处理程序。 |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 总计 | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


获取事件的描述

值：描述。

**Returns:**
java.lang.String - 事件的描述
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


获取事件的类型。

值：事件的类型。

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


获取最新的进度事件处理程序。

值：最新的进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


获取上限进度值。

值：上限进度值。

**Returns:**
int - 上限进度值。
### getValue() {#getValue--}
```
public final int getValue()
```


获取当前进度值。

值：进度值。

**Returns:**
int - 当前进度值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


指示进度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 事件的类型。 |

**Returns:**
boolean - 如果成功则为 true，否则为 false
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


指示进度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 事件的类型。 |
| 值 | int | 该值。 |

**Returns:**
boolean - 如果成功则为 true，否则为 false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


上限进度值。

值：上限进度值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 上限进度值。 |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


当前进度值。

值：进度值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 当前进度值。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

