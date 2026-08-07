---
title: "ILayerResourceLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής πόρων επιπέδου."
type: docs
weight: 32
url: /el/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

Ο φορτωτής πόρων επιπέδου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | Καθορίζει εάν ο πόρος του στρώματος μπορεί να φορτωθεί από το καθορισμένο  StreamContainer . |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | Φορτώνει το [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource). |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


Καθορίζει εάν ο πόρος του στρώματος μπορεί να φορτωθεί από το καθορισμένο  StreamContainer .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| psdVersion | int | Η έκδοση PSD. |

**Returns:**
boolean -  true  εάν ο πόρος του στρώματος μπορεί να φορτωθεί από το καθορισμένο  StreamContainer ; διαφορετικά,  false .
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


Φορτώνει το [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το δοχείο ροής από το οποίο θα φορτωθεί. |
| psdVersion | int | Η έκδοση PSD. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
