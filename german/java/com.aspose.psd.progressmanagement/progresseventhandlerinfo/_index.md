---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Diese Klasse repräsentiert Informationen über den Fortschritt von Bildlade-/Speicher-/Exportvorgängen, die in einer externen Anwendung verwendet werden können, um den Konvertierungsfortschritt dem Endbenutzer anzuzeigen"
type: docs
weight: 10
url: /de/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Diese Klasse stellt Informationen über den Fortschritt von Bildlade-/Speicher-/Exportvorgängen bereit, die in einer externen Anwendung verwendet werden können, um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Fügt den Fortschrittsereignis-Handler hinzu. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Liefert die Beschreibung des Ereignisses |
| [getEventType()](#getEventType--) | Liefert den Typ des Ereignisses. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Liefert den neuesten Fortschrittsereignis-Handler. |
| [getMaxValue()](#getMaxValue--) | Liefert die obere Grenze des Fortschrittswertes. |
| [getValue()](#getValue--) | Liefert den aktuellen Fortschrittswert. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Zeigt den Fortschritt an. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Zeigt den Fortschritt an. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Die obere Grenze des Fortschrittswertes. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Aktueller Fortschrittswert. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Fügt den Fortschrittsereignis-Handler hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Der Fortschrittsereignis-Handler. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gesamt | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Liefert die Beschreibung des Ereignisses

Value: Die Beschreibung.

**Returns:**
java.lang.String - die Beschreibung des Ereignisses
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Liefert den Typ des Ereignisses.

Value: Der Typ des Ereignisses.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Liefert den neuesten Fortschrittsereignis-Handler.

Value: Der letzte Fortschritt-Ereignis-Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Liefert die obere Grenze des Fortschrittswertes.

Value: Die obere Grenze des Fortschrittswerts.

**Returns:**
int - die obere Grenze des Fortschrittswerts.
### getValue() {#getValue--}
```
public final int getValue()
```


Liefert den aktuellen Fortschrittswert.

Value: Der Fortschrittswert.

**Returns:**
int - aktueller Fortschrittswert.
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


Zeigt den Fortschritt an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Typ des Ereignisses. |

**Returns:**
boolean - true, wenn erfolgreich, false sonst
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Zeigt den Fortschritt an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Typ des Ereignisses. |
| Wert | int | Der Wert. |

**Returns:**
boolean - true, wenn erfolgreich, false sonst
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


Die obere Grenze des Fortschrittswertes.

Value: Die obere Grenze des Fortschrittswerts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die obere Grenze des Fortschrittswerts. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Aktueller Fortschrittswert.

Value: Der Fortschrittswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | aktueller Fortschrittswert. |

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

