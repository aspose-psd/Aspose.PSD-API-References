---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής πόρων."
type: docs
weight: 84
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

Ο φορτωτής πόρων [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | Καθορίζει εάν ο πόρος [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) μπορεί να φορτωθεί από το καθορισμένο StreamContainer . |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | Φορτώνει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Καθορίζει εάν ο πόρος [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) μπορεί να φορτωθεί από το καθορισμένο StreamContainer .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |

**Returns:**
boolean -  true  εάν ο πόρος [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) μπορεί να φορτωθεί από το καθορισμένο StreamContainer ; διαφορετικά,  false .
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


Φορτώνει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το δοχείο ροής από το οποίο θα φορτωθεί. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
