---
title: ILayerResourceLoader
second_title: Aspose.PSD for Java API Reference
description: The layer resource loader.
type: docs
weight: 31
url: /java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

The layer resource loader.
## Methods

| Method | Description |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Determines whether layer resource can be loaded from the specified  StreamContainer . |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | Loads the [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Determines whether layer resource can be loaded from the specified  StreamContainer .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| psdVersion | int | The PSD version. |

**Returns:**
boolean -  true  if layer resource can be loaded from the specified  StreamContainer ; otherwise,  false .
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


Loads the [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to load from. |
| psdVersion | int | The PSD version. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
