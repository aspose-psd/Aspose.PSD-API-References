---
title: "LevlResource klasse"
type: docs
weight: 490
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Initialiseert een nieuw exemplaar van de [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) klasse. |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Initialiseert een nieuw exemplaar van de [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) klasse.<br/>            Ondersteund in GrayScale, Duotone, RGB, CMYK, Lab-kleurmodi<br/>            2 bytes - Versie (=2)<br/>            29 * 10 bytes - Sets van levelrecords met 5 korte gehele getallen<br/>            4 bytes - Lvls-header (Begint bij index 292)<br/>            2 bytes - Versie (=3)<br/>            2 bytes - Aantal totale levelrecords<br/>            10 * (Total Count - 29)<br/>            Nulafsluiting van Lvls-resource moet ook voor vier worden gevouwen |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| version | short | r | Haalt de versie op. Standaard is 2 |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Haalt het kanaal op. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Initialiseert een nieuw exemplaar van de [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) klasse.

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Initialiseert een nieuw exemplaar van de [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) klasse.<br/>            Ondersteund in GrayScale, Duotone, RGB, CMYK, Lab-kleurmodi<br/>            2 bytes - Versie (=2)<br/>            29 * 10 bytes - Sets van levelrecords met 5 korte gehele getallen<br/>            4 bytes - Lvls-header (Begint bij index 292)<br/>            2 bytes - Versie (=3)<br/>            2 bytes - Aantal totale levelrecords<br/>            10 * (Total Count - 29)<br/>            Nulafsluiting van Lvls-resource moet ook voor vier worden gevouwen

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De bytes. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Haalt het kanaal op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Levelgegevens van kanaal |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

