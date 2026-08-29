---
title: "CgEdResource Sınıfı"
type: docs
weight: 130
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Yeni bir CgEdResource sınıfının örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| auto | bool | r/w | Bu [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) otomatik olup olmadığını gösteren bir değeri alır veya ayarlar. |
| parlaklık | int | r/w | Parlaklığı alır veya ayarlar. |
| kontrast | int | r/w | Kontrasti alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| lab_color | bool | r/w | [lab color] kullanılıp kullanılmadığını belirten bir değeri alır veya ayarlar. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| mean_value_for_brightness_and_contrast | int | r/w | Parlaklık ve kontrast için ortalama değeri alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| use_legacy | bool | r/w | [use legacy] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| version | int | r/w | Sürümü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Yeni bir CgEdResource sınıfının örneğini başlatır

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

