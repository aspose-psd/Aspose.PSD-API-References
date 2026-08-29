---
title: "IOSTypeStructureLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il caricatore di risorse."
type: docs
weight: 84
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Il caricatore di risorse [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Determina se la risorsa [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) può essere caricata dal StreamContainer specificato . |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Carica la [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Determina se la risorsa [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) può essere caricata dal StreamContainer specificato .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |

**Returns:**
boolean -  true  se la risorsa [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) può essere caricata dal StreamContainer specificato ; altrimenti,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Carica la [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso da cui caricare. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
