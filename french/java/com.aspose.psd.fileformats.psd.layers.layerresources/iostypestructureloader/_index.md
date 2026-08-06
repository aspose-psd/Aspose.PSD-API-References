---
title: "IOSTypeStructureLoader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le chargeur de ressources."
type: docs
weight: 84
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Le chargeur de ressources [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Méthodes

| Méthode | Description |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Détermine si la ressource [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) peut être chargée depuis le StreamContainer spécifié. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Charge la [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Détermine si la ressource [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) peut être chargée depuis le StreamContainer spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |

**Returns:**
boolean -  true  si la ressource [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) peut être chargée depuis le StreamContainer spécifié ; sinon,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Charge la [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux depuis lequel charger. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
