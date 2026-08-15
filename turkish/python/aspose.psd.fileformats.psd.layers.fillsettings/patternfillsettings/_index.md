---
title: "PatternFillSettings Sınıfı"
type: docs
weight: 130
url: /tr/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | PatternFillSettings sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Katmanla bağlantılı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| açı | double | r/w | Açıyı alır veya ayarlar. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Rengi alır veya ayarlar. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Dolgu türü |
| horizontal_offset | int | r/w | Yatay ofseti alır veya ayarlar. |
| linked | bool | r/w | Bu [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) bağlantılı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| pattern_data | int | r/w | Desen verisini alır veya ayarlar. |
| pattern_height | int | r/w | Desenin yüksekliğini alır veya ayarlar. |
| pattern_id | string | r/w | Desen tanımlayıcısını alır veya ayarlar. |
| pattern_name | string | r/w | Desenin adını alır veya ayarlar. |
| pattern_width | int | r/w | Desenin genişliğini alır veya ayarlar. |
| point_type | string | r/w | Noktanın tipini alır veya ayarlar. |
| scale | double | r/w | Ölçeği alır veya ayarlar. |
| vertical_offset | int | r/w | Dikey ofseti alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | LFX2 kaynak düğümlerini oluşturur. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

PatternFillSettings sınıfının yeni bir örneğini başlatır

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

LFX2 kaynak düğümlerini oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point_type | string | Noktanın tipi. |
| color | [Color](/psd/python-net/aspose.psd/color) | Renk. |
| pattern_name | string | Desenin adı. |
| tanımlayıcı | string | Tanımlayıcı. |
| scale | double | Ölçek. |
| bağlı | bool | eğer <c>true</c> olarak ayarlanmışsa [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Ofset. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Liste: [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


