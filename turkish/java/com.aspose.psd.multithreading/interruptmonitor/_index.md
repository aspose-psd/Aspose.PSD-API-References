---
title: "InterruptMonitor"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kesinti hakkında bilgiyi temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Kesinti hakkında bilgiyi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | InterruptMonitor sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | İşlemleri kesmek için bir istek gönderir. |
| [isInterrupted()](#isInterrupted--) | İşlemlerin kesilmesi gerekip gerekmediğini gösteren değeri alır. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Geçerli iş parçacığı için kesinti izleyicisi mevcut ve kesintiye uğramışsa true döndürür, aksi takdirde false döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | boolean - geçerli iş parçacığı için kesinti izleyicisi mevcut ve kesintiye uğramışsa true, aksi takdirinde false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


InterruptMonitor sınıfının yeni bir örneğini başlatır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır.

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


İşlemleri kesmek için bir istek gönderir.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


İşlemlerin kesilmesi gerekip gerekmediğini gösteren değeri alır.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Geçerli iş parçacığı için kesinti izleyicisi mevcut ve kesintiye uğramışsa true döndürür, aksi takdirde false döndürür.

**Returns:**
LayerStateEffects
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


boolean - geçerli iş parçacığı için kesinti izleyicisi mevcut ve kesintiye uğramışsa true, aksi takdirinde false.

**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

