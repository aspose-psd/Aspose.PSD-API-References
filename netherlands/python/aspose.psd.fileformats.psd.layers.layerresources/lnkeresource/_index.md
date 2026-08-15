---
title: "LnkeResource Klasse"
type: docs
weight: 590
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/
---

**Summary:** Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image.<br/>            The link resource may contain several [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instances which can be accessed by indexer.<br/>            This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnkeResource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LnkeResource()](#LnkeResource__1) | Initialiseert een nieuw exemplaar van de [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klasse. |
| [LnkeResource(data_sources)](#LnkeResource_data_sources_2) | Initialiseert een nieuw exemplaar van de [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| data_source_count | int | r | Haalt het aantal linkgegevensbronnen op dat via de indexeerder benaderd kan worden. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of deze linkresource‑instantie leeg is. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de globale linkresource‑lengte van de PSD in bytes op. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de resourceblokgegevens op. |


### Constructor: LnkeResource() {#LnkeResource__1}


```
 LnkeResource() 
```

Initialiseert een nieuw exemplaar van de [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klasse.

### Constructor: LnkeResource(data_sources) {#LnkeResource_data_sources_2}


```
 LnkeResource(data_sources) 
```

Initialiseert een nieuw exemplaar van de [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data_sources | [LinkDataSource[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) | De gegevensbronnen. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de resourceblokgegevens op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

