---
title: "구성"
second_title: "Java용 Aspose.PSD API 참조"
description: "메모리 관리 전역 구성"
type: docs
weight: 10
url: /ko/java/com.aspose.psd.memorymanagement/configuration/
---

**Inheritance:**
java.lang.Object
```
public final class Configuration
```

메모리 관리 전역 구성
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | 내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Returns:**
int - 정의된 최대 허용 크기로, 모든 내부 버퍼에 대한 버퍼 크기 힌트입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 내부 버퍼 전체에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트. |

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

