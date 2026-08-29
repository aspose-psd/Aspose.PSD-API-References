---
title: "AddNoiseSmartFilter Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | Yeni bir [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | Mevcut akıllı filtrenin tanımlayıcısı. |
| amount_noise | double | r/w | Gürültü değeri miktarını alır veya ayarlar. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Karıştırma modunu alır veya ayarlar. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | Gürültü filtresinin dağılımını alır veya ayarlar. |
| filter_id | int | r | Akıllı filtre türü tanımlayıcısını alır. |
| is_enabled | bool | r/w | Akıllı filtrenin etkin durumunu alır veya ayarlar. |
| is_monochromatic | bool | r/w | Monokromatik değerini alır veya ayarlar. |
| name | string | r | Akıllı filtre adını alır. |
| opaklık | double | r/w | Akıllı filtrenin opaklık değerini alır veya ayarlar. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Akıllı filtre verileri içeren kaynak tanımlayıcı yapısı. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Mevcut filtreyi giriş [RasterImage](/psd/python-net/aspose.psd/rasterimage/) görüntüsüne uygular. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Mevcut filtreyi giriş [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) maske verilerine uygular. |
| [clone()](#clone__3) | Türün mevcut örneğinin üye bazlı klonunu oluşturur. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

Yeni bir [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/) sınıfı örneği başlatır.

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


