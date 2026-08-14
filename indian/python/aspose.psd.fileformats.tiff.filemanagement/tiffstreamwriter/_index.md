---
title: "TiffStreamWriter क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | एक नया उदाहरण प्रारंभ करता है [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| position | long | r/w | स्ट्रीम स्थिति को प्राप्त करता है या सेट करता है। |
| sync_root | object | r | एक ऑब्जेक्ट प्राप्त करता है जिसका उपयोग सिंक्रनाइज़्ड संसाधन तक पहुँच को समकालिक करने के लिए किया जा सकता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [write(data)](#write_data_1) | निर्दिष्ट डेटा लिखता है। |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | निर्दिष्ट डेटा लिखता है। |
| [write_double(data)](#write_double_data_3) | स्ट्रीम में एकल डबल मान लिखता है। |
| [write_double_array(data)](#write_double_array_data_4) | स्ट्रीम में डबल मानों की एक एरे लिखता है। |
| [write_float(data)](#write_float_data_5) | स्ट्रीम में एकल फ़्लोट मान लिखता है। |
| [write_float_array(data)](#write_float_array_data_6) | स्ट्रीम में फ़्लोट मानों की एक एरे लिखता है। |
| [write_rational(data)](#write_rational_data_7) | स्ट्रीम में एकल रैशनल संख्या मान लिखता है। |
| [write_rational_array(data)](#write_rational_array_data_8) | स्ट्रीम में अनसाइन्ड रैशनल मानों की एक एरे लिखता है। |
| [write_s_byte(data)](#write_s_byte_data_9) | स्ट्रीम में एकल साइन्ड बाइट मान लिखता है। |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | स्ट्रीम में साइन्ड बाइट मानों की एक एरे लिखता है। |
| [write_s_long_array(data)](#write_s_long_array_data_11) | स्ट्रीम में पूर्णांक मानों की एक एरे लिखता है। |
| [write_s_rational(data)](#write_s_rational_data_12) | स्ट्रीम में एकल साइन्ड रैशनल नंबर मान लिखता है। |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | स्ट्रीम में साइन्ड रैशनल मानों की एक एरे लिखता है। |
| [write_s_short(data)](#write_s_short_data_14) | स्ट्रीम में एकल शॉर्ट मान लिखता है। |
| [write_s_short_array(data)](#write_s_short_array_data_15) | स्ट्रीम में शॉर्ट मानों की एक एरे लिखता है। |
| [write_slong(data)](#write_slong_data_16) | स्ट्रीम में एकल पूर्णांक मान लिखता है। |
| [write_u_byte(data)](#write_u_byte_data_17) | स्ट्रीम में एकल बाइट मान लिखता है। |
| [write_u_long(data)](#write_u_long_data_18) | स्ट्रीम में एकल अनसाइन्ड पूर्णांक मान लिखता है। |
| [write_u_long_array(data)](#write_u_long_array_data_19) | स्ट्रीम में अनसाइन्ड पूर्णांक मानों की एक एरे लिखता है। |
| [write_u_short(data)](#write_u_short_data_20) | स्ट्रीम में एकल अनसाइन्ड शॉर्ट मान लिखता है। |
| [write_u_short_array(data)](#write_u_short_array_data_21) | स्ट्रीम में अनसाइन्ड शॉर्ट मानों की एक एरे लिखता है। |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

एक नया उदाहरण प्रारंभ करता है [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम राइटर। |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

निर्दिष्ट डेटा लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | लिखने के लिए डेटा। |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

निर्दिष्ट डेटा लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | लिखने के लिए डेटा। |
| offset | int | डेटा ऑफसेट। |
| data_length | int | लिखने के लिए डेटा की लंबाई। |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

स्ट्रीम में एकल डबल मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | डबल | लिखने के लिए मान। |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

स्ट्रीम में डबल मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | डबल | लिखने के लिए एरे। |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

स्ट्रीम में एकल फ़्लोट मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | float | लिखने के लिए मान। |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

स्ट्रीम में फ़्लोट मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | float | लिखने के लिए एरे। |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

स्ट्रीम में एकल रैशनल संख्या मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | लिखने के लिए मान। |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

स्ट्रीम में अनसाइन्ड रैशनल मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | लिखने के लिए एरे। |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

स्ट्रीम में एकल साइन्ड बाइट मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | sbyte | लिखने के लिए मान। |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

स्ट्रीम में साइन्ड बाइट मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | sbyte | लिखने के लिए एरे। |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

स्ट्रीम में पूर्णांक मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | int | लिखने के लिए एरे। |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

स्ट्रीम में एकल साइन्ड रैशनल नंबर मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | लिखने के लिए मान। |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

स्ट्रीम में साइन्ड रैशनल मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | लिखने के लिए एरे। |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

स्ट्रीम में एकल शॉर्ट मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | short | लिखने के लिए मान। |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

स्ट्रीम में शॉर्ट मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | short | लिखने के लिए एरे। |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

स्ट्रीम में एकल पूर्णांक मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | int | लिखने के लिए मान। |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

स्ट्रीम में एकल बाइट मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | लिखने के लिए मान। |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

स्ट्रीम में एकल अनसाइन्ड पूर्णांक मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | uint | लिखने के लिए मान। |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

स्ट्रीम में अनसाइन्ड पूर्णांक मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | uint | लिखने के लिए एरे। |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

स्ट्रीम में एकल अनसाइन्ड शॉर्ट मान लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | ushort | लिखने के लिए मान। |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

स्ट्रीम में अनसाइन्ड शॉर्ट मानों की एक एरे लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | ushort | लिखने के लिए एरे। |

