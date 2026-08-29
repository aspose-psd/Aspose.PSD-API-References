---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Deze klasse vertegenwoordigt informatie over de voortgang van beeld‑laden/‑opslaan/‑exportbewerkingen die kan worden gebruikt in een externe applicatie om de conversievoortgang aan de eindgebruiker te tonen."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Deze klasse vertegenwoordigt informatie over de voortgang van beeld laad-/opsla- en exportbewerkingen, die kan worden gebruikt in een externe applicatie om de conversievoortgang aan de eindgebruiker te tonen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Voegt de voortgangs‑eventhandler toe. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Verkrijgt de beschrijving van het event. |
| [getEventType()](#getEventType--) | Verkrijgt het type van het event. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Verkrijgt de nieuwste voortgangs‑eventhandler. |
| [getMaxValue()](#getMaxValue--) | Verkrijgt de bovenste limiet van de voortgangswaarde. |
| [getValue()](#getValue--) | Verkrijgt de huidige voortgangswaarde. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Geeft de voortgang aan. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Geeft de voortgang aan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | De bovenste limiet van de voortgangswaarde. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Huidige voortgangswaarde. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Voegt de voortgangs‑eventhandler toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | De voortgangs‑eventhandler. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| totaal | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Verkrijgt de beschrijving van het event.

Waarde: De beschrijving.

**Returns:**
java.lang.String - de beschrijving van het event
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Verkrijgt het type van het event.

Waarde: Het type van het event.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Verkrijgt de nieuwste voortgangs‑eventhandler.

Waarde: De nieuwste voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Verkrijgt de bovenste limiet van de voortgangswaarde.

Waarde: De bovenste limiet van de voortgangswaarde.

**Returns:**
int - de bovenste limiet van de voortgangswaarde.
### getValue() {#getValue--}
```
public final int getValue()
```


Verkrijgt de huidige voortgangswaarde.

Waarde: De voortgangswaarde.

**Returns:**
int - huidige voortgangswaarde.
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


Geeft de voortgang aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Type van het event. |

**Returns:**
boolean - true als succesvol, false anders
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Geeft de voortgang aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Type van het event. |
| waarde | int | De waarde. |

**Returns:**
boolean - true als succesvol, false anders
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


De bovenste limiet van de voortgangswaarde.

Waarde: De bovenste limiet van de voortgangswaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de bovenste voortgangswaarde limiet. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Huidige voortgangswaarde.

Waarde: De voortgangswaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | huidige voortgangswaarde. |

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

