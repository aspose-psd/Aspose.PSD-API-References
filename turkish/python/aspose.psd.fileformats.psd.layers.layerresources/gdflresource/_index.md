---
title: "GdFlResource Sınıfı"
type: docs
weight: 330
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | GdFlResource sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| align_with_layer | bool | r/w | Katmanla [align with layer] gösteren bir değeri alır veya ayarlar. |
| açı | double | r/w | Açıyı alır veya ayarlar. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | RGB'nin rengini alır. |
| color_model | string | r/w | Renk Modeli - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Renk noktalarını alır. |
| dither | bool | r/w | Bu [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) nesnesinin dithering yapıp yapmadığını gösteren bir değeri alır veya ayarlar. |
| gradient_interval | double | r/w | Gradyan aralığını alır veya ayarlar. |
| gradient_mode | string | r/w | Bu gradyan için mod.<br/>            'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\" belirler. |
| gradient_name | string | r/w | Degrade adını alır veya ayarlar. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Degrade tipini alır veya ayarlar. |
| horizontal_offset | double | r/w | Yatay ofseti alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat'ın maksimum rengi. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat'ın minimum rengi. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| reverse | bool | r/w | Bu [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| rnd_number_seed | int | r/w | Gürültü gradyanı için renk üretiminde kullanılan rastgele sayı tohumu. |
| pürüzlülük | int | r/w | Pürüzlülük faktörü. |
| scale | int | r/w | Ölçeği alır veya ayarlar. |
| show_transparency | bool | r/w | Şeffaflığı gösterme bayrağı. |
| signature | int | r | İmzayı alır. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Şeffaflık noktalarını alır. |
| use_vector_color | bool | r/w | Vektör rengini kullanma bayrağı. |
| vertical_offset | double | r/w | Dikey ofseti alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

GdFlResource sınıfının yeni bir örneğini başlatır

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

