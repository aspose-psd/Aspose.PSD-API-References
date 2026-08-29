---
title: "Txt2Resource klass"
type: docs
weight: 970
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Initierar en ny instans av Txt2Resource-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| data | byte | r/w | Hämtar eller anger data. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Lägger till textposten i Resource och returnerar id för textposten. |
| [get_text_data()](#get_text_data__2) | Hämtar textposten från resurssdata. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Sparar den angivna strömbehållaren. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Initierar en ny instans av Txt2Resource-klassen

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Lägger till textposten i Resource och returnerar id för textposten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | Postens text. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Gränserna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Returnerar Id för textpost för resursen |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Hämtar textposten från resurssdata.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Array av textpost |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Sparar den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| psd_version | int | PSD-versionen. |

