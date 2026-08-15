---
title: "BlwhResource Klasse"
type: docs
weight: 90
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Initialiseert een nieuw exemplaar van de BlwhResource-klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| black_and_white_preset_file_name | string | r/w | Haalt op of stelt de bestandsnaam van de zwart-witpreset in. |
| blauwwaarden | int | r/w | Haalt op of stelt de blauwwaarde in. |
| bw_preset_kind | int | r/w | Haalt op of stelt de waarde van het zwart-witpresettype in. |
| cyaanwaarden | int | r/w | Haalt op of stelt de cyaanwaarde in. |
| groenwaarden | int | r/w | Haalt op of stelt de groenwaarde in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| magenta-waarden | int | r/w | Haalt op of stelt de magentawaarde in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| roodwaarden | int | r/w | Haalt of stelt de rode waarde in. |
| signature | int | r | Haalt de handtekening op. |
| tint_color | int | r/w | Haalt op of stelt de Tint Color ARGB-waarde in. |
| use_tint | bool | r/w | Haalt of stelt een waarde in die aangeeft of [tint color] wordt gebruikt. |
| yellows | int | r/w | Haalt of stelt de gele waarden in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Initialiseert een nieuw exemplaar van de BlwhResource-klasse

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

