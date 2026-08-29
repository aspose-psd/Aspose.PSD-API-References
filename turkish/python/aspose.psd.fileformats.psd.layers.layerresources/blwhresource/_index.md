---
title: "BlwhResource Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | BlwhResource sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| black_and_white_preset_file_name | string | r/w | Siyah beyaz ön ayar dosya adını alır veya ayarlar. |
| maviler | int | r/w | Maviler değerini alır veya ayarlar. |
| bw_preset_kind | int | r/w | Siyah beyaz ön ayar türü değerini alır veya ayarlar. |
| camgöbeği | int | r/w | Camgöbeği değerini alır veya ayarlar. |
| yeşiller | int | r/w | Yeşiller değerini alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| eflatun | int | r/w | Eflatun değerini alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| kırmızılar | int | r/w | Kırmızıların değerini alır veya ayarlar. |
| signature | int | r | İmzayı alır. |
| tint_color | int | r/w | Tint Color ARGB değerini alır veya ayarlar. |
| use_tint | bool | r/w | Bir değeri alır veya ayarlar; [tint color] kullanılıp kullanılmadığını gösterir. |
| yellows | int | r/w | Sarıların değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

BlwhResource sınıfının yeni bir örneğini başlatır.

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

