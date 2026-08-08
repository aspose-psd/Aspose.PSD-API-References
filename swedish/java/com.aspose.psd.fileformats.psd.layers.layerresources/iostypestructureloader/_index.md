---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Resursläsaren."
type: docs
weight: 84
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Resursläsaren för [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Bestämmer om [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-resursen kan läsas in från den angivna  StreamContainer . |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Läser in [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Bestämmer om [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-resursen kan läsas in från den angivna  StreamContainer .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |

**Returns:**
boolean -  true  om [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-resursen kan läsas in från den angivna  StreamContainer ; annars,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Läser in [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att läsa från. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
