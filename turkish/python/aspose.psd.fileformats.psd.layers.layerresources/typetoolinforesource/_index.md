---
title: "TypeToolInfoResource Sınıfı"
type: docs
weight: 1000
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | TypeToolInfoResource sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| a_component | short | r/w | Bir bileşeni alır veya ayarlar. |
| b_component | short | r/w | b bileşenini alır veya ayarlar. |
| character_count | int | r/w | Karakter sayısını alır veya ayarlar. |
| color_space_value | short | r/w | Renk uzayı değerini alır veya ayarlar. |
| font_version | short | r/w | Yazı tipi sürümünü alır veya ayarlar. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Yazı tiplerini alır veya ayarlar. |
| fonts_count | short | r | Yazı tipi sayısını alır. |
| g_component | short | r/w | g bileşenini alır veya ayarlar. |
| horizontal_placement | int | r/w | Yatay yerleşimi alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| line_count | short | r | Satır sayısını alır. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Satırları alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| r_component | short | r/w | r bileşenini alır veya ayarlar. |
| scale_factor | int | r/w | Ölçek faktörünü alır veya ayarlar. |
| selection_end | int | r/w | Seçim sonunu alır veya ayarlar. |
| selection_start | int | r/w | Seçim başlangıcını alır veya ayarlar. |
| signature | int | r | İmzayı alır. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Yazı tipi stillerini alır veya ayarlar. |
| styles_count | short | r | Stil sayısını alır. |
| transform_matrix | double | r/w | Dönüşüm matrisini alır veya ayarlar. |
| type_value | short | r/w | Tür değerini alır veya ayarlar. |
| version | short | r/w | Sürümü alır veya ayarlar. |
| vertical_placement | int | r/w | Dikey yerleşimi alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Belirtilen akış konteynerini kaydeder. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

TypeToolInfoResource sınıfının yeni bir örneğini başlatır

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Belirtilen akış konteynerini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

