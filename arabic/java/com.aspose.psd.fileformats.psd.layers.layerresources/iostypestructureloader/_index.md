---
title: "IOSTypeStructureLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "محمل الموارد."
type: docs
weight: 84
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

محمل موارد [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | يحدد ما إذا كان يمكن تحميل مورد [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) من الـ StreamContainer المحدد. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | يقوم بتحميل [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


يحدد ما إذا كان يمكن تحميل مورد [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) من الـ StreamContainer المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |

**Returns:**
boolean -  true  إذا كان يمكن تحميل مورد [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) من الـ StreamContainer المحدد؛ وإلا،  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


يقوم بتحميل [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم التحميل منها. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
