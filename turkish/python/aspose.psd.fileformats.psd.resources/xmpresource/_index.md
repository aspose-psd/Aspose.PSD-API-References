---
title: "XmpResource Sınıfı"
type: docs
weight: 330
url: /tr/python-net/aspose.psd.fileformats.psd.resources/xmpresource/
---

**Summary:** Represents the XMP metadata resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.XmpResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpResource()](#XmpResource__1) | Yeni bir XmpResource sınıf örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady'ın kaynak imzası. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Normal Photoshop kaynak imzası. |
| data_size | int | r | Kaynak veri boyutunu bayt cinsinden alır. |
| id | short | r/w | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| minimal_version | int | r | Gerekli minimum psd sürümünü alır. |
| name | string | r/w | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null bir ad iki bayt 0'dan oluşur). |
| signature | int | r | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| boyut | int | r | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP veri kapsayıcısını al veya ayarla |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Kaynak bloğunu belirtilen akışa kaydeder. |
| validate_values() | Kaynak değerlerini doğrular. |


### Constructor: XmpResource() {#XmpResource__1}


```
 XmpResource() 
```

Yeni bir XmpResource sınıf örneği başlatır.

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Kaynak bloğunu belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaynak bloğunun kaydedileceği akış. |

