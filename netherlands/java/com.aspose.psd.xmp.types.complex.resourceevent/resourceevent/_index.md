---
title: "ResourceEvent"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Bevat afmetingen voor een getekend object."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Bevat afmetingen voor een getekend object.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initialiseert een nieuw exemplaar van de  ResourceEvent  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Voegt de opgegeven sleutel toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Haalt de actie op. |
| [getActionDate()](#getActionDate--) | Haalt op of stelt de actiedatum in. |
| [getChanged()](#getChanged--) | Haalt de door puntkomma gescheiden lijst op van de delen van de bron die zijn gewijzigd sinds de vorige gebeurtenishistorie. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Haalt de waarde op van de xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Haalt de standaard namespace‑URI op. |
| [getParameters()](#getParameters--) | Haalt op of stelt de aanvullende beschrijving van de actie in. |
| [getPrefix()](#getPrefix--) | Haalt het voorvoegsel op. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Haalt op of stelt de naam van de software‑agent in. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Haalt de tekenreeksinhoud op in XMP-indeling. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Stelt de actie in. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Haalt op of stelt de actiedatum in. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Stelt de door puntkomma gescheiden lijst in van de delen van de bron die zijn gewijzigd sinds de vorige gebeurtenishistorie. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Haalt op of stelt de waarde van de xmpMM:InstanceId in. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Haalt op of stelt de aanvullende beschrijving van de actie in. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Haalt op of stelt de naam van de software‑agent in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initialiseert een nieuw exemplaar van de  ResourceEvent  klasse.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Voegt de opgegeven sleutel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is gekoppeld aan de toegevoegde waarde. |
| waarde | java.lang.Object | De waarde om aan toe te voegen. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Haalt de actie op.

Gedefinieerde waarden zijn: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nieuwe waarden moeten werkwoorden in de verleden tijd zijn.

**Returns:**
java.lang.String - De actie.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Haalt op of stelt de actiedatum in.

**Returns:**
java.util.Date - De actiedatum.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Haalt de door puntkomma gescheiden lijst op van de delen van de bron die zijn gewijzigd sinds de vorige gebeurtenishistorie.

**Returns:**
java.lang.String - De door puntkomma gescheiden lijst van de delen van de bron die zijn gewijzigd sinds de vorige gebeurtenishistorie.
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


Haalt de waarde op van de xmpMM:InstanceId.

**Returns:**
java.util.UUID - De waarde van de xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Haalt de standaard namespace‑URI op.

**Returns:**
java.lang.String - De standaard namespace-URI.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Haalt op of stelt de aanvullende beschrijving van de actie in.

Waarde: De aanvullende beschrijving van de actie.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Haalt het voorvoegsel op.

**Returns:**
java.lang.String - De prefix.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Haalt op of stelt de naam van de software‑agent in.

**Returns:**
java.lang.String - De naam van de software‑agent.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Haalt de tekenreeksinhoud op in XMP-indeling.

**Returns:**
java.lang.String - Retourneert de tekenreeksinhoud in XMP-indeling.
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


Stelt de actie in.

Gedefinieerde waarden zijn: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nieuwe waarden moeten werkwoorden in de verleden tijd zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De actie. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Haalt op of stelt de actiedatum in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date | De datum van de actie. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Stelt de door puntkomma gescheiden lijst in van de delen van de bron die zijn gewijzigd sinds de vorige gebeurtenishistorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De door puntkomma gescheiden lijst van de delen van de bron die zijn gewijzigd sinds de vorige gebeurtenishistorie. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Haalt op of stelt de waarde van de xmpMM:InstanceId in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID | De waarde van de xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Haalt op of stelt de aanvullende beschrijving van de actie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De aanvullende beschrijving van de actie. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Haalt op of stelt de naam van de software‑agent in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De naam van de software‑agent. |

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

