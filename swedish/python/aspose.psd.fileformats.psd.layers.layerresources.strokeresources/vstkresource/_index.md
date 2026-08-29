---
title: "VstkResource-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Initierar en ny instans av VstkResource-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| fill_enabled | bool | r/w | Hämtar eller anger ett värde som indikerar om Stroke-fyllning är aktiverad. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Hämtar eller anger fyllningsinställningar för Stroke. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| stroke_enabled | bool | r/w | Hämtar eller anger ett värde som indikerar om stroke-effekt är aktiverad. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Hämtar eller anger Stroke Blend-läge. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Hämtar eller anger Stroke-entitet. Egenskapen bestämmer fyllningsinställningarna för stroket. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Hämtar eller anger Stroke‑stilens linjejustering. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Hämtar eller anger typen av linjekap för stroke-stil. |
| stroke_style_line_cap_width | double | r/w | Hämtar eller anger Stroke linjekapbredd. |
| stroke_style_line_dash_offset | int | r/w | Hämtar eller anger streckstilens linjedash‑offset. |
| stroke_style_line_dash_set | double | r/w | Hämtar eller anger en array av linjedashar. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Hämtar eller anger streckstilens linjesammanfogningstyp. |
| stroke_style_line_width | double | r/w | Hämtar eller anger strecklinjebredd. |
| stroke_style_miter_limit | double | r/w | Hämtar eller anger streckstilens mitergräns. |
| stroke_style_opacity | int | r/w | Hämtar eller anger streckstilens opacitet (0‑100 %). |
| stroke_style_resolution | double | r/w | Hämtar eller anger streckstilens upplösning. |
| stroke_style_scale_lock | bool | r/w | Hämtar eller anger streckstilens skalningslås. |
| stroke_style_stroke_adjust | bool | r/w | Hämtar eller anger streckjustering. |
| stroke_style_version | int | r/w | Hämtar eller anger streckstilens version. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Initierar en ny instans av VstkResource-klassen

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

