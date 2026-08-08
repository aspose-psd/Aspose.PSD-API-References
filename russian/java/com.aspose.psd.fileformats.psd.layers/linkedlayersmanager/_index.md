---
title: "LinkedLayersManager"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс менеджера связанных слоёв."
type: docs
weight: 27
url: /ru/java/com.aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Inheritance:**
java.lang.Object
```
public final class LinkedLayersManager
```

Класс менеджера связанных слоёв.
## Методы

| Метод | Описание |
| --- | --- |
| [create_internalized(Image container, LinkedLayersRegistry linksRegistry)](#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLayersByLinkGroupId(short linkGroupId)](#getLayersByLinkGroupId-short-) | Получает слои по идентификатору группы ссылок. |
| [getLinkGroupId(Layer layer)](#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-) | Получает идентификатор группы ссылок, связанный с слоем. |
| [hashCode()](#hashCode--) |  |
| [linkLayers(Layer[] layers)](#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Связывает входные слои и возвращает LingGroupId. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unlinkLayer(Layer layer)](#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Отвязывает слой.. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(Image container, LinkedLayersRegistry linksRegistry) {#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static LinkedLayersManager create_internalized(Image container, LinkedLayersRegistry linksRegistry)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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


Получает слои по идентификатору группы ссылок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| linkGroupId | short | Идентификатор группы ссылок. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[] - Массив слоёв.
### getLinkGroupId(Layer layer) {#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final short getLinkGroupId(Layer layer)
```


Получает идентификатор группы ссылок, связанный с слоем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой. |

**Returns:**
short - Идентификатор группы ссылок.
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


Связывает входные слои и возвращает LingGroupId.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Слои. |

**Returns:**
short - Идентификатор группы ссылок.
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


Отвязывает слой..

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

