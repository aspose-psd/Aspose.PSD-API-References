---
title: "AiLayerSection Klasse"
type: docs
weight: 50
url: /nl/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| blauw | int | r/w | Haalt of stelt de blauwe kleurcomponent in. |
| color_index | int | r/w | Haalt of stelt de index van de kleur in.<br/>            Dit argument kan waarden aannemen tussen –1 en 26. Elke integer<br/>            vertegenwoordigt een kleur die aan de laag kan worden toegewezen voor gebruikers<br/>            identificatiedoeleinden. |
| color_number | int | r/w | Haalt of stelt het kleurnummer in. -1 is de aangepaste kleurwaarde van de rood-, groen- en blauw‑eigenschappen.<br/>            Specificeert de kleuraanpassing van de laag. |
| dim_value | int | r/w | Haalt of stelt de dim‑waarde in als percentage.<br/>            Vermindert de intensiteit van gekoppelde afbeeldingen en bitmap‑afbeeldingen die in de laag zijn opgenomen tot het opgegeven percentage. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| groen | int | r/w | Geeft of stelt de groene kleurcomponent in. |
| has_multi_layer_masks | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze instantie multilayer masks heeft. |
| is_images_dimmed | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze laag gedimd is.<br/>            Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen die in de laag zijn opgenomen. |
| is_locked | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze laag vergrendeld is.<br/>            Voorkomt wijzigingen aan het item. |
| is_preview | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze laag een voorbeeld is.<br/>            Toont het in de laag opgenomen artwork in kleur in plaats van als contouren. |
| is_printed | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze laag afgedrukt is.<br/>            Maakt het in de laag opgenomen artwork afdrukbaar indien waar. |
| is_shown | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze laag zichtbaar is.<br/>            Toont al het in de laag opgenomen artwork op het artboard indien waar. |
| is_template | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze laag een sjabloonlaag is. |
| name | string | r/w | Geeft of stelt de laagnaam in.<br/>            Specificeert de naam van het item zoals deze verschijnt in het Lagenpaneel. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Haalt de rasterafbeeldingen op. |
| rood | int | r/w | Geeft of stelt de rode kleurcomponent in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Voegt de rasterafbeelding toe. |
| [get_data()](#get_data__2) | Haalt de tekenreeksgegevens op. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Voegt de rasterafbeelding toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | De rasterafbeelding. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Haalt de tekenreeksgegevens op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De tekenreeksgegevens van de sectie |


