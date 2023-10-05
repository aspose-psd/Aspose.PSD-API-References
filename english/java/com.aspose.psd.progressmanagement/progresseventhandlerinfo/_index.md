---
title: ProgressEventHandlerInfo
second_title: Aspose.PSD for Java API Reference
description: This class represents information about image load/save/export operations progress that can be used in external application to show conversion progress to end user
type: docs
weight: 10
url: /java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

This class represents information about image load/save/export operations progress, that can be used in external application to show conversion progress to end user
## Methods

| Method | Description |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Adds the progress event handler. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the description of the event |
| [getEventType()](#getEventType--) | Gets the type of the event. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Gets the latest progress event handler. |
| [getMaxValue()](#getMaxValue--) | Gets the upper progress value limit. |
| [getValue()](#getValue--) | Gets current progress value. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indicates the progress. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Indicates the progress. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | The upper progress value limit. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Current progress value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Adds the progress event handler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | The progress event handler. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| total | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the description of the event

Value: The description.

**Returns:**
java.lang.String - the description of the event
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Gets the type of the event.

Value: The type of the event.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Gets the latest progress event handler.

Value: The latest progress event handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Gets the upper progress value limit.

Value: The upper progress value limit.

**Returns:**
int - the upper progress value limit.
### getValue() {#getValue--}
```
public final int getValue()
```


Gets current progress value.

Value: The progress value.

**Returns:**
int - current progress value.
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


Indicates the progress.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Type of the event. |

**Returns:**
boolean - true if successful, false otherwise
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Indicates the progress.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Type of the event. |
| value | int | The value. |

**Returns:**
boolean - true if successful, false otherwise
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


The upper progress value limit.

Value: The upper progress value limit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the upper progress value limit. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Current progress value.

Value: The progress value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | current progress value. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

