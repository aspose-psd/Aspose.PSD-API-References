---
title: "BritResource Sınıfı"
type: docs
weight: 120
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BritResource()](#BritResource__1) | Yeni bir [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) sınıfının bir örneğini başlatır. |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Yeni bir [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) sınıfının bir örneğini başlatır. |
| [BritResource(bytes)](#BritResource_bytes_3) | Yeni bir [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) sınıfının bir örneğini başlatır.<br/>            PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir:<br/>            2 Parlaklık<br/>            2 Kontrast<br/>            2 Parlaklık ve kontrast için ortalama değer<br/>            1 Sadece Lab rengi<br/>            Modern PSD(CS5 ve üzeri) içinde CgEd'in bulunduğu yerde kullanılmaz. CgEd bilgi özelliklerini depolar |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| parlaklık | short | r/w | Parlaklığı alır veya ayarlar. |
| kontrast | short | r/w | Kontrasti alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| lab_color | bool | r/w | Bir değeri alır veya ayarlar ve bu değer [lab color] olup olmadığını gösterir. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| mean_value_for_brightness_and_contrast | short | r/w | Parlaklık ve kontrast için ortalama değeri alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Yeni bir [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) sınıfının bir örneğini başlatır.

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Yeni bir [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parlaklık | short | Parlaklık. |
| kontrast | short | Kontrast. |
| mean_value_for_brightness_and_contrast | short | Parlaklık ve kontrast için ortalama değer. |
| lab_color | bool | eğer <c>true</c> [Lab rengi]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Yeni bir [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) sınıfının bir örneğini başlatır.<br/>            PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir:<br/>            2 Parlaklık<br/>            2 Kontrast<br/>            2 Parlaklık ve kontrast için ortalama değer<br/>            1 Sadece Lab rengi<br/>            Modern PSD(CS5 ve üzeri) içinde CgEd'in bulunduğu yerde kullanılmaz. CgEd bilgi özelliklerini depolar

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Baytlar. |

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

