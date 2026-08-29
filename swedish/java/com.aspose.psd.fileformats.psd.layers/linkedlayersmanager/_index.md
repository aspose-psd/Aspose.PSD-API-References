---
title: "LinkedLayersManager"
second_title: "Aspose.PSD för Java API-referens"
description: "Klass för hantering av länkade lager."
type: docs
weight: 27
url: /sv/java/com.aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Inheritance:**
java.lang.Object
```
public final class LinkedLayersManager
```

Klass för hantering av länkade lager.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(Image container, LinkedLayersRegistry linksRegistry)](#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLayersByLinkGroupId(short linkGroupId)](#getLayersByLinkGroupId-short-) | Hämtar lager efter länkgrupps‑ID. |
| [getLinkGroupId(Layer layer)](#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-) | Hämtar länkgruppens ID som är associerad med lagret. |
| [hashCode()](#hashCode--) |  |
| [linkLayers(Layer[] layers)](#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Länkar inmatningslagren och returnerar LingGroupId. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unlinkLayer(Layer layer)](#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Kopplar bort lagret.. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(Image container, LinkedLayersRegistry linksRegistry) {#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static LinkedLayersManager create_internalized(Image container, LinkedLayersRegistry linksRegistry)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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


Hämtar lager efter länkgrupps‑ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| linkGroupId | short | Länkgruppens ID. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[] - Lagerarrayen.
### getLinkGroupId(Layer layer) {#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final short getLinkGroupId(Layer layer)
```


Hämtar länkgruppens ID som är associerad med lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret. |

**Returns:**
short - Länkgruppens ID.
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


Länkar inmatningslagren och returnerar LingGroupId.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagren. |

**Returns:**
short - Länkgruppens ID.
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


Kopplar bort lagret..

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret. |

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

