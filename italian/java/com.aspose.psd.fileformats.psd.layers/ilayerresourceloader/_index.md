---
title: "ILayerResourceLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il caricatore delle risorse del livello."
type: docs
weight: 32
url: /it/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

Il caricatore delle risorse del livello.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Determina se la risorsa del livello può essere caricata dal StreamContainer specificato. |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | Carica il [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Determina se la risorsa del livello può essere caricata dal StreamContainer specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| psdVersion | int | La versione PSD. |

**Returns:**
boolean -  true  se la risorsa del livello può essere caricata dal StreamContainer specificato; altrimenti,  false .
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


Carica il [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso da cui caricare. |
| psdVersion | int | La versione PSD. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
