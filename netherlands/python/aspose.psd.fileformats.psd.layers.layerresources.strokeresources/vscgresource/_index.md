---
title: "VscgResource Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Initialiseert een nieuw exemplaar van de VscgResource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Haalt op of stelt de array van structuuritems in.<br/>            **Warning:** De `Items` arraywaarden moeten overeenkomen met de `KeyForData` eigenschap, die het type fill-instellingen bepaalt dat is opgeslagen in de structuren binnen `Items`. |
| key | int | r | Haalt de laagresource key op. |
| key_for_data | int | r | Haalt de gehele sleutel op die definieert welk type fill-instellingen is opgeslagen in de resource:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradient - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Pattern - 0x5074466c - PtFlResource.TypeToolKey<br/>            Waarschuwing! De waarde van de eigenschap KeyForData moet overeenkomen met het type Fill-instellingen dat is opgeslagen in Items-structuren. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Initialiseert een nieuw exemplaar van de VscgResource klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

