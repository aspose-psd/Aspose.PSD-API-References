---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Ressourcenlader."
type: docs
weight: 84
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Der [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-Ressourcenlader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Bestimmt, ob die Ressource [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) aus dem angegebenen StreamContainer geladen werden kann. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Lädt die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Bestimmt, ob die Ressource [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) aus dem angegebenen StreamContainer geladen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |

**Returns:**
boolean - true, wenn die Ressource [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) aus dem angegebenen StreamContainer geladen werden kann; andernfalls false.
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Lädt die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der StreamContainer, aus dem geladen werden soll. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
