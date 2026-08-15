---
title: "GrdmResource Sınıfı"
type: docs
weight: 340
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Yeni bir [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| color_model | short | r/w | Renk Modeli.<br/>            'Gradient type' = 'Noise' olduğunda, 'Color Model' değerini RGB/SHB/LAB (3/4/6) olarak atayabiliriz. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Renk noktalarını alır veya ayarlar. |
| dither | bool | r/w | Gradyan titremeli. |
| expansion_count | short | r/w | Genişleme sayısı ( = 2 Photoshop 6.0 için). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Bu gradyan için mod<br/>            'Gradient Type' = 'Solid/Noise' (0/1) belirler. |
| gradient_name | string | r/w | Gradyanın adı: Unicode dizesi, doldurulmuş. |
| interpolasyon | short | r/w | Enterpolasyon. 'Gradient Type' = 'Solid' (GradientMode = 0) olduğunda Pürüzsüzlüğü belirler. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp formatının maksimum rengi.<br/>            Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp formatının minimum rengi.<br/>            Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| ters | bool | r/w | Gradyan ters mi. |
| rnd_number_seed | int | r/w | Gürültü gradyanı için renk üretiminde kullanılan rastgele sayı tohumu. |
| pürüzlülük | int | r/w | Pürüz faktörü<br/>            'Gradient type' = 'Noise' olduğunda, 'Roughness' (0 - 2048) atayabiliriz. |
| show_transparency | short | r/w | Şeffaflığı gösterme bayrağı<br/>            'Gradient type' = 'Noise' olduğunda, 'Add transparency' true olarak ayarlanabilir. |
| signature | int | r | İmzayı alır. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Şeffaflık noktalarını alır veya ayarlar. |
| use_vector_color | short | r/w | Vektör rengini kullanma bayrağı. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynak verilerini belirtilen akış konteynerine kaydeder. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Yeni bir [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| psd_version | int | Kaynağın psd sürümü. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Kaynak verilerini belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

