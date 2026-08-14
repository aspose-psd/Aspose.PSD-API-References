---
title: "Kelas TiffStreamWriter"
type: docs
weight: 20
url: /id/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Menginisialisasi sebuah instance baru dari kelas [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| posisi | long | r/w | Mendapatkan atau mengatur posisi aliran. |
| sync_root | object | r | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [write(data)](#write_data_1) | Menulis data yang ditentukan. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Menulis data yang ditentukan. |
| [write_double(data)](#write_double_data_3) | Menulis satu nilai double ke aliran. |
| [write_double_array(data)](#write_double_array_data_4) | Menulis sebuah array nilai double ke aliran. |
| [write_float(data)](#write_float_data_5) | Menulis satu nilai float ke aliran. |
| [write_float_array(data)](#write_float_array_data_6) | Menulis sebuah array nilai float ke aliran. |
| [write_rational(data)](#write_rational_data_7) | Menulis satu nilai bilangan rasional ke aliran. |
| [write_rational_array(data)](#write_rational_array_data_8) | Menulis sebuah array nilai rasional tak bertanda ke aliran. |
| [write_s_byte(data)](#write_s_byte_data_9) | Menulis satu nilai byte bertanda ke aliran. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Menulis sebuah array nilai byte bertanda ke aliran. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Menulis sebuah array nilai integer ke aliran. |
| [write_s_rational(data)](#write_s_rational_data_12) | Menulis satu nilai bilangan rasional bertanda ke aliran. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Menulis sebuah array nilai rasional bertanda ke aliran. |
| [write_s_short(data)](#write_s_short_data_14) | Menulis satu nilai short ke aliran. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Menulis sebuah array nilai short ke aliran. |
| [write_slong(data)](#write_slong_data_16) | Menulis satu nilai integer ke aliran. |
| [write_u_byte(data)](#write_u_byte_data_17) | Menulis satu nilai byte ke aliran. |
| [write_u_long(data)](#write_u_long_data_18) | Menulis satu nilai integer tak bertanda ke aliran. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Menulis sebuah array nilai integer tak bertanda ke aliran. |
| [write_u_short(data)](#write_u_short_data_20) | Menulis satu nilai short tak bertanda ke aliran. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Menulis sebuah array nilai short tak bertanda ke aliran. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Penulis aliran. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Menulis data yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data yang akan ditulis. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Menulis data yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data yang akan ditulis. |
| offset | int | Offset data. |
| data_length | int | Panjang data untuk penulis. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Menulis satu nilai double ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | double | Nilai yang akan ditulis. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Menulis sebuah array nilai double ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | double | Array yang akan ditulis. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Menulis satu nilai float ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | float | Nilai yang akan ditulis. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Menulis sebuah array nilai float ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | float | Array yang akan ditulis. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Menulis satu nilai bilangan rasional ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Nilai yang akan ditulis. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Menulis sebuah array nilai rasional tak bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Array yang akan ditulis. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Menulis satu nilai byte bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | sbyte | Nilai yang akan ditulis. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Menulis sebuah array nilai byte bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | sbyte | Array yang akan ditulis. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Menulis sebuah array nilai integer ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | int | Array yang akan ditulis. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Menulis satu nilai bilangan rasional bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Nilai yang akan ditulis. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Menulis sebuah array nilai rasional bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Array yang akan ditulis. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Menulis satu nilai short ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | short | Nilai yang akan ditulis. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Menulis sebuah array nilai short ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | short | Array yang akan ditulis. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Menulis satu nilai integer ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | int | Nilai yang akan ditulis. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Menulis satu nilai byte ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Nilai yang akan ditulis. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Menulis satu nilai integer tak bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | uint | Nilai yang akan ditulis. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Menulis sebuah array nilai integer tak bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | uint | Array yang akan ditulis. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Menulis satu nilai short tak bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | ushort | Nilai yang akan ditulis. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Menulis sebuah array nilai short tak bertanda ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | ushort | Array yang akan ditulis. |

