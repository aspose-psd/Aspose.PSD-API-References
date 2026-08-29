---
title: "LayerHashCalculator"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Hashrekenmachine voor PSD-lagen."
type: docs
weight: 20
url: /nl/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Hashcalculator voor PSD-lagen. Het kan worden gebruikt om gelijke of verschillende lagen in verschillende PSD-bestanden te vinden.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Initialiseert een nieuw exemplaar van de klasse [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Haalt de blendhash op. |
| [getChannelsHash()](#getChannelsHash--) | Haalt de kanaalhash op. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Haalt de inhoudshash op. |
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


Initialiseert een nieuw exemplaar van de klasse [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag. |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Haalt de blendhash op.

**Returns:**
int - Unieke hash voor laagblendopties
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Haalt de kanaalhash op.

**Returns:**
int - Hash van alle laagkanalen
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


Haalt de inhoudshash op.

**Returns:**
int - De hash van de significante parameters van lagen. Deze hash verschilt voor alle soorten lagen
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

