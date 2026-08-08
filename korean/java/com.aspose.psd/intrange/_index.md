---
title: "IntRange"
second_title: "Java용 Aspose.PSD API 참조"
description: "요소 시퀀스를 나타내는 클래스"
type: docs
weight: 62
url: /ko/java/com.aspose.psd/intrange/
---

**Inheritance:**
java.lang.Object
```
public class IntRange
```

요소 시퀀스를 나타내는 클래스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | IntRange 클래스의 새 인스턴스를 초기화합니다. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | IntRange 클래스의 새 인스턴스를 초기화합니다. |
| [IntRange(int[] range)](#IntRange-int---) | IntRange 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | 지정된 인덱스에서 하나의 항목 배열을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getRange()](#getRange--) | 범위를 가져옵니다. |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | 시작 위치에서 시작하는 int 요소들의 개수 범위를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRange(int[] value)](#setRange-int---) | 범위를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


IntRange 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시작 | int | 시작. |
| count | int | 개수. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


IntRange 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시작 | int | 시작. |
| count | int | 개수. |
| 델타 | int | 델타. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


IntRange 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 범위 | int[] | 범위. |

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
### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


지정된 인덱스에서 하나의 항목 배열을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 범위 인덱스. |

**Returns:**
int[] - System.Int32 배열
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getRange() {#getRange--}
```
public int[] getRange()
```


범위를 가져옵니다.

**Returns:**
int[] - 범위.
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


시작 위치에서 시작하는 int 요소들의 개수 범위를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시작 | int | 시작. |
| count | int | 개수. |
| 델타 | int | 델타. |

**Returns:**
int[] - 항목 배열
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


범위를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 범위. |

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

