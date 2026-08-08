---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD för Java API-referens"
description: "Denna klass representerar information om framsteg för bildladdning-/sparande-/exportoperationer som kan användas i ett externt program för att visa konverteringsframsteg för slutanvändaren"
type: docs
weight: 10
url: /sv/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Denna klass representerar information om framsteg för bildladdning/sparande/exportoperationer, som kan användas i en extern applikation för att visa konverteringsframsteg för slutanvändaren.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Lägger till progress‑händelsehanteraren. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Hämtar beskrivningen av händelsen |
| [getEventType()](#getEventType--) | Hämtar typen av händelsen. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Hämtar den senaste progress‑händelsehanteraren. |
| [getMaxValue()](#getMaxValue--) | Hämtar den övre gränsen för progress‑värdet. |
| [getValue()](#getValue--) | Hämtar aktuellt progress‑värde. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Anger framstegen. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Anger framstegen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Den övre gränsen för progress‑värdet. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Aktuellt progress‑värde. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Lägger till progress‑händelsehanteraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Progress‑händelsehanteraren. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| totalt | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Hämtar beskrivningen av händelsen

Värde: Beskrivningen.

**Returns:**
java.lang.String - beskrivningen av händelsen
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Hämtar typen av händelsen.

Värde: Typen av händelsen.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Hämtar den senaste progress‑händelsehanteraren.

Värde: Den senaste progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Hämtar den övre gränsen för progress‑värdet.

Värde: Den övre gränsen för progress‑värdet.

**Returns:**
int - den övre gränsen för progress‑värdet.
### getValue() {#getValue--}
```
public final int getValue()
```


Hämtar aktuellt progress‑värde.

Värde: Progress‑värdet.

**Returns:**
int - aktuellt progress‑värde.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


Anger framstegen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Typ av händelsen. |

**Returns:**
boolean - sant om lyckat, falskt annars
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Anger framstegen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Typ av händelsen. |
| värde | int | Värdet. |

**Returns:**
boolean - sant om lyckat, falskt annars
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


Den övre gränsen för progress‑värdet.

Värde: Den övre gränsen för progress‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | det övre gränsvärdet för framstegsvärdet. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Aktuellt progress‑värde.

Värde: Progress‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | aktuellt framstegsvärde. |

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

