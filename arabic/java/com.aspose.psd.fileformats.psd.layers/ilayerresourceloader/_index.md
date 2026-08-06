---
title: "ILayerResourceLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "محمل موارد الطبقة."
type: docs
weight: 32
url: /ar/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

محمل موارد الطبقة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | يحدد ما إذا كان يمكن تحميل مورد الطبقة من StreamContainer المحدد. |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | يقوم بتحميل [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


يحدد ما إذا كان يمكن تحميل مورد الطبقة من StreamContainer المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| psdVersion | int | إصدار PSD. |

**Returns:**
منطقي - true إذا كان يمكن تحميل مورد الطبقة من StreamContainer المحدد؛ وإلا false.
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


يقوم بتحميل [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم التحميل منها. |
| psdVersion | int | إصدار PSD. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
