---
title: "BlncResource Klasse"
type: docs
weight: 80
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Initialiseert een nieuw exemplaar van de [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| highlights_cyan_red_balance | short | r/w | Haalt of stelt de Highlights Cyan Red Balance in. |
| highlights_magenta_green_balance | short | r/w | Haalt of stelt de Highlights Magenta Green Balance in. |
| highlights_yellow_blue_balance | short | r/w | Haalt of stelt de Highlights Yellow Blue Balance in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| midtones_cyan_red_balance | short | r/w | Haalt of stelt de Midtones Cyan Red Balance in. |
| midtones_magenta_green_balance | short | r/w | Geeft of stelt de Midtones Magenta Green Balance in. |
| midtones_yellow_blue_balance | short | r/w | Geeft of stelt de Midtones Yellow Blue Balance in. |
| preserve_luminosity | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) de luminantie behoudt. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| shadows_cyan_red_balance | short | r/w | Geeft of stelt de Shadows Cyan Red Balance in. |
| shadows_magenta_green_balance | short | r/w | Geeft of stelt de Shadows Magenta Green Balance in. |
| shadows_yellow_blue_balance | short | r/w | Geeft of stelt de Schaduwen Geel Blauw Balans in. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Initialiseert een nieuw exemplaar van de [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) klasse.

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

