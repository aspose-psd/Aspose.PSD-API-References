---
title: "ILayerResourceLoader Κλάση"
type: docs
weight: 720
url: /el/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Καθορίζει εάν ο πόρος layer μπορεί να φορτωθεί από το καθορισμένο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Φορτώνει το [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Καθορίζει εάν ο πόρος layer μπορεί να φορτωθεί από το καθορισμένο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| psd_version | int | Η έκδοση PSD. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν ο πόρος layer μπορεί να φορτωθεί από το καθορισμένο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/); διαφορετικά, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Φορτώνει το [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής για φόρτωση. |
| psd_version | int | Η έκδοση PSD. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Ο φορτωμένος πόρος. |


