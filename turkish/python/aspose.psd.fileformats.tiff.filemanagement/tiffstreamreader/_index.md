---
title: "TiffStreamReader Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır. |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır. |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır. |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| uzunluk | long | r | Okuyucu uzunluğunu alır. |
| throw_exceptions | bool | r/w | İstisnaların hatalı veri işleme (akışı okuma veya yazma) sırasında atılıp atılmayacağını gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Akıştan bayt değerlerinden oluşan bir dizi okur. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Akıştan işaretsiz bayt değerlerinden oluşan bir dizi okur. |
| [read_double(position)](#read_double_position_3) | Akıştan tek bir double değer okur. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Akıştan double değerlerinden oluşan bir dizi okur. |
| [read_float(position)](#read_float_position_5) | Akıştan tek bir float değer okur. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Akıştan float değerlerinden oluşan bir dizi okur. |
| [read_rational(position)](#read_rational_position_7) | Akıştan tek bir rasyonel sayı değeri okur. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Akıştan rasyonel değerlerden oluşan bir dizi okur. |
| [read_s_byte(position)](#read_s_byte_position_9) | Akıştan işaretli bayt verilerini okur. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Akıştan işaretli bayt değerlerinden oluşan bir dizi okur. |
| [read_s_long(position)](#read_s_long_position_11) | Akıştan işaretli tamsayı değeri okur. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Akıştan işaretli tamsayı değerlerinden oluşan bir dizi okur. |
| [read_s_rational(position)](#read_s_rational_position_13) | Akıştan tek bir işaretli rasyonel sayı değeri okur. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Akıştan işaretli rasyonel değerlerden oluşan bir dizi okur. |
| [read_s_short(position)](#read_s_short_position_15) | Akıştan işaretli short değeri okur. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Akıştan işaretli short değerlerinden oluşan bir dizi okur. |
| [read_u_long(position)](#read_u_long_position_17) | Akıştan işaretsiz tamsayı değeri okur. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Akıştan işaretsiz tamsayı değerlerinden oluşan bir dizi okur. |
| [read_u_short(position)](#read_u_short_position_19) | Akıştan işaretsiz short değeri okur. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Akıştan işaretsiz tamsayı değerlerinden oluşan bir dizi okur. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Temel verileri akış konteynerine dönüştürür. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Bayt dizi verisi. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Bayt dizi verisi. |
| start_index | int | Veri <paramref name="data" /> için başlangıç indeksi. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Bayt dizi verisi. |
| start_index | int | Veri <paramref name="data" /> için başlangıç indeksi. |
| data_length | int | Verinin uzunluğu. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Yeni bir [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Akıştan bayt değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dizi | byte | Doldurulacak dizi. |
| array_index | int | Değerleri koymaya başlanacak dizi indeksi. |
| konum | long | Okunacak akış konumu. |
| sayım | long | Okunacak öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| long | Bayt değerlerinin dizisi. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Akıştan işaretsiz bayt değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | İşaretsiz bayt değerlerinin dizisi. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Akıştan tek bir double değer okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Tek double değeri. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Akıştan double değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Double değerlerinin dizisi. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Akıştan tek bir float değer okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Tek float değeri. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Akıştan float değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Float değerlerinin dizisi. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Akıştan tek bir rasyonel sayı değeri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Rasyonel sayı. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Akıştan rasyonel değerlerden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Rasyonel değerlerin dizisi. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Akıştan işaretli bayt verilerini okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| sbyte | İşaretli bayt değeri. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Akıştan işaretli bayt değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| sbyte | İşaretli bayt değerlerinin dizisi. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Akıştan işaretli tamsayı değeri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | İşaretli tamsayı değeri. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Akıştan işaretli tamsayı değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | İşaretli tamsayı değerlerinin dizisi. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Akıştan tek bir işaretli rasyonel sayı değeri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | İşaretli rasyonel sayı. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Akıştan işaretli rasyonel değerlerden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | İşaretli rasyonel değerlerin dizisi. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Akıştan işaretli short değeri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| short | İşaretli short değeri. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Akıştan işaretli short değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| short | İşaretli short değerlerinin dizisi. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Akıştan işaretsiz tamsayı değeri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| uint | İşaretsiz tamsayı değeri. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Akıştan işaretsiz tamsayı değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| uint | İşaretsiz tamsayı değerlerinin dizisi. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Akıştan işaretsiz short değeri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| ushort | İşaretsiz short değeri. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Akıştan işaretsiz tamsayı değerlerinden oluşan bir dizi okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Okunacak konum. |
| sayım | long | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| ushort | İşaretsiz tamsayı değerlerinin dizisi. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Temel verileri akış konteynerine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_position | long | Dönüşümün başlayacağı başlangıç konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Dönüştürülmüş verileri içeren [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


