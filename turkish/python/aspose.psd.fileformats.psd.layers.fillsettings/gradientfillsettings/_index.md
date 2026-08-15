---
title: "GradientFillSettings Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Yeni bir [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Katmanla [align with layer] gösteren bir değeri alır veya ayarlar. |
| açı | double | r/w | Açıyı alır veya ayarlar. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Rengi alır veya ayarlar. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Renk noktalarını alır veya ayarlar. |
| dither | bool | r/w | Bu [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) nesnesinin titremeli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Dolgu türü. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Bu degrade için modu alır.<br/>            'Gradient Type' = 'Solid/Noise' (0/1) belirler. |
| gradient_name | string | r/w | Degrade adını alır veya ayarlar. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Degrade tipini alır veya ayarlar. |
| horizontal_offset | double | r/w | Yüzde olarak yatay ofseti alır veya ayarlar. |
| interpolasyon | short | r/w | Interpolasyon. 'Gradient Type' = 'Solid' olduğunda Pürüzsüzlüğü belirler. Değer aralığı: 0-4096. |
| reverse | bool | r/w | Bu [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| scale | int | r/w | Ölçeği alır veya ayarlar. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Şeffaflık noktalarını alır veya ayarlar. |
| vertical_offset | double | r/w | Yüzde olarak dikey ofseti alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Renk noktasını ekler. |
| [add_transparency_point()](#add_transparency_point__2) | Renk noktasını ekler. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | LFX2 kaynak düğümlerini oluşturur. |
| [remove_color_point(point)](#remove_color_point_point_4) | Renk noktasını kaldırır. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Şeffaflık noktasını kaldırır. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Yeni bir [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) sınıfının örneğini başlatır.

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Renk noktasını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Oluşturulan renk noktası |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Renk noktasını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Oluşturulan şeffaflık noktası |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

LFX2 kaynak düğümlerini oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Oluşturulan [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) listesi |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Renk noktasını kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Nokta. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Şeffaflık noktasını kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Nokta. |

