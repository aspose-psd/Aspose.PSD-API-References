---
title: "ResourceEvent"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Enthält Abmessungen für ein gezeichnetes Objekt."
type: docs
weight: 10
url: /de/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Enthält Abmessungen für ein gezeichnetes Objekt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initialisiert eine neue Instanz der  ResourceEvent  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Fügt den angegebenen Schlüssel hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Liest die Aktion. |
| [getActionDate()](#getActionDate--) | Liest oder setzt das Aktionsdatum. |
| [getChanged()](#getChanged--) | Liest die durch Semikolon getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Liest den Wert von xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Liest den Standard-Namespace-URI. |
| [getParameters()](#getParameters--) | Liest oder setzt die zusätzliche Beschreibung der Aktion. |
| [getPrefix()](#getPrefix--) | Liest das Präfix. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Liest oder setzt den Namen des Software-Agenten. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenkettenwert im XMP-Format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Setzt die Aktion. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Liest oder setzt das Aktionsdatum. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Setzt die durch Semikolon getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Liest oder setzt den Wert von xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Liest oder setzt die zusätzliche Beschreibung der Aktion. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Liest oder setzt den Namen des Software-Agenten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initialisiert eine neue Instanz der  ResourceEvent  Klasse.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Fügt den angegebenen Schlüssel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.Object | Der Wert, zu dem hinzugefügt werden soll. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Liest die Aktion.

Definierte Werte sind: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Neue Werte sollten Verben im Präteritum sein.

**Returns:**
java.lang.String - Die Aktion.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Liest oder setzt das Aktionsdatum.

**Returns:**
java.util.Date - Das Aktionsdatum.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Liest die durch Semikolon getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden.

**Returns:**
java.lang.String - Die durch Semikolon getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden.
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


Liest den Wert von xmpMM:InstanceId.

**Returns:**
java.util.UUID - Der Wert von xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Liest den Standard-Namespace-URI.

**Returns:**
java.lang.String - Der Standard-Namespace-URI.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Liest oder setzt die zusätzliche Beschreibung der Aktion.

Wert: Die zusätzliche Beschreibung der Aktion.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Liest das Präfix.

**Returns:**
java.lang.String - Das Präfix.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Liest oder setzt den Namen des Software-Agenten.

**Returns:**
java.lang.String - Der Name des Software-Agenten.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenkettenwert im XMP-Format.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
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


Setzt die Aktion.

Definierte Werte sind: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Neue Werte sollten Verben im Präteritum sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die Aktion. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Liest oder setzt das Aktionsdatum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date | Das Aktionsdatum. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Setzt die durch Semikolon getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die durch Semikolons getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisverlauf geändert wurden. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Liest oder setzt den Wert von xmpMM:InstanceId.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID | Der Wert von xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Liest oder setzt die zusätzliche Beschreibung der Aktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die zusätzliche Beschreibung der Aktion. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Liest oder setzt den Namen des Software-Agenten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Name des Software-Agenten. |

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

