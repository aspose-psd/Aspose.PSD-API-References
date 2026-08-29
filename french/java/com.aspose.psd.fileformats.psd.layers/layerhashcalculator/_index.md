---
title: "LayerHashCalculator"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Calculateur de hachage pour les calques PSD."
type: docs
weight: 20
url: /fr/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Calculateur de hachage pour les calques PSD. Il peut être utilisé pour trouver des calques égaux ou différents dans différents fichiers PSD
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Initialise une nouvelle instance de la classe [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Obtient le hachage de fusion. |
| [getChannelsHash()](#getChannelsHash--) | Obtient le hachage des canaux. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Obtient le hachage du contenu. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


Initialise une nouvelle instance de la classe [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque. |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Obtient le hachage de fusion.

**Returns:**
int - Hachage unique pour les options de fusion de calque
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Obtient le hachage des canaux.

**Returns:**
int - Hachage de tous les canaux du calque
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


Obtient le hachage du contenu.

**Returns:**
int - Le hachage des paramètres significatifs des calques. Ce hachage est différent pour tous les types de calques
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

