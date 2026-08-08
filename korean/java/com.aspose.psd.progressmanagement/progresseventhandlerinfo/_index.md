---
title: "ProgressEventHandlerInfo"
second_title: "Java용 Aspose.PSD API 참조"
description: "이 클래스는 외부 애플리케이션에서 변환 진행 상황을 최종 사용자에게 표시하기 위해 사용할 수 있는 이미지 로드/저장/내보내기 작업 진행에 대한 정보를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

이 클래스는 이미지 로드/저장/내보내기 작업 진행에 대한 정보를 나타내며, 외부 애플리케이션에서 최종 사용자에게 변환 진행 상황을 표시하는 데 사용할 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | 진행 이벤트 핸들러를 추가합니다. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 이벤트의 설명을 가져옵니다. |
| [getEventType()](#getEventType--) | 이벤트의 유형을 가져옵니다. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | 최신 진행 이벤트 핸들러를 가져옵니다. |
| [getMaxValue()](#getMaxValue--) | 상위 진행 값 한계를 가져옵니다. |
| [getValue()](#getValue--) | 현재 진행 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 진행을 나타냅니다. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | 진행을 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | 상위 진행 값 한계. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | 현재 진행 값. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


진행 이벤트 핸들러를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 진행 이벤트 핸들러. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 전체 | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


이벤트의 설명을 가져옵니다.

값: 설명.

**Returns:**
java.lang.String - 이벤트에 대한 설명
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


이벤트의 유형을 가져옵니다.

값: 이벤트의 유형.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


최신 진행 이벤트 핸들러를 가져옵니다.

값: 최신 진행 이벤트 핸들러.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


상위 진행 값 한계를 가져옵니다.

값: 상한 진행 값 제한.

**Returns:**
int - 상한 진행 값 제한.
### getValue() {#getValue--}
```
public final int getValue()
```


현재 진행 값을 가져옵니다.

값: 진행 값.

**Returns:**
int - 현재 진행 값.
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


진행을 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 이벤트 유형. |

**Returns:**
boolean - 성공이면 true, 그렇지 않으면 false
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


진행을 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | 이벤트 유형. |
| 값 | int | 값. |

**Returns:**
boolean - 성공이면 true, 그렇지 않으면 false
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


상위 진행 값 한계.

값: 상한 진행 값 제한.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 상한 진행 값 제한. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


현재 진행 값.

값: 진행 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 현재 진행 값. |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

