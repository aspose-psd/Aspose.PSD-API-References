---
title: "PostResource-klass"
type: docs
weight: 840
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/
---

**Summary:** Class PostResource. Posterize layer settings.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PostResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PostResource()](#PostResource__1) | Initierar en ny instans av klassen PostResource |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| nivåer | short | r/w | Nivåer för Posterize‑lagret. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: PostResource() {#PostResource__1}


```
 PostResource() 
```

Initierar en ny instans av klassen PostResource

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

