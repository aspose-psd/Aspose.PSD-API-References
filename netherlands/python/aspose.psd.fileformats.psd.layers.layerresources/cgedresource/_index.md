---
title: "CgEdResource Klasse"
type: docs
weight: 130
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Initialiseert een nieuw exemplaar van de CgEdResource‑klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| auto | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) automatisch is. |
| helderheid | int | r/w | Haalt de helderheid op of stelt deze in. |
| contrast | int | r/w | Haalt het contrast op of stelt dit in. |
| key | int | r | Haalt de laagresource key op. |
| lab_color | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of [lab color] wordt gebruikt. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| mean_value_for_brightness_and_contrast | int | r/w | Haalt de gemiddelde waarde voor helderheid en contrast op of stelt deze in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| use_legacy | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of [use legacy] wordt gebruikt. |
| version | int | r/w | Haalt de versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Initialiseert een nieuw exemplaar van de CgEdResource‑klasse

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

