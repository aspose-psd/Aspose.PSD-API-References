---
title: "LinkedLayersManager"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लिंक्ड लेयर्स मैनेजर क्लास।"
type: docs
weight: 27
url: /hi/java/com.aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Inheritance:**
java.lang.Object
```
public final class LinkedLayersManager
```

लिंक्ड लेयर्स मैनेजर क्लास।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(Image container, LinkedLayersRegistry linksRegistry)](#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLayersByLinkGroupId(short linkGroupId)](#getLayersByLinkGroupId-short-) | लिंक समूह आईडी द्वारा लेयर्स प्राप्त करता है। |
| [getLinkGroupId(Layer layer)](#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-) | लेयर से जुड़े लिंक समूह आईडी को प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [linkLayers(Layer[] layers)](#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | इनपुट लेयर्स को लिंक करता है और LingGroupId लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unlinkLayer(Layer layer)](#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | लेयर को अनलिंक करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(Image container, LinkedLayersRegistry linksRegistry) {#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static LinkedLayersManager create_internalized(Image container, LinkedLayersRegistry linksRegistry)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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


लिंक समूह आईडी द्वारा लेयर्स प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linkGroupId | short | लिंक समूह आईडी। |

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[] - लेयर्स एरे।
### getLinkGroupId(Layer layer) {#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final short getLinkGroupId(Layer layer)
```


लेयर से जुड़े लिंक समूह आईडी को प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | लेयर। |

**Returns:**
short - लिंक समूह आईडी।
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


इनपुट लेयर्स को लिंक करता है और LingGroupId लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | लेयर्स। |

**Returns:**
short - लिंक समूह आईडी।
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


लेयर को अनलिंक करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | लेयर। |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

