---
title: "Kelas TiffStreamReader"
type: docs
weight: 10
url: /id/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| panjang | long | r | Mendapatkan panjang pembaca. |
| throw_exceptions | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah pengecualian dilempar pada pemrosesan data yang tidak tepat (membaca atau menulis ke aliran). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Membaca sebuah array nilai byte dari aliran. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Membaca sebuah array nilai byte tak bertanda dari aliran. |
| [read_double(position)](#read_double_position_3) | Membaca satu nilai double dari aliran. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Membaca sebuah array nilai double dari aliran. |
| [read_float(position)](#read_float_position_5) | Membaca satu nilai float dari aliran. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Membaca sebuah array nilai float dari aliran. |
| [read_rational(position)](#read_rational_position_7) | Membaca satu nilai bilangan rasional dari aliran. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Membaca sebuah array nilai rasional dari aliran. |
| [read_s_byte(position)](#read_s_byte_position_9) | Membaca data byte bertanda dari aliran. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Membaca sebuah array nilai byte bertanda dari aliran. |
| [read_s_long(position)](#read_s_long_position_11) | Membaca nilai integer bertanda dari aliran. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Membaca sebuah array nilai integer bertanda dari aliran. |
| [read_s_rational(position)](#read_s_rational_position_13) | Membaca satu nilai bilangan rasional bertanda dari aliran. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Membaca sebuah array nilai rasional bertanda dari aliran. |
| [read_s_short(position)](#read_s_short_position_15) | Membaca nilai short bertanda dari aliran. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Membaca sebuah array nilai short bertanda dari aliran. |
| [read_u_long(position)](#read_u_long_position_17) | Membaca nilai integer tak bertanda dari aliran. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Membaca sebuah array nilai integer tak bertanda dari aliran. |
| [read_u_short(position)](#read_u_short_position_19) | Membaca nilai short tak bertanda dari aliran. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Membaca sebuah array nilai integer tak bertanda dari aliran. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Mengonversi data dasar ke dalam wadah aliran. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data array byte. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data array byte. |
| start_index | int | Indeks awal ke dalam <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data array byte. |
| start_index | int | Indeks awal ke dalam <paramref name="data" />. |
| data_length | int | Panjang data. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Menginisialisasi sebuah instance baru dari kelas [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Membaca sebuah array nilai byte dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| array | byte | Array yang akan diisi. |
| array_index | int | Indeks array untuk memulai menempatkan nilai. |
| posisi | long | Posisi aliran untuk dibaca. |
| jumlah | long | Jumlah elemen yang akan dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Array nilai byte. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Membaca sebuah array nilai byte tak bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Array nilai byte tak bertanda. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Membaca satu nilai double dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Nilai double tunggal. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Membaca sebuah array nilai double dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Array nilai double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Membaca satu nilai float dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| float | Nilai float tunggal. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Membaca sebuah array nilai float dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| float | Array nilai float. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Membaca satu nilai bilangan rasional dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Bilangan rasional. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Membaca sebuah array nilai rasional dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Array nilai rasional. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Membaca data byte bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| sbyte | Nilai byte bertanda. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Membaca sebuah array nilai byte bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| sbyte | Array nilai byte bertanda. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Membaca nilai integer bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai integer bertanda. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Membaca sebuah array nilai integer bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Array nilai integer bertanda. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Membaca satu nilai bilangan rasional bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Bilangan rasional bertanda. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Membaca sebuah array nilai rasional bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Array nilai rasional bertanda. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Membaca nilai short bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| short | Nilai short bertanda. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Membaca sebuah array nilai short bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| short | Array nilai short bertanda. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Membaca nilai integer tak bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| uint | Nilai integer tak bertanda. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Membaca sebuah array nilai integer tak bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| uint | Array nilai integer tak bertanda. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Membaca nilai short tak bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| ushort | Nilai short tak bertanda. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Membaca sebuah array nilai integer tak bertanda dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk dibaca. |
| jumlah | long | Jumlah elemen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| ushort | Array nilai integer tak bertanda. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Mengonversi data dasar ke dalam wadah aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_position | long | Posisi awal untuk memulai konversi dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) dengan data yang dikonversi. |


