---
title: InterruptMonitor
second_title: Aspose.PSD for Java API Reference
description: Represents information about interruption.
type: docs
weight: 10
url: /java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Represents information about interruption.
## Constructors

| Constructor | Description |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initializes a new instance of the  InterruptMonitor  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Gets the IInterruptMonitor instance which is unique for each thread. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Sends a request to interrupt operations. |
| [isInterrupted()](#isInterrupted--) | Gets the value indicating whether operations should be interrupted. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Returns  true  if interrupt monitor for current thread exists and it was interrupted otherwise  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Sets the IInterruptMonitor instance which is unique for each thread. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initializes a new instance of the  InterruptMonitor  class.

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
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Gets the IInterruptMonitor instance which is unique for each thread.

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


Sends a request to interrupt operations.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Gets the value indicating whether operations should be interrupted.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Returns  true  if interrupt monitor for current thread exists and it was interrupted otherwise  false .

**Returns:**
boolean -  true  if interrupt monitor for current thread exists and it was interrupted otherwise  false .
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


Sets the IInterruptMonitor instance which is unique for each thread.

**Parameters:**
| Parameter | Type | Description |
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

