---
title: "ResourceEvent"
second_title: "Aspose.PSD för Java API-referens"
description: "Innehåller dimensioner för ett ritat objekt."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Innehåller dimensioner för ett ritat objekt.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initialiserar en ny instans av klassen  ResourceEvent  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Lägger till den angivna nyckeln. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Hämtar åtgärden. |
| [getActionDate()](#getActionDate--) | Hämtar eller anger åtgärdsdatumet. |
| [getChanged()](#getChanged--) | Hämtar den semikolonavgränsade listan över de delar av resursen som har ändrats sedan föregående händelsehistorik. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Hämtar värdet för xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Hämtar standardnamnutrymmets URI. |
| [getParameters()](#getParameters--) | Hämtar eller anger den ytterligare beskrivningen av åtgärden. |
| [getPrefix()](#getPrefix--) | Hämtar prefixet. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Hämtar eller anger namnet på programvaruagenten. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar det stränginnehållande värdet i XMP-format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Anger åtgärden. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Hämtar eller anger åtgärdsdatumet. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Anger den semikolonavgränsade listan över de delar av resursen som har ändrats sedan föregående händelsehistorik. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Hämtar eller anger värdet för xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Hämtar eller anger den ytterligare beskrivningen av åtgärden. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Hämtar eller anger namnet på programvaruagenten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initialiserar en ny instans av klassen  ResourceEvent  .

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Lägger till den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.Object | Värdet att lägga till i. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Hämtar åtgärden.

Definierade värden är: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nya värden bör vara verb i dåtid.

**Returns:**
java.lang.String - Åtgärden.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Hämtar eller anger åtgärdsdatumet.

**Returns:**
java.util.Date - Åtgärdsdatumet.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Hämtar den semikolonavgränsade listan över de delar av resursen som har ändrats sedan föregående händelsehistorik.

**Returns:**
java.lang.String - Den semikolonavgränsade listan över de delar av resursen som har ändrats sedan föregående händelsehistorik.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Hämtar värdet för xmpMM:InstanceId.

**Returns:**
java.util.UUID - Värdet för xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Hämtar standardnamnutrymmets URI.

**Returns:**
java.lang.String - Standardnamnutrymmes URI.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Hämtar eller anger den ytterligare beskrivningen av åtgärden.

Värde: Den ytterligare beskrivningen av åtgärden.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Hämtar prefixet.

**Returns:**
java.lang.String - Prefixet.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Hämtar eller anger namnet på programvaruagenten.

**Returns:**
java.lang.String - Programvaruagentens namn.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Hämtar det stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Anger åtgärden.

Definierade värden är: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nya värden bör vara verb i dåtid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Åtgärden. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Hämtar eller anger åtgärdsdatumet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date | Åtgärdens datum. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Anger den semikolonavgränsade listan över de delar av resursen som har ändrats sedan föregående händelsehistorik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Den semikolonavgränsade listan över de delar av resursen som har ändrats sedan föregående händelsehistorik. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Hämtar eller anger värdet för xmpMM:InstanceId.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID | Värdet för xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Hämtar eller anger den ytterligare beskrivningen av åtgärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Den ytterligare beskrivningen av åtgärden. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Hämtar eller anger namnet på programvaruagenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Programvaruagentens namn. |

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

