---
title: "LinkedLayersManager"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Klasse voor beheer van gekoppelde lagen."
type: docs
weight: 27
url: /nl/java/com.aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Inheritance:**
java.lang.Object
```
public final class LinkedLayersManager
```

Klasse voor beheer van gekoppelde lagen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create_internalized(Image container, LinkedLayersRegistry linksRegistry)](#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLayersByLinkGroupId(short linkGroupId)](#getLayersByLinkGroupId-short-) | Haalt lagen op op basis van linkgroeps-id. |
| [getLinkGroupId(Layer layer)](#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-) | Haalt de linkgroeps-ID op die aan de laag is gekoppeld. |
| [hashCode()](#hashCode--) |  |
| [linkLayers(Layer[] layers)](#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Koppelt de invoerlagen en retourneert LingGroupId. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unlinkLayer(Layer layer)](#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Ontkoppelt de laag.. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(Image container, LinkedLayersRegistry linksRegistry) {#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static LinkedLayersManager create_internalized(Image container, LinkedLayersRegistry linksRegistry)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) |  |
| linksRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry |  |

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
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
### getLayersByLinkGroupId(short linkGroupId) {#getLayersByLinkGroupId-short-}
```
public final Layer[] getLayersByLinkGroupId(short linkGroupId)
```


Haalt lagen op op basis van linkgroeps-id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linkGroupId | short | De linkgroeps-id. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[] - De lagenarray.
### getLinkGroupId(Layer layer) {#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final short getLinkGroupId(Layer layer)
```


Haalt de linkgroeps-ID op die aan de laag is gekoppeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag. |

**Returns:**
short - De linkgroeps-id.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### linkLayers(Layer[] layers) {#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final short linkLayers(Layer[] layers)
```


Koppelt de invoerlagen en retourneert LingGroupId.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | De lagen. |

**Returns:**
short - De linkgroeps-id.
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
### unlinkLayer(Layer layer) {#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void unlinkLayer(Layer layer)
```


Ontkoppelt de laag..

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag. |

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

