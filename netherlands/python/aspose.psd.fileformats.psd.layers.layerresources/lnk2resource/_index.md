---
title: "Lnk2Resource Klasse"
type: docs
weight: 570
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---

**Summary:** Defines the class which contains information about embedded files in the PSD format image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by the indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk2Resource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Lnk2Resource()](#Lnk2Resource__1) | Initialiseert een nieuw exemplaar van de [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) klasse. |
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


### Constructor: Lnk2Resource() {#Lnk2Resource__1}


```
 Lnk2Resource() 
```

Initialiseert een nieuw exemplaar van de [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) klasse.

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

