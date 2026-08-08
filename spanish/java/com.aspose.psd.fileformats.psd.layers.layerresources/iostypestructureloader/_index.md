---
title: "IOSTypeStructureLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El cargador de recursos."
type: docs
weight: 84
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

El cargador de recursos [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Métodos

| Método | Descripción |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Determina si el recurso [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) puede cargarse desde el StreamContainer especificado. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Carga el recurso [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Determina si el recurso [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) puede cargarse desde el StreamContainer especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |

**Returns:**
boolean -  true  si el recurso [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) puede cargarse desde el StreamContainer especificado; de lo contrario,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Carga el recurso [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo del que cargar. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
