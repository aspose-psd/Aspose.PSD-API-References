---
title: "TiffDataType Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Ek veri boyutunu bayt olarak alır (12 baytın etiket verisini sığdırmak için yeterli olmaması durumunda). |
| sayım | uint | r | Eleman sayısını alır. |
| data_size | uint | r | Ek veri boyutunu bayt olarak alır (12 baytın etiket verisini sığdırmak için yeterli olmaması durumunda). |
| id | ushort | r | Etiket kimliğinin tam sayı temsilini alır. |
| is_valid | bool | r | Etiket verisinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket ise saklanamaz. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Etiket kimliğini alır. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Etiket tipini alır. |
| değer | object | r/w | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Mevcut örneği aynı tipteki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu gösteren bir tam sayı döndürür. |
| [deep_clone()](#deep_clone__2) | Bu örneğin derin bir kopyasını oluşturur. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Etiket verisini okur. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Ek etiket verisini yazar. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Etiket verilerini yazar. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Mevcut örneği aynı tipteki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu gösteren bir tam sayı döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| obj | object | Bu örnek ile karşılaştırılacak bir nesne. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | A 32-bit işaretli tam sayı, karşılaştırılan nesnelerin göreceli sırasını gösterir. Döndürülen değer şu anlamlara sahiptir:<br/>            Değer<br/>            Anlam<br/>            Sıfırdan küçük<br/>            Bu örnek <paramref name=\"obj\" />'den küçüktür.<br/>            Sıfır<br/>            Bu örnek <paramref name=\"obj\" />'e eşittir.<br/>            Sıfırdan büyük<br/>            Bu örnek <paramref name=\"obj\" />'den büyüktür. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Bu örneğin derin bir kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Mevcut örneğin derin bir kopyası. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Etiket verisini okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Veri akışı. |
| konum | long | Etiket konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Okunan etiket. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Ek etiket verisini yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Veri akışı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| long | Gerçek yazılan baytlar. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Etiket verilerini yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Veri akışı. |
| additional_data_offset | long | Ek veri yazılacak ofset. |

