---
title: "BritResource‑klasse"
type: docs
weight: 120
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [BritResource()](#BritResource__1) | Initialiseert een nieuw exemplaar van de [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) klasse. |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Initialiseert een nieuw exemplaar van de [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) klasse. |
| [BritResource(bytes)](#BritResource_bytes_3) | Initialiseert een nieuw exemplaar van de [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) klasse.<br/> De PSD‑formaatspecificatie bevat de volgende beschrijving:<br/> 2 Helderheid<br/> 2 Contrast<br/> 2 Gemiddelde waarde voor helderheid en contrast<br/> 1 Alleen Lab‑kleur<br/> Het wordt niet gebruikt in moderne PSD (CS5 en hoger) waar CgEd is. CgEd slaat informatieve eigenschappen op |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| helderheid | short | r/w | Haalt de helderheid op of stelt deze in. |
| contrast | short | r/w | Haalt het contrast op of stelt dit in. |
| key | int | r | Haalt de laagresource key op. |
| lab_color | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [lab color]. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| mean_value_for_brightness_and_contrast | short | r/w | Haalt de gemiddelde waarde voor helderheid en contrast op of stelt deze in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Initialiseert een nieuw exemplaar van de [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) klasse.

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Initialiseert een nieuw exemplaar van de [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| helderheid | short | De helderheid. |
| contrast | short | Het contrast. |
| mean_value_for_brightness_and_contrast | short | De gemiddelde waarde voor helderheid en contrast. |
| lab_color | bool | indien ingesteld op <c>true</c> [Lab-kleur]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Initialiseert een nieuw exemplaar van de [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) klasse.<br/> De PSD‑formaatspecificatie bevat de volgende beschrijving:<br/> 2 Helderheid<br/> 2 Contrast<br/> 2 Gemiddelde waarde voor helderheid en contrast<br/> 1 Alleen Lab‑kleur<br/> Het wordt niet gebruikt in moderne PSD (CS5 en hoger) waar CgEd is. CgEd slaat informatieve eigenschappen op

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De bytes. |

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

