---
title: "InterruptMonitor"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt Informationen über Unterbrechungen dar."
type: docs
weight: 10
url: /de/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Stellt Informationen über Unterbrechungen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initialisiert eine neue Instanz der  InterruptMonitor  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Liefert die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Sendet eine Anfrage, um Vorgänge zu unterbrechen. |
| [isInterrupted()](#isInterrupted--) | Liefert den Wert, der angibt, ob Vorgänge unterbrochen werden sollen. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Gibt  true  zurück, wenn ein interrupt monitor für den aktuellen Thread existiert und er unterbrochen wurde, andernfalls  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initialisiert eine neue Instanz der  InterruptMonitor  Klasse.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liefert die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist.

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


Sendet eine Anfrage, um Vorgänge zu unterbrechen.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Liefert den Wert, der angibt, ob Vorgänge unterbrochen werden sollen.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Gibt  true  zurück, wenn ein interrupt monitor für den aktuellen Thread existiert und er unterbrochen wurde, andernfalls  false .

**Returns:**
boolean -  true  wenn ein interrupt monitor für den aktuellen Thread existiert und er unterbrochen wurde, andernfalls  false .
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


Setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

