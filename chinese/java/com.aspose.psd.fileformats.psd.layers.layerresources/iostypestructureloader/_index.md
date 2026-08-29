---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "资源加载器。"
type: docs
weight: 84
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

The [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 资源加载器。
## Methods

| Method | 描述 |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | 确定是否可以从指定的 StreamContainer 加载 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 资源。 |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | 加载 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)。 |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


确定是否可以从指定的 StreamContainer 加载 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |

**Returns:**
布尔值 - 如果可以从指定的 StreamContainer 加载 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 资源则为 true；否则为 false。
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


加载 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要加载的流容器。 |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
