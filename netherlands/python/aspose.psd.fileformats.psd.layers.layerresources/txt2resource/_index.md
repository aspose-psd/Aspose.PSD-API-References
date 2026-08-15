---
title: "Txt2Resource Klasse"
type: docs
weight: 970
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Initialiseert een nieuw exemplaar van de Txt2Resource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| data | byte | r/w | Haalt de gegevens op of stelt ze in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Voegt het tekstrecord toe aan Resource en retourneert de id van het tekstrecord. |
| [get_text_data()](#get_text_data__2) | Haalt het tekstrecord op uit resource-gegevens. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Slaat de opgegeven streamcontainer op. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Initialiseert een nieuw exemplaar van de Txt2Resource klasse

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Voegt het tekstrecord toe aan Resource en retourneert de id van het tekstrecord.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string | De tekst van het record. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De grenzen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Retourneert Id van tekstrecord voor resource |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Haalt het tekstrecord op uit resource-gegevens.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Array van tekstrecord |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Slaat de opgegeven streamcontainer op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| psd_version | int | De PSD‑versie. |

