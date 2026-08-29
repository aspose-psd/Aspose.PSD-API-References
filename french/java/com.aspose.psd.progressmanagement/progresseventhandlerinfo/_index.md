---
title: "ProgressEventHandlerInfo"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Cette classe représente des informations sur la progression des opérations de chargement/enregistrement/export d'image qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Cette classe représente des informations sur la progression des opérations de chargement/enregistrement/exportation d'images, qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Ajoute le gestionnaire d'événement de progression. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtient la description de l'événement |
| [getEventType()](#getEventType--) | Obtient le type de l'événement. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Obtient le dernier gestionnaire d'événement de progression. |
| [getMaxValue()](#getMaxValue--) | Obtient la limite supérieure de la valeur de progression. |
| [getValue()](#getValue--) | Obtient la valeur de progression actuelle. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indique la progression. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Indique la progression. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | La limite supérieure de la valeur de progression. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Valeur de progression actuelle. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Ajoute le gestionnaire d'événement de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Le gestionnaire d'événement de progression. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| total | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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


Obtient la description de l'événement

Valeur : La description.

**Returns:**
java.lang.String - la description de l'événement
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Obtient le type de l'événement.

Valeur : Le type de l'événement.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Obtient le dernier gestionnaire d'événement de progression.

Valeur : Le gestionnaire d'événement de progression le plus récent.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Obtient la limite supérieure de la valeur de progression.

Valeur : La limite supérieure de la valeur de progression.

**Returns:**
int - la limite supérieure de la valeur de progression.
### getValue() {#getValue--}
```
public final int getValue()
```


Obtient la valeur de progression actuelle.

Valeur : La valeur de progression.

**Returns:**
int - valeur de progression actuelle.
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


Indique la progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Type de l'événement. |

**Returns:**
boolean - vrai si réussi, faux sinon
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Indique la progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Type de l'événement. |
| valeur | int | La valeur. |

**Returns:**
boolean - vrai si réussi, faux sinon
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


La limite supérieure de la valeur de progression.

Valeur : La limite supérieure de la valeur de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la limite supérieure de la valeur de progression. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Valeur de progression actuelle.

Valeur : La valeur de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | valeur de progression actuelle. |

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

