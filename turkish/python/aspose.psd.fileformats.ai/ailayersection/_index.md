---
title: "AiLayerSection Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| mavi | int | r/w | Mavi renk bileşenini alır veya ayarlar. |
| color_index | int | r/w | Renk indeksini alır veya ayarlar.<br/>            Bu argüman –1 ile 26 arasında değer alabilir. Her tam sayı<br/>            katmanın kullanıcı tanımlama amaçları için atanabilecek bir rengi temsil eder. |
| color_number | int | r/w | Renk numarasını alır veya ayarlar. -1, Kırmızı, Yeşil, Mavi özelliklerinden gelen özel renk değeridir.<br/>            Katmanın renk ayarını belirtir. |
| dim_value | int | r/w | Dim değerini yüzde olarak alır veya ayarlar.<br/>            Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu belirtilen yüzdeye düşürür. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| yeşil | int | r/w | Yeşil renk bileşenini alır veya ayarlar. |
| has_multi_layer_masks | bool | r/w | Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar. |
| is_images_dimmed | bool | r/w | Bu katmanın karartılıp karartılmadığını gösteren bir değeri alır veya ayarlar.<br/>            Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu azaltır. |
| is_locked | bool | r/w | Bu katmanın kilitli olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Öğenin değişikliklerini engeller. |
| is_preview | bool | r/w | Bu katmanın ön izleme olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Katmanda bulunan sanat eserini konturlar yerine renkte gösterir. |
| is_printed | bool | r/w | Bu katmanın basılı olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Doğru ise katmanda bulunan sanat eserini yazdırılabilir yapar. |
| is_shown | bool | r/w | Bu katmanın gösterilip gösterilmediğini gösteren bir değeri alır veya ayarlar.<br/>            Doğru ise katmanda bulunan tüm sanat eserini çalışma tahtasında gösterir. |
| is_template | bool | r/w | Bu katmanın şablon katmanı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| name | string | r/w | Katman adını alır veya ayarlar.<br/>            Öğenin Katmanlar panelinde göründüğü adı belirler. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Raster görüntüleri alır. |
| kırmızı | int | r/w | Kırmızı renk bileşenini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Raster görüntüyü ekler. |
| [get_data()](#get_data__2) | Dize verisini alır. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Raster görüntüyü ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | Raster görüntü. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Dize verisini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bölümün dize verisi |


