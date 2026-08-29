---
title: "InterruptMonitor"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente les informations sur l'interruption."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Représente les informations sur l'interruption.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initialise une nouvelle instance de la classe  InterruptMonitor  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Obtient l'instance IInterruptMonitor qui est unique pour chaque thread. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Envoie une requête pour interrompre les opérations. |
| [isInterrupted()](#isInterrupted--) | Obtient la valeur indiquant si les opérations doivent être interrompues. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Renvoie  true  si le moniteur d'interruption pour le thread actuel existe et a été interrompu, sinon  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Définit l'instance IInterruptMonitor qui est unique pour chaque thread. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initialise une nouvelle instance de la classe  InterruptMonitor  .

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient l'instance IInterruptMonitor qui est unique pour chaque thread.

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


Envoie une requête pour interrompre les opérations.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Obtient la valeur indiquant si les opérations doivent être interrompues.

**Returns:**
booléen
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Renvoie  true  si le moniteur d'interruption pour le thread actuel existe et a été interrompu, sinon  false .

**Returns:**
booléen -  true  si le moniteur d'interruption pour le thread actuel existe et a été interrompu, sinon  false .
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


Définit l'instance IInterruptMonitor qui est unique pour chaque thread.

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

