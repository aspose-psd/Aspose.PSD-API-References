---
title: "IOSTypeStructureLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kaynak yükleyici."
type: docs
weight: 84
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Bu [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) kaynağı yükleyicisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Belirtilen StreamContainer'dan [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) kaynağının yüklenip yüklenemeyeceğini belirler. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) kaynağını yükler. |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Belirtilen StreamContainer'dan [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) kaynağının yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |

**Returns:**
boolean -  true  eğer belirtilen StreamContainer'dan [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) kaynağı yüklenebiliyorsa; aksi takdirde,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) kaynağını yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Yüklenecek akış konteyneri. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
