---
title: "TiffStreamReader क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| लंबाई | long | r | रीडर की लंबाई प्राप्त करता है। |
| throw_exceptions | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या गलत डेटा प्रोसेसिंग (रीडिंग या स्ट्रीम में राइटिंग) पर एक्सेप्शन फेंके जाते हैं। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | स्ट्रीम से बाइट मानों की एक ऐरे पढ़ता है। |
| [read_bytes(position, count)](#read_bytes_position_count_2) | स्ट्रीम से अनसाइन्ड बाइट मानों की एक ऐरे पढ़ता है। |
| [read_double(position)](#read_double_position_3) | स्ट्रीम से एकल डबल मान पढ़ता है। |
| [read_double_array(position, count)](#read_double_array_position_count_4) | स्ट्रीम से डबल मानों की एक ऐरे पढ़ता है। |
| [read_float(position)](#read_float_position_5) | स्ट्रीम से एकल फ़्लोट मान पढ़ता है। |
| [read_float_array(position, count)](#read_float_array_position_count_6) | स्ट्रीम से फ़्लोट मानों की एक ऐरे पढ़ता है। |
| [read_rational(position)](#read_rational_position_7) | स्ट्रीम से एकल रैशनल नंबर मान पढ़ता है। |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | स्ट्रीम से रैशनल मानों की एक ऐरे पढ़ता है। |
| [read_s_byte(position)](#read_s_byte_position_9) | स्ट्रीम से साइन्ड बाइट डेटा पढ़ता है। |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | स्ट्रीम से साइन्ड बाइट मानों की एक ऐरे पढ़ता है। |
| [read_s_long(position)](#read_s_long_position_11) | स्ट्रीम से साइन्ड इंटीजर मान पढ़ता है। |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | स्ट्रीम से साइन्ड इंटीजर मानों की एक ऐरे पढ़ता है। |
| [read_s_rational(position)](#read_s_rational_position_13) | स्ट्रीम से एकल साइन्ड रैशनल नंबर मान पढ़ता है। |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | स्ट्रीम से साइन्ड रैशनल मानों की एक ऐरे पढ़ता है। |
| [read_s_short(position)](#read_s_short_position_15) | स्ट्रीम से साइन्ड शॉर्ट मान पढ़ता है। |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | स्ट्रीम से साइन्ड शॉर्ट मानों की एक ऐरे पढ़ता है। |
| [read_u_long(position)](#read_u_long_position_17) | स्ट्रीम से अनसाइन्ड इंटीजर मान पढ़ता है। |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक ऐरे पढ़ता है। |
| [read_u_short(position)](#read_u_short_position_19) | स्ट्रीम से अनसाइन्ड शॉर्ट मान पढ़ता है। |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक ऐरे पढ़ता है। |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | अधोस्थ डेटा को स्ट्रीम कंटेनर में परिवर्तित करता है। |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | बाइट ऐरे डेटा। |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | बाइट ऐरे डेटा। |
| start_index | int | डेटा में प्रारंभिक सूचकांक <paramref name=\"data\" />। |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | बाइट ऐरे डेटा। |
| start_index | int | डेटा में प्रारंभिक सूचकांक <paramref name=\"data\" />। |
| data_length | int | डेटा की लंबाई। |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

नए [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

स्ट्रीम से बाइट मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ऐरे | byte | भरण के लिए ऐरे। |
| array_index | int | एरे इंडेक्स जिससे मान डालना शुरू किया जाता है। |
| position | long | पढ़ने के लिए स्ट्रीम स्थिति। |
| count | long | पढ़ने के लिए तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long | बाइट मानों की एरे। |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

स्ट्रीम से अनसाइन्ड बाइट मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | अनसाइन्ड बाइट मानों की एरे। |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

स्ट्रीम से एकल डबल मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| डबल | एकल डबल मान। |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

स्ट्रीम से डबल मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| डबल | डबल मानों की एरे। |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

स्ट्रीम से एकल फ़्लोट मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float | एकल फ़्लोट मान। |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

स्ट्रीम से फ़्लोट मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float | फ़्लोट मानों की एरे। |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

स्ट्रीम से एकल रैशनल नंबर मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | रैशनल संख्या। |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

स्ट्रीम से रैशनल मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | रैशनल मानों की एरे। |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

स्ट्रीम से साइन्ड बाइट डेटा पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| sbyte | साइन्ड बाइट मान। |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

स्ट्रीम से साइन्ड बाइट मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| sbyte | साइन्ड बाइट मानों की एरे। |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

स्ट्रीम से साइन्ड इंटीजर मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | एक साइन्ड इंटीजर मान। |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

स्ट्रीम से साइन्ड इंटीजर मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | साइन्ड इंटीजर मानों की एरे। |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

स्ट्रीम से एकल साइन्ड रैशनल नंबर मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | साइन्ड रैशनल संख्या। |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

स्ट्रीम से साइन्ड रैशनल मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | साइन्ड रैशनल मानों की एरे। |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

स्ट्रीम से साइन्ड शॉर्ट मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| short | एक साइन्ड शॉर्ट मान। |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

स्ट्रीम से साइन्ड शॉर्ट मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| short | साइन्ड शॉर्ट मानों की एरे। |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

स्ट्रीम से अनसाइन्ड इंटीजर मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| uint | एक अनसाइन्ड इंटीजर मान। |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| uint | अनसाइन्ड इंटीजर मानों की एरे। |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

स्ट्रीम से अनसाइन्ड शॉर्ट मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| ushort | एक अनसाइन्ड शॉर्ट मान। |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक ऐरे पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की गिनती। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| ushort | अनसाइन्ड इंटीजर मानों की एरे। |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

अधोस्थ डेटा को स्ट्रीम कंटेनर में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| start_position | long | रूपांतरण शुरू करने के लिए प्रारंभिक स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | परिवर्तित डेटा के साथ [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)। |


