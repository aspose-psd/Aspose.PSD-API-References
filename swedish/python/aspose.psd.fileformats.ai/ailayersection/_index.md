---
title: "AiLayerSection-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| blå | int | r/w | Hämtar eller anger den blå färgkomponenten. |
| color_index | int | r/w | Hämtar eller anger färgindexet.<br/>            Detta argument kan ha värden mellan –1 och 26. Varje heltal<br/>            representerar en färg som kan tilldelas lagret för användarens<br/>            identifieringsändamål. |
| color_number | int | r/w | Hämtar eller anger färgnumret. -1 är det anpassade färgvärdet från egenskaperna Röd, Grön, Blå.<br/>            Anger lagrets färginställning. |
| dim_value | int | r/w | Hämtar eller anger dimningsvärdet i procent.<br/>            Minskar intensiteten för länkade bilder och bitmapbilder som finns i lagret till den angivna procentsatsen. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| grön | int | r/w | Hämtar eller anger den gröna färgkomponenten. |
| has_multi_layer_masks | bool | r/w | Hämtar eller anger ett värde som indikerar om detta objekt har flerskiktsmasker. |
| is_images_dimmed | bool | r/w | Hämtar eller anger ett värde som indikerar om detta lager är dimmat.<br/>            Minskar intensiteten för länkade bilder och bitmapbilder som finns i lagret. |
| is_locked | bool | r/w | Hämtar eller anger ett värde som indikerar om detta lager är låst.<br/>            Förhindrar ändringar av objektet. |
| is_preview | bool | r/w | Hämtar eller anger ett värde som indikerar om detta lager är en förhandsvisning.<br/>            Visar konstverket i lagret i färg istället för som konturer. |
| is_printed | bool | r/w | Hämtar eller anger ett värde som indikerar om detta lager är utskrivet.<br/>            Gör konstverket i lagret utskrivbart om sant. |
| is_shown | bool | r/w | Hämtar eller anger ett värde som indikerar om detta lager visas.<br/>            Visar allt konstverk i lagret på arbetsytan om sant. |
| is_template | bool | r/w | Hämtar eller anger ett värde som indikerar om detta lager är ett mallager. |
| name | string | r/w | Hämtar eller anger lagernamnet.<br/>            Anger namnet på objektet som det visas i lagerpanelen. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Hämtar rasterbilderna. |
| röd | int | r/w | Hämtar eller anger den röda färgkomponenten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Lägger till rasterbilden. |
| [get_data()](#get_data__2) | Hämtar strängdata. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Lägger till rasterbilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | Rasterbilden. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Hämtar strängdata.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Strängdata för avsnittet |


