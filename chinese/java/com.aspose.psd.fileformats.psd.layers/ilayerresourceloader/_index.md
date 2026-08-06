---
title: "ILayerResourceLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图层资源加载器。"
type: docs
weight: 32
url: /zh/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

图层资源加载器。
## Methods

| Method | 描述 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | 确定是否可以从指定的 StreamContainer 加载图层资源。 |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | 加载 [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)。 |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


确定是否可以从指定的 StreamContainer 加载图层资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| psdVersion | int | PSD 版本。 |

**Returns:**
布尔值 - 如果可以从指定的 StreamContainer 加载图层资源，则为 true；否则为 false。
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


加载 [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要加载的流容器。 |
| psdVersion | int | PSD 版本。 |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
