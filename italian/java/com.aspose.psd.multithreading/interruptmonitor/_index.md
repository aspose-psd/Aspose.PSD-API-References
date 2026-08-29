---
title: "InterruptMonitor"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta informazioni sull'interruzione."
type: docs
weight: 10
url: /it/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Rappresenta informazioni sull'interruzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Inizializza una nuova istanza della classe InterruptMonitor. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Ottiene l'istanza IInterruptMonitor che è unica per ogni thread. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Invia una richiesta per interrompere le operazioni. |
| [isInterrupted()](#isInterrupted--) | Ottiene il valore che indica se le operazioni devono essere interrotte. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Restituisce true se il monitor di interruzione per il thread corrente esiste ed è stato interrotto, altrimenti false. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Imposta l'istanza IInterruptMonitor che è unica per ogni thread. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Inizializza una nuova istanza della classe InterruptMonitor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene l'istanza IInterruptMonitor che è unica per ogni thread.

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


Invia una richiesta per interrompere le operazioni.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Ottiene il valore che indica se le operazioni devono essere interrotte.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Restituisce true se il monitor di interruzione per il thread corrente esiste ed è stato interrotto, altrimenti false.

**Returns:**
boolean - true se il monitor di interruzione per il thread corrente esiste ed è stato interrotto, altrimenti false.
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


Imposta l'istanza IInterruptMonitor che è unica per ogni thread.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

