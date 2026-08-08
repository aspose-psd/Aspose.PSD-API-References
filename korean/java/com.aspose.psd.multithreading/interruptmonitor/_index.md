---
title: "InterruptMonitor"
second_title: "Java용 Aspose.PSD API 참조"
description: "중단에 대한 정보를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

중단에 대한 정보를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | InterruptMonitor 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | 각 스레드마다 고유한 IInterruptMonitor 인스턴스를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | 작업을 중단하도록 요청을 보냅니다. |
| [isInterrupted()](#isInterrupted--) | 작업을 중단해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [isThreadInterrupted()](#isThreadInterrupted--) | interrupt monitor가 현재 스레드에 존재하고 중단된 경우 true 를 반환하고, 그렇지 않으면 false 를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | 각 스레드마다 고유한 IInterruptMonitor 인스턴스를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


InterruptMonitor 클래스의 새 인스턴스를 초기화합니다.

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
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


각 스레드마다 고유한 IInterruptMonitor 인스턴스를 가져옵니다.

**Returns:**
[IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### interrupt() {#interrupt--}
```
public void interrupt()
```


작업을 중단하도록 요청을 보냅니다.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


작업을 중단해야 하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


interrupt monitor가 현재 스레드에 존재하고 중단된 경우 true 를 반환하고, 그렇지 않으면 false 를 반환합니다.

**Returns:**
boolean - interrupt monitor가 현재 스레드에 존재하고 중단된 경우 true , 그렇지 않으면 false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


각 스레드마다 고유한 IInterruptMonitor 인스턴스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor) |  |

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

