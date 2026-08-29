---
title: "BritResource-klass"
type: docs
weight: 120
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [BritResource()](#BritResource__1) | Initierar en ny instans av klassen [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Initierar en ny instans av klassen [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Initierar en ny instans av klassen [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) .<br/>            PSD-formatsspecifikationen innehåller följande beskrivning:<br/>            2 Ljusstyrka<br/>            2 Kontrast<br/>            2 Medelvärde för ljusstyrka och kontrast<br/>            1 Endast Lab-färg<br/>            Den används inte i moderna PSD (CS5 och senare) där CgEd finns. CgEd lagrar informationsegenskaper |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| ljusstyrka | short | r/w | Hämtar eller anger ljusstyrkan. |
| kontrast | short | r/w | Hämtar eller anger kontrasten. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| lab_color | bool | r/w | Hämtar eller anger ett värde som indikerar om [lab color]. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| mean_value_for_brightness_and_contrast | short | r/w | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Initierar en ny instans av klassen [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Initierar en ny instans av klassen [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | short | Ljusstyrkan. |
| kontrast | short | Kontrasten. |
| mean_value_for_brightness_and_contrast | short | Medelvärdet för ljusstyrka och kontrast. |
| lab_color | bool | om inställd på <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Initierar en ny instans av klassen [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) .<br/>            PSD-formatsspecifikationen innehåller följande beskrivning:<br/>            2 Ljusstyrka<br/>            2 Kontrast<br/>            2 Medelvärde för ljusstyrka och kontrast<br/>            1 Endast Lab-färg<br/>            Den används inte i moderna PSD (CS5 och senare) där CgEd finns. CgEd lagrar informationsegenskaper

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

