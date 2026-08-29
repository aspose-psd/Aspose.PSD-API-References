---
title: "EventType"
second_title: "Aspose.PSD för Java API-referens"
description: "Denna enum beskriver möjliga typer av framstegshändelser som kan inträffa under bildbehandlingsoperationer."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.progressmanagement/eventtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Denna enum beskriver möjliga typer av framstegshändelser som kan inträffa under bildbehandlingsoperationer.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Finalization](#Finalization) | Slutförandet av operationen |
| [Initialization](#Initialization) | Initieringen av operationen |
| [PreProcessing](#PreProcessing) | Förbehandlingen |
| [Processing](#Processing) | Bearbetningen |
| [RelativeProgress](#RelativeProgress) | Relativt framsteg för nuvarande steg i operationens bearbetning |
| [StageChange](#StageChange) | Nästa steg i operationen har startat |
## Metoder

| Metod | Beskrivning |
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


Slutförandet av operationen

### Initialization {#Initialization}
```
public static final EventType Initialization
```


Initieringen av operationen

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


Förbehandlingen

### Processing {#Processing}
```
public static final EventType Processing
```


Bearbetningen

### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Relativt framsteg för nuvarande steg i operationens bearbetning

### StageChange {#StageChange}
```
public static final EventType StageChange
```


Nästa steg i operationen har startat

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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

