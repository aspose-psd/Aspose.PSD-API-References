---
title: "InterruptMonitor"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa información sobre interrupción."
type: docs
weight: 10
url: /es/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Representa información sobre interrupción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Inicializa una nueva instancia de la clase InterruptMonitor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Obtiene la instancia IInterruptMonitor que es única para cada hilo. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Envía una solicitud para interrumpir las operaciones. |
| [isInterrupted()](#isInterrupted--) | Obtiene el valor que indica si las operaciones deben interrumpirse. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Devuelve true si el monitor de interrupción para el hilo actual existe y fue interrumpido; de lo contrario, false. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Establece la instancia IInterruptMonitor que es única para cada hilo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Inicializa una nueva instancia de la clase InterruptMonitor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene la instancia IInterruptMonitor que es única para cada hilo.

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


Envía una solicitud para interrumpir las operaciones.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Obtiene el valor que indica si las operaciones deben interrumpirse.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Devuelve true si el monitor de interrupción para el hilo actual existe y fue interrumpido; de lo contrario, false.

**Returns:**
boolean - true si el monitor de interrupción para el hilo actual existe y fue interrumpido; de lo contrario, false.
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


Establece la instancia IInterruptMonitor que es única para cada hilo.

**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

