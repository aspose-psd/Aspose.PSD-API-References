---
title: "InterruptMonitor"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar information om avbrott."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Representerar information om avbrott.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initierar en ny instans av klassen  InterruptMonitor . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Hämtar IInterruptMonitor-instansen som är unik för varje tråd. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Skickar en begäran om att avbryta operationer. |
| [isInterrupted()](#isInterrupted--) | Hämtar värdet som indikerar om operationer ska avbrytas. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Returnerar  true  om avbrottsmonitor för aktuell tråd finns och den avbröts, annars  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Ställer in IInterruptMonitor-instansen som är unik för varje tråd. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initierar en ny instans av klassen  InterruptMonitor .

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar IInterruptMonitor-instansen som är unik för varje tråd.

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


Skickar en begäran om att avbryta operationer.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Hämtar värdet som indikerar om operationer ska avbrytas.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Returnerar  true  om avbrottsmonitor för aktuell tråd finns och den avbröts, annars  false .

**Returns:**
boolean -  true  om avbrottsmonitor för aktuell tråd finns och den avbröts, annars  false .
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


Ställer in IInterruptMonitor-instansen som är unik för varje tråd.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

