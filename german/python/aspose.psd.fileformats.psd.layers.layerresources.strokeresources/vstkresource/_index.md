---
title: "VstkResource Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Initialisiert eine neue Instanz der VstkResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| fill_enabled | bool | r/w | Liefert oder setzt einen Wert, der angibt, ob die Stroke-Füllung aktiviert ist. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Liest oder setzt Fill-Einstellungen des Stroke. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| stroke_enabled | bool | r/w | Liefert oder setzt einen Wert, der angibt, ob der stroke effect aktiviert ist. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Liefert oder setzt Stroke Blend mode. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Liefert oder setzt Stroke entity. Die Eigenschaft bestimmt die Fülleinstellungen des Stroke. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Liest oder setzt Stroke-Stil Zeilen-Ausrichtung. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Liefert oder setzt den Typ des stroke style line cap. |
| stroke_style_line_cap_width | double | r/w | Liefert oder setzt die Stroke line cap width. |
| stroke_style_line_dash_offset | int | r/w | Liefert oder setzt den stroke style line dash offset. |
| stroke_style_line_dash_set | double | r/w | Liest oder setzt Array von line dashes. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Liefert oder setzt Stroke style line join type. |
| stroke_style_line_width | double | r/w | Liefert oder setzt Stroke line width. |
| stroke_style_miter_limit | double | r/w | Liefert oder setzt das stroke style miter limit. |
| stroke_style_opacity | int | r/w | Liest oder setzt die Deckkraft des Stroke-Stils (0-100%). |
| stroke_style_resolution | double | r/w | Liest oder setzt die Auflösung des Stroke-Stils. |
| stroke_style_scale_lock | bool | r/w | Liest oder setzt die Skalierungsverriegelung des Stroke-Stils. |
| stroke_style_stroke_adjust | bool | r/w | Liest oder setzt die Stroke-Anpassung. |
| stroke_style_version | int | r/w | Liest oder setzt die Version des Stroke-Stils. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Initialisiert eine neue Instanz der VstkResource Klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

