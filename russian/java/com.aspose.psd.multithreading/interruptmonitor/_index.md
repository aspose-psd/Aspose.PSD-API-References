---
title: "InterruptMonitor"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет информацию о прерывании."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Представляет информацию о прерывании.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Инициализирует новый экземпляр класса  InterruptMonitor . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Получает экземпляр IInterruptMonitor, который уникален для каждого потока. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Отправляет запрос на прерывание операций. |
| [isInterrupted()](#isInterrupted--) | Получает значение, указывающее, следует ли прерывать операции. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Возвращает  true  если монитор прерываний для текущего потока существует и был прерван, иначе  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Устанавливает экземпляр IInterruptMonitor, который уникален для каждого потока. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Инициализирует новый экземпляр класса  InterruptMonitor .

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Получает экземпляр IInterruptMonitor, который уникален для каждого потока.

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


Отправляет запрос на прерывание операций.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Получает значение, указывающее, следует ли прерывать операции.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Возвращает  true  если монитор прерываний для текущего потока существует и был прерван, иначе  false .

**Returns:**
boolean -  true  если монитор прерываний для текущего потока существует и был прерван, иначе  false .
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


Устанавливает экземпляр IInterruptMonitor, который уникален для каждого потока.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

