---
title: "InterruptMonitor"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili informasi tentang interupsi."
type: docs
weight: 10
url: /id/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Mewakili informasi tentang interupsi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Menginisialisasi instance baru dari kelas  InterruptMonitor  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Mendapatkan instance IInterruptMonitor yang unik untuk setiap thread. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Mengirim permintaan untuk menghentikan operasi. |
| [isInterrupted()](#isInterrupted--) | Mendapatkan nilai yang menunjukkan apakah operasi harus dihentikan. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Mengembalikan  true  jika monitor interupsi untuk thread saat ini ada dan telah dihentikan, jika tidak  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Mengatur instance IInterruptMonitor yang unik untuk setiap thread. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Menginisialisasi instance baru dari kelas  InterruptMonitor  .

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan instance IInterruptMonitor yang unik untuk setiap thread.

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


Mengirim permintaan untuk menghentikan operasi.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Mendapatkan nilai yang menunjukkan apakah operasi harus dihentikan.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Mengembalikan  true  jika monitor interupsi untuk thread saat ini ada dan telah dihentikan, jika tidak  false .

**Returns:**
boolean -  true  jika monitor interupsi untuk thread saat ini ada dan telah dihentikan, jika tidak  false .
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


Mengatur instance IInterruptMonitor yang unik untuk setiap thread.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

