---
title: "ILayerResourceLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Ebenen‑Ressourcen‑Lader."
type: docs
weight: 32
url: /de/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

Der Ebenen‑Ressourcen‑Lader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Bestimmt, ob die Layer-Ressource aus dem angegebenen StreamContainer geladen werden kann. |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | Lädt das [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Bestimmt, ob die Layer-Ressource aus dem angegebenen StreamContainer geladen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| psdVersion | int | Die PSD‑Version. |

**Returns:**
boolean – true, wenn die Layer-Ressource aus dem angegebenen StreamContainer geladen werden kann; andernfalls false.
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


Lädt das [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der StreamContainer, aus dem geladen werden soll. |
| psdVersion | int | Die PSD‑Version. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
