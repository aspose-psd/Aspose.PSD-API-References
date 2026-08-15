---
title: "VstkResource Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Initialiseert een nieuw exemplaar van de VstkResource‑klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| fill_enabled | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of Stroke‑vulling is ingeschakeld. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Haalt op of stelt de Fill-instellingen van de Stroke in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| stroke_enabled | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of stroke‑effect is ingeschakeld. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Haalt een waarde op of stelt de Stroke Blend‑modus in. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Haalt een waarde op of stelt de Stroke‑entiteit in. Eigenschap bepaalt de vulinstellingen van de stroke. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Haalt op of stelt de Stroke style lijnuitlijning in. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Haalt een waarde op of stelt het type van de stroke‑stijl lijnkap in. |
| stroke_style_line_cap_width | double | r/w | Haalt een waarde op of stelt de Stroke‑lijnkapbreedte in. |
| stroke_style_line_dash_offset | int | r/w | Haalt een waarde op of stelt de stroke‑stijl lijndash‑offset in. |
| stroke_style_line_dash_set | double | r/w | Haalt op of stelt de array van lijnstreepjes in. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Haalt een waarde op of stelt het type van de Stroke‑stijl lijnverbinding in. |
| stroke_style_line_width | double | r/w | Haalt een waarde op of stelt de Stroke‑lijnbreedte in. |
| stroke_style_miter_limit | double | r/w | Haalt een waarde op of stelt de stroke‑stijl miterlimiet in. |
| stroke_style_opacity | int | r/w | Haalt een waarde op of stelt de Stroke‑stijl doorzichtigheid in (0-100%). |
| stroke_style_resolution | double | r/w | Geeft of stelt de resolutie van de Stroke-stijl in. |
| stroke_style_scale_lock | bool | r/w | Geeft of stelt de schaalvergrendeling van de Stroke-stijl in. |
| stroke_style_stroke_adjust | bool | r/w | Geeft of stelt de Stroke-aanpassing in. |
| stroke_style_version | int | r/w | Geeft of stelt de versie van de Stroke-stijl in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Initialiseert een nieuw exemplaar van de VstkResource‑klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

