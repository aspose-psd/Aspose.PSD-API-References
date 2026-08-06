---
title: "InterruptMonitor"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示中断信息。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

表示中断信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | 初始化一个新的  InterruptMonitor  类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | 获取每个线程唯一的 IInterruptMonitor 实例。 |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | 发送请求以中断操作。 |
| [isInterrupted()](#isInterrupted--) | 获取指示是否应中断操作的值。 |
| [isThreadInterrupted()](#isThreadInterrupted--) | 如果当前线程的中断监视器存在且已被中断，则返回  true ，否则返回  false 。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | 设置每个线程唯一的 IInterruptMonitor 实例。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


初始化一个新的  InterruptMonitor  类实例。

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
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


获取每个线程唯一的 IInterruptMonitor 实例。

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


发送请求以中断操作。

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


获取指示是否应中断操作的值。

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


如果当前线程的中断监视器存在且已被中断，则返回  true ，否则返回  false 。

**Returns:**
boolean -  true  如果当前线程的中断监视器存在且已被中断，否则为  false 。
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


设置每个线程唯一的 IInterruptMonitor 实例。

**Parameters:**
| Parameter | Type | 描述 |
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

