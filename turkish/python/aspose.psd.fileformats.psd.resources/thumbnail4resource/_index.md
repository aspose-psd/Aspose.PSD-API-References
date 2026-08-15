---
title: "Thumbnail4Resource Sınıfı"
type: docs
weight: 240
url: /tr/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | Thumbnail4Resource sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady'ın kaynak imzası. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Normal Photoshop kaynak imzası. |
| bits_pixel | short | r/w | Bit piksel değerini alır veya ayarlar. |
| data_size | int | r | Kaynak veri boyutunu bayt cinsinden alır. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Küçük resim veri formatını alır veya ayarlar. |
| yükseklik | int | r/w | Küçük resmin piksel cinsinden yüksekliğini alır veya ayarlar. |
| id | short | r/w | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | JPEG seçeneklerini alır veya ayarlar. Yalnızca küçük resim kaynağı JPEG dosya formatında kaydedildiğinde uygundur. RAW formatı tanımlandığında bu seçenek etkisizdir. |
| minimal_version | int | r | Gerekli minimum psd sürümünü alır. |
| name | string | r/w | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null bir ad iki bayt 0'dan oluşur). |
| planes_count | short | r/w | Katman sayısını alır veya ayarlar. |
| signature | int | r | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| boyut | int | r | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| size_after_compression | int | r | Sıkıştırma sonrası boyutu alır veya ayarlar. Tutarlılık kontrolü için kullanılır. |
| thumbnail_argb_32_data | int | r/w | 32 bit ARGB küçük resim verisini alır veya ayarlar. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Küçük resim verisini alır veya ayarlar. |
| total_size | int | r | Toplam veri boyutunu alır. |
| width | int | r/w | Küçük resmin piksel cinsinden genişliğini alır veya ayarlar. |
| width_bytes | int | r | Satır genişliğini bayt cinsinden alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Kaynak blok verisini kaydeder. |
| validate_values() | Kaynak değerlerini doğrular. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

Thumbnail4Resource sınıfının yeni bir örneğini başlatır

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Kaynak blok verisini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

