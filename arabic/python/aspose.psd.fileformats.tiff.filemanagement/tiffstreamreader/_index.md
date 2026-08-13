---
title: "فئة TiffStreamReader"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الطول | long | r | يحصل على طول القارئ. |
| throw_exceptions | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة بيانات غير صحيحة (قراءة أو كتابة إلى الدفق). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | يقرأ مصفوفة من قيم البايت من التدفق. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | يقرأ مصفوفة من قيم البايت غير الموقعة من التدفق. |
| [read_double(position)](#read_double_position_3) | اقرأ قيمة مزدوجة واحدة من التدفق. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | يقرأ مصفوفة من القيم المزدوجة من التدفق. |
| [read_float(position)](#read_float_position_5) | اقرأ قيمة عائمة واحدة من التدفق. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | يقرأ مصفوفة من القيم العائمة من التدفق. |
| [read_rational(position)](#read_rational_position_7) | اقرأ قيمة عدد نسبي واحد من التدفق. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | يقرأ مصفوفة من القيم النسبية من التدفق. |
| [read_s_byte(position)](#read_s_byte_position_9) | يقرأ بيانات بايت موقعة من التدفق. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | يقرأ مصفوفة من قيم البايت الموقعة من التدفق. |
| [read_s_long(position)](#read_s_long_position_11) | اقرأ قيمة عدد صحيح موقعة من التدفق. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من التدفق. |
| [read_s_rational(position)](#read_s_rational_position_13) | اقرأ قيمة عدد نسبي موقعة واحدة من التدفق. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | يقرأ مصفوفة من القيم النسبية الموقعة من التدفق. |
| [read_s_short(position)](#read_s_short_position_15) | اقرأ قيمة قصير موقعة من التدفق. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | يقرأ مصفوفة من قيم القصير الموقعة من التدفق. |
| [read_u_long(position)](#read_u_long_position_17) | اقرأ قيمة عدد صحيح غير موقعة من التدفق. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق. |
| [read_u_short(position)](#read_u_short_position_19) | اقرأ قيمة قصير غير موقعة من التدفق. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | يحول البيانات الأساسية إلى حاوية التدفق. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/)

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات مصفوفة البايت. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/)

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات مصفوفة البايت. |
| start_index | int | فهرس البداية في <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/)

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات مصفوفة البايت. |
| start_index | int | فهرس البداية في <paramref name="data" />. |
| data_length | int | طول البيانات. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

ينشئ مثيلاً جديداً من الفئة [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/)

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

يقرأ مصفوفة من قيم البايت من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| مصفوفة | byte | المصفوفة للتعبئة. |
| array_index | int | فهرس المصفوفة للبدء بوضع القيم فيه. |
| position | long | موضع الدفق للقراءة منه. |
| count | long | عدد العناصر للقراءة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| long | مصفوفة قيم البايت. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

يقرأ مصفوفة من قيم البايت غير الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | مصفوفة قيم البايت غير الموقعة. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

اقرأ قيمة مزدوجة واحدة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| double | القيمة المزدوجة المفردة. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

يقرأ مصفوفة من القيم المزدوجة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| double | مصفوفة القيم المزدوجة. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

اقرأ قيمة عائمة واحدة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| float | القيمة العائمة المفردة. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

يقرأ مصفوفة من القيم العائمة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| float | مصفوفة القيم العائمة. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

اقرأ قيمة عدد نسبي واحد من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | العدد النسبي. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

يقرأ مصفوفة من القيم النسبية من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | مصفوفة القيم النسبية. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

يقرأ بيانات بايت موقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| sbyte | قيمة البايت الموقعة. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

يقرأ مصفوفة من قيم البايت الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| sbyte | مصفوفة قيم البايت الموقعة. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

اقرأ قيمة عدد صحيح موقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | قيمة عدد صحيح موقعة. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | مصفوفة قيم الأعداد الصحيحة الموقعة. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

اقرأ قيمة عدد نسبي موقعة واحدة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | العدد النسبي الموقّع. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

يقرأ مصفوفة من القيم النسبية الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | مصفوفة القيم النسبية الموقعة. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

اقرأ قيمة قصير موقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| short | قيمة عدد قصير موقعة. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

يقرأ مصفوفة من قيم القصير الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| short | مصفوفة قيم الأعداد القصيرة الموقعة. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

اقرأ قيمة عدد صحيح غير موقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| uint | قيمة عدد صحيح غير موقعة. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| uint | مصفوفة قيم الأعداد الصحيحة غير الموقعة. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

اقرأ قيمة قصير غير موقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| ushort | قيمة عدد قصير غير موقعة. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| ushort | مصفوفة قيم الأعداد الصحيحة غير الموقعة. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

يحول البيانات الأساسية إلى حاوية التدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| start_position | long | موضع البدء للبدء من التحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الـ[StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) مع البيانات المحوّلة. |


