---
title: "ILayerResourceLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Katman kaynağı yükleyicisi."
type: docs
weight: 32
url: /tr/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

Katman kaynağı yükleyicisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Belirtilen StreamContainer'dan katman kaynağının yüklenip yüklenemeyeceğini belirler. |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) öğesini yükler. |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Belirtilen StreamContainer'dan katman kaynağının yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| psdVersion | int | PSD sürümü. |

**Returns:**
boolean - belirtilen StreamContainer'dan katman kaynağı yüklenebiliyorsa true; aksi takdirde false.
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) öğesini yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Yüklenecek akış konteyneri. |
| psdVersion | int | PSD sürümü. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
