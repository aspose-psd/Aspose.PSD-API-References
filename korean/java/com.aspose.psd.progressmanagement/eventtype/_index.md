---
title: "EventType"
second_title: "Java용 Aspose.PSD API 참조"
description: "이 열거형은 이미지 처리 작업 중에 발생할 수 있는 가능한 진행 이벤트 유형을 설명합니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.progressmanagement/eventtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

이 열거형은 이미지 처리 작업 중에 발생할 수 있는 가능한 진행 이벤트 유형을 설명합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Finalization](#Finalization) | 작업의 마무리 |
| [Initialization](#Initialization) | 작업의 초기화 |
| [PreProcessing](#PreProcessing) | 전처리 |
| [Processing](#Processing) | 처리 |
| [RelativeProgress](#RelativeProgress) | 작업 처리 현재 단계의 상대 진행률 |
| [StageChange](#StageChange) | 작업의 다음 단계가 시작되었습니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Finalization {#Finalization}
```
public static final EventType Finalization
```


작업의 마무리

### Initialization {#Initialization}
```
public static final EventType Initialization
```


작업의 초기화

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


전처리

### Processing {#Processing}
```
public static final EventType Processing
```


처리

### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


작업 처리 현재 단계의 상대 진행률

### StageChange {#StageChange}
```
public static final EventType StageChange
```


작업의 다음 단계가 시작되었습니다

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static EventType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype)
### values() {#values--}
```
public static EventType[] values()
```




**Returns:**
com.aspose.psd.progressmanagement.EventType[]
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

