---
title: "TiffStreamWriter Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Yeni bir [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| konum | long | r/w | Akış konumunu alır veya ayarlar. |
| sync_root | object | r | Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [write(data)](#write_data_1) | Belirtilen veriyi yazar. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Belirtilen veriyi yazar. |
| [write_double(data)](#write_double_data_3) | Akışa tek bir double değer yazar. |
| [write_double_array(data)](#write_double_array_data_4) | Akışa bir dizi double değer yazar. |
| [write_float(data)](#write_float_data_5) | Akışa tek bir float değer yazar. |
| [write_float_array(data)](#write_float_array_data_6) | Akışa bir dizi float değer yazar. |
| [write_rational(data)](#write_rational_data_7) | Akışa tek bir rasyonel sayı değeri yazar. |
| [write_rational_array(data)](#write_rational_array_data_8) | Akışa bir dizi işaretsiz rasyonel değer yazar. |
| [write_s_byte(data)](#write_s_byte_data_9) | Akışa tek bir işaretli bayt değeri yazar. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Akışa işaretli bayt değerlerinden oluşan bir dizi yazar. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Akışa tam sayı değerlerinden oluşan bir dizi yazar. |
| [write_s_rational(data)](#write_s_rational_data_12) | Akışa tek bir işaretli rasyonel sayı değeri yazar. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Akışa işaretli rasyonel değerlerden oluşan bir dizi yazar. |
| [write_s_short(data)](#write_s_short_data_14) | Akışa tek bir kısa değer yazar. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Akışa kısa değerlerden oluşan bir dizi yazar. |
| [write_slong(data)](#write_slong_data_16) | Akışa tek bir tam sayı değeri yazar. |
| [write_u_byte(data)](#write_u_byte_data_17) | Akışa tek bir bayt değeri yazar. |
| [write_u_long(data)](#write_u_long_data_18) | Akışa tek bir işaretsiz tam sayı değeri yazar. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Akışa işaretsiz tam sayı değerlerinden oluşan bir dizi yazar. |
| [write_u_short(data)](#write_u_short_data_20) | Akışa tek bir işaretsiz kısa değer yazar. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Akışa işaretsiz kısa değerlerden oluşan bir dizi yazar. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Yeni bir [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış yazıcısı. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Belirtilen veriyi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Yazılacak veri. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Belirtilen veriyi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Yazılacak veri. |
| offset | int | Veri ofseti. |
| data_length | int | Yazılacak verinin uzunluğu. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Akışa tek bir double değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | double | Yazılacak değer. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Akışa bir dizi double değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | double | Yazılacak dizi. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Akışa tek bir float değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | float | Yazılacak değer. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Akışa bir dizi float değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | float | Yazılacak dizi. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Akışa tek bir rasyonel sayı değeri yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Yazılacak değer. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Akışa bir dizi işaretsiz rasyonel değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Yazılacak dizi. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Akışa tek bir işaretli bayt değeri yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | sbyte | Yazılacak değer. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Akışa işaretli bayt değerlerinden oluşan bir dizi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | sbyte | Yazılacak dizi. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Akışa tam sayı değerlerinden oluşan bir dizi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | int | Yazılacak dizi. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Akışa tek bir işaretli rasyonel sayı değeri yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Yazılacak değer. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Akışa işaretli rasyonel değerlerden oluşan bir dizi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Yazılacak dizi. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Akışa tek bir kısa değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | short | Yazılacak değer. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Akışa kısa değerlerden oluşan bir dizi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | short | Yazılacak dizi. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Akışa tek bir tam sayı değeri yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | int | Yazılacak değer. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Akışa tek bir bayt değeri yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Yazılacak değer. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Akışa tek bir işaretsiz tam sayı değeri yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | uint | Yazılacak değer. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Akışa işaretsiz tam sayı değerlerinden oluşan bir dizi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | uint | Yazılacak dizi. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Akışa tek bir işaretsiz kısa değer yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | ushort | Yazılacak değer. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Akışa işaretsiz kısa değerlerden oluşan bir dizi yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | ushort | Yazılacak dizi. |

