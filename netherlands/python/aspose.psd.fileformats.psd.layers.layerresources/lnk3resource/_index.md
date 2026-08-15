---
title: "Lnk3Resource Klasse"
type: docs
weight: 580
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---

**Summary:** Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk3Resource

**Inheritance:** Lnk2Resource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Lnk3Resource()](#Lnk3Resource__1) | Initialiseert een nieuw exemplaar van de [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) klasse. |
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


### Constructor: Lnk3Resource() {#Lnk3Resource__1}


```
 Lnk3Resource() 
```

Initialiseert een nieuw exemplaar van de [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) klasse.

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

