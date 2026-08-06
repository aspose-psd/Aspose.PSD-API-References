---
title: "ResourceEvent"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Contenant les dimensions d'un objet dessiné."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Contenant les dimensions d'un objet dessiné.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initialise une nouvelle instance de la classe ResourceEvent. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Ajoute la clé spécifiée. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Obtient l'action. |
| [getActionDate()](#getActionDate--) | Obtient ou définit la date de l'action. |
| [getChanged()](#getChanged--) | Obtient la liste séparée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événement précédent. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Obtient la valeur de xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtient l'URI de l'espace de noms par défaut. |
| [getParameters()](#getParameters--) | Obtient ou définit la description supplémentaire de l'action. |
| [getPrefix()](#getPrefix--) | Obtient le préfixe. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Obtient ou définit le nom de l'agent logiciel. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Définit l'action. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Obtient ou définit la date de l'action. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Définit la liste séparée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événement précédent. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Obtient ou définit la valeur de xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Obtient ou définit la description supplémentaire de l'action. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Obtient ou définit le nom de l'agent logiciel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initialise une nouvelle instance de la classe ResourceEvent.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Ajoute la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| valeur | java.lang.Object | La valeur à ajouter à. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAction() {#getAction--}
```
public String getAction()
```


Obtient l'action.

Les valeurs définies sont : converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Les nouvelles valeurs doivent être des verbes au passé.

**Returns:**
java.lang.String - L'action.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Obtient ou définit la date de l'action.

**Returns:**
java.util.Date - La date de l'action.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Obtient la liste séparée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événement précédent.

**Returns:**
java.lang.String - La liste séparée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événement précédent.
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


Obtient la valeur de xmpMM:InstanceId.

**Returns:**
java.util.UUID - La valeur de xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtient l'URI de l'espace de noms par défaut.

**Returns:**
java.lang.String - L'URI d'espace de noms par défaut.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Obtient ou définit la description supplémentaire de l'action.

Valeur : La description supplémentaire de l'action.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtient le préfixe.

**Returns:**
java.lang.String - Le préfixe.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Obtient ou définit le nom de l'agent logiciel.

**Returns:**
java.lang.String - Le nom de l'agent logiciel.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.
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


Définit l'action.

Les valeurs définies sont : converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Les nouvelles valeurs doivent être des verbes au passé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | L'action. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Obtient ou définit la date de l'action.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date | La date de l'action. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Définit la liste séparée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événement précédent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La liste séparée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événement précédent. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Obtient ou définit la valeur de xmpMM:InstanceId.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID | La valeur de xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Obtient ou définit la description supplémentaire de l'action.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La description supplémentaire de l'action. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Obtient ou définit le nom de l'agent logiciel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom de l'agent logiciel. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

