---
title: "VstkResource Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | VstkResource sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| fill_enabled | bool | r/w | Darbe doldurmanın etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Stroke'un Fill ayarlarını alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| stroke_enabled | bool | r/w | Darbe efektinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Darbe Karışım modunu alır veya ayarlar. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Darbe varlığını alır veya ayarlar. Özellik, darbenin doldurma ayarlarını belirler. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Stroke stil satır hizalamasını alır veya ayarlar. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Darbe stil çizgi ucu tipini alır veya ayarlar. |
| stroke_style_line_cap_width | double | r/w | Darbe çizgi ucu genişliğini alır veya ayarlar. |
| stroke_style_line_dash_offset | int | r/w | Darbe stil çizgi kesik ofsetini alır veya ayarlar. |
| stroke_style_line_dash_set | double | r/w | Satır tirelerinin dizisini alır veya ayarlar. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Darbe stil çizgi birleşim tipini alır veya ayarlar. |
| stroke_style_line_width | double | r/w | Darbe çizgi genişliğini alır veya ayarlar. |
| stroke_style_miter_limit | double | r/w | Darbe stil keskinlik sınırını alır veya ayarlar. |
| stroke_style_opacity | int | r/w | Darbe stil opaklığını alır veya ayarlar (0-100%). |
| stroke_style_resolution | double | r/w | Alır veya ayarlar Stroke style resolution'ı. |
| stroke_style_scale_lock | bool | r/w | Alır veya ayarlar Stroke style scale lock'ı. |
| stroke_style_stroke_adjust | bool | r/w | Alır veya ayarlar Stroke adjust'ı. |
| stroke_style_version | int | r/w | Alır veya ayarlar stroke style version'ı. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

VstkResource sınıfının yeni bir örneğini başlatır.

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

