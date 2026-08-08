---
title: "EventType"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Esta enumeración describe los posibles tipos de eventos de progreso que pueden ocurrir durante las operaciones de procesamiento de imágenes."
type: docs
weight: 11
url: /es/java/com.aspose.psd.progressmanagement/eventtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Esta enumeración describe los posibles tipos de eventos de progreso que pueden ocurrir durante las operaciones de procesamiento de imágenes.
## Campos

| Campo | Descripción |
| --- | --- |
| [Finalization](#Finalization) | La finalización de la operación |
| [Initialization](#Initialization) | La inicialización de la operación |
| [PreProcessing](#PreProcessing) | El preprocesamiento |
| [Processing](#Processing) | El procesamiento |
| [RelativeProgress](#RelativeProgress) | Progreso relativo de la etapa actual del procesamiento de la operación |
| [StageChange](#StageChange) | La siguiente etapa de la operación comenzó |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Finalization {#Finalization}
```
public static final EventType Finalization
```


La finalización de la operación

### Initialization {#Initialization}
```
public static final EventType Initialization
```


La inicialización de la operación

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


El preprocesamiento

### Processing {#Processing}
```
public static final EventType Processing
```


El procesamiento

### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Progreso relativo de la etapa actual del procesamiento de la operación

### StageChange {#StageChange}
```
public static final EventType StageChange
```


La siguiente etapa de la operación comenzó

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static EventType valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype)
### values() {#values--}
```
public static EventType[] values()
```




**Returns:**
com.aspose.psd.progressmanagement.EventType[]
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

