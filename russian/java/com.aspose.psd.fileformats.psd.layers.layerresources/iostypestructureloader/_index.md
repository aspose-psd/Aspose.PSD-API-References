---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Загрузчик ресурсов."
type: docs
weight: 84
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Загрузчик ресурса [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Методы

| Метод | Описание |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Определяет, может ли ресурс [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) быть загружен из указанного StreamContainer. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Загружает [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Определяет, может ли ресурс [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) быть загружен из указанного StreamContainer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |

**Returns:**
boolean -  true  если ресурс [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) может быть загружен из указанного StreamContainer; иначе,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Загружает [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока, из которого загружать. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
