---
title: "ILayerResourceLoader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De laagresource‑lader."
type: docs
weight: 32
url: /nl/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

De laagresource‑lader.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Bepaalt of laagresource kan worden geladen vanuit de opgegeven  StreamContainer . |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | Laadt de [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Bepaalt of laagresource kan worden geladen vanuit de opgegeven  StreamContainer .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| psdVersion | int | De PSD-versie. |

**Returns:**
boolean -  true  als laagresource kan worden geladen vanuit de opgegeven  StreamContainer ; anders,  false .
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


Laadt de [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om uit te laden. |
| psdVersion | int | De PSD-versie. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
