---
title: "BlncResource Sınıfı"
type: docs
weight: 80
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| highlights_cyan_red_balance | short | r/w | Vurguların Camgöbeği Kırmızı Dengesini alır veya ayarlar. |
| highlights_magenta_green_balance | short | r/w | Vurguların Magenta Yeşil Dengesini alır veya ayarlar. |
| highlights_yellow_blue_balance | short | r/w | Vurguların Sarı Mavi Dengesini alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| midtones_cyan_red_balance | short | r/w | Ara tonların Camgöbeği Kırmızı Dengesini alır veya ayarlar. |
| midtones_magenta_green_balance | short | r/w | Midtones Magenta Green Balance değerini alır veya ayarlar. |
| midtones_yellow_blue_balance | short | r/w | Midtones Yellow Blue Balance değerini alır veya ayarlar. |
| preserve_luminosity | bool | r/w | Bu [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) ışıklılığı koruyup korumadığını gösteren bir değeri alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| shadows_cyan_red_balance | short | r/w | Shadows Cyan Red Balance değerini alır veya ayarlar. |
| shadows_magenta_green_balance | short | r/w | Shadows Magenta Green Balance değerini alır veya ayarlar. |
| shadows_yellow_blue_balance | short | r/w | Gölgeler Sarı Mavi Dengesini alır veya ayarlar. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

[BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) sınıfının yeni bir örneğini başlatır.

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

