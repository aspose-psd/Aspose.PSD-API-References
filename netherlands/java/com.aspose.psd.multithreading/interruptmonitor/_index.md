---
title: "InterruptMonitor"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt informatie over onderbreking voor."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Stelt informatie over onderbreking voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initialiseert een nieuw exemplaar van de InterruptMonitor-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Haalt de IInterruptMonitor‑instantie op die uniek is voor elke thread. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Stuurt een verzoek om bewerkingen te onderbreken. |
| [isInterrupted()](#isInterrupted--) | Haalt de waarde op die aangeeft of bewerkingen onderbroken moeten worden. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Retourneert  true  als de interruptmonitor voor de huidige thread bestaat en onderbroken is, anders  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Stelt de IInterruptMonitor‑instantie in die uniek is voor elke thread. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initialiseert een nieuw exemplaar van de InterruptMonitor-klasse.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de IInterruptMonitor‑instantie op die uniek is voor elke thread.

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


Stuurt een verzoek om bewerkingen te onderbreken.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Haalt de waarde op die aangeeft of bewerkingen onderbroken moeten worden.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Retourneert  true  als de interruptmonitor voor de huidige thread bestaat en onderbroken is, anders  false .

**Returns:**
boolean -  true  als de interruptmonitor voor de huidige thread bestaat en onderbroken is, anders  false .
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


Stelt de IInterruptMonitor‑instantie in die uniek is voor elke thread.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

