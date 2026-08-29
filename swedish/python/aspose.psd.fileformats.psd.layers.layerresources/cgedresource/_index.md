---
title: "CgEdResource-klass"
type: docs
weight: 130
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Initierar en ny instans av CgEdResource-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| auto | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) är automatisk. |
| ljusstyrka | int | r/w | Hämtar eller anger ljusstyrkan. |
| kontrast | int | r/w | Hämtar eller anger kontrasten. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| lab_color | bool | r/w | Hämtar eller anger ett värde som indikerar om [lab color] används. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| mean_value_for_brightness_and_contrast | int | r/w | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| use_legacy | bool | r/w | Hämtar eller anger ett värde som indikerar om [use legacy]. |
| version | int | r/w | Hämtar eller anger versionen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Initierar en ny instans av CgEdResource-klassen

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

