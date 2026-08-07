---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pemuat sumber daya."
type: docs
weight: 84
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Pemuat sumber daya [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Menentukan apakah sumber daya [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) dapat dimuat dari StreamContainer yang ditentukan. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Memuat [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Menentukan apakah sumber daya [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) dapat dimuat dari StreamContainer yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |

**Returns:**
boolean - true jika sumber daya [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) dapat dimuat dari StreamContainer yang ditentukan; sebaliknya, false.
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Memuat [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk dimuat dari. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
