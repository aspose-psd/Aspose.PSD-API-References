---
title: "ILayerResourceLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Lagrets resursladdare."
type: docs
weight: 32
url: /sv/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

Lagrets resursladdare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Bestämmer om lagerresursen kan laddas från den angivna  StreamContainer . |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | Laddar [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Bestämmer om lagerresursen kan laddas från den angivna  StreamContainer .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| psdVersion | int | PSD-versionen. |

**Returns:**
boolean -  true  om lagerresursen kan laddas från den angivna  StreamContainer ; annars,  false .
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


Laddar [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att läsa från. |
| psdVersion | int | PSD-versionen. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
