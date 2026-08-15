---
title: "GridAndGuidesResouce Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | GridAndGuidesResouce sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady'ın kaynak imzası. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Normal Photoshop kaynak imzası. |
| data_size | int | r | Kaynak veri boyutunu bayt cinsinden alır. |
| grid_cycle_x | int | r/w | Yatay ızgara döngüsünü alır veya ayarlar. Varsayılan değer 576'dır. |
| grid_cycle_y | int | r/w | Dikey ızgara döngüsünü alır veya ayarlar. Varsayılan değer 576'dır. |
| guide_count | int | r | Kılavuz kaynak blok sayısını alır. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Kılavuzları alır veya ayarlar. |
| header_version | int | r/w | Üstbilgi sürümünü alır veya ayarlar. Bu değer her zaman 1 olmalıdır. |
| id | short | r/w | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| minimal_version | int | r | Gerekli minimum psd sürümünü alır. |
| name | string | r/w | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null bir ad iki bayt 0'dan oluşur). |
| signature | int | r | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| boyut | int | r | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Kaynak bloğunu belirtilen akışa kaydeder. |
| validate_values() | Kaynak değerlerini doğrular. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

GridAndGuidesResouce sınıfının yeni bir örneğini başlatır.

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Kaynak bloğunu belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaynak bloğunun kaydedileceği akış. |

