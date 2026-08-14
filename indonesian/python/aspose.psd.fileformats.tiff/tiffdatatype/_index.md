---
title: "Kelas TiffDataType"
type: docs
weight: 10
url: /id/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag). |
| jumlah | uint | r | Mendapatkan jumlah elemen. |
| data_size | uint | r | Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag). |
| id | ushort | r | Mendapatkan representasi integer id tag. |
| is_valid | bool | r | Mendapatkan nilai yang menunjukkan apakah data tag valid. Tag yang valid berisi data yang dapat dipertahankan. Tag yang tidak valid tidak dapat disimpan. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Mendapatkan id tag. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Mendapatkan tipe tag. |
| value | object | r/w | Mendapatkan atau mengatur nilai yang dimiliki tipe data ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Membandingkan instance saat ini dengan objek lain dengan tipe yang sama dan mengembalikan sebuah integer yang menunjukkan apakah instance saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan pengurutan dibandingkan objek lainnya. |
| [deep_clone()](#deep_clone__2) | Melakukan kloning mendalam dari instance ini. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Membaca data tag. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Menulis data tag tambahan. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Menulis data tag. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Membandingkan instance saat ini dengan objek lain dengan tipe yang sama dan mengembalikan sebuah integer yang menunjukkan apakah instance saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan pengurutan dibandingkan objek lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| obj | object | Objek untuk dibandingkan dengan instance ini. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Integer 32-bit bertanda yang menunjukkan urutan relatif dari objek-objek yang dibandingkan. Nilai kembali memiliki arti berikut:<br/>            Nilai<br/>            Arti<br/>            Kurang dari nol<br/>            Instance ini kurang dari <paramref name=\"obj\" />.<br/>            Nol<br/>            Instance ini sama dengan <paramref name=\"obj\" />.<br/>            Lebih dari nol<br/>            Instance ini lebih besar dari <paramref name=\"obj\" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Melakukan kloning mendalam dari instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Sebuah klon mendalam dari instance saat ini. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Membaca data tag.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Aliran data. |
| posisi | long | Posisi tag. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Tag yang dibaca. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Menulis data tag tambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Aliran data. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Byte yang sebenarnya ditulis. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Menulis data tag.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Aliran data. |
| additional_data_offset | long | Offset untuk menulis data tambahan ke. |

