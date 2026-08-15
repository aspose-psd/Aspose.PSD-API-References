---
title: "UnknownSmartFilter Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.psd.fileformats.psd.layers.smartfilters/unknownsmartfilter/
---

**Summary:** The class to hold unknown smart filter data.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.UnknownSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Karıştırma modunu alır veya ayarlar. |
| filter_id | int | r | Akıllı filtre türü tanımlayıcısını alır. |
| is_enabled | bool | r/w | Akıllı filtrenin etkin durumunu alır veya ayarlar. |
| name | string | r | Akıllı filtre adını alır. |
| opaklık | double | r/w | Akıllı filtrenin opaklık değerini alır veya ayarlar. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Akıllı filtre verileri içeren kaynak tanımlayıcı yapısı. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Mevcut filtreyi giriş [RasterImage](/psd/python-net/aspose.psd/rasterimage/) görüntüsüne uygular. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Mevcut filtreyi giriş [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) maske verilerine uygular. |
| [clone()](#clone__3) | Türün mevcut örneğinin üye bazlı klonunu oluşturur. |


### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Mevcut filtreyi giriş [RasterImage](/psd/python-net/aspose.psd/rasterimage/) görüntüsüne uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Raster görüntü. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Mevcut filtreyi giriş [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) maske verilerine uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Maske verileri içeren katman. |

### Method: clone() {#clone__3}


```
 clone() 
```

Türün mevcut örneğinin üye bazlı klonunu oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Türün mevcut örneğinin üye bazlı klonunu döndürür. |


