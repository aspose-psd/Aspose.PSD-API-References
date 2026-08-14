---
title: "TiffDataType वर्ग"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | बाइट्स में अतिरिक्त डेटा आकार प्राप्त करता है (यदि 12 बाइट्स टैग डेटा को फिट करने के लिए पर्याप्त नहीं हैं)। |
| count | uint | r | तत्वों की गिनती प्राप्त करता है। |
| data_size | uint | r | बाइट्स में अतिरिक्त डेटा आकार प्राप्त करता है (यदि 12 बाइट्स टैग डेटा को फिट करने के लिए पर्याप्त नहीं हैं)। |
| id | ushort | r | टैग आईडी का पूर्णांक प्रतिनिधित्व प्राप्त करता है। |
| is_valid | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि टैग डेटा वैध है या नहीं। वैध टैग में डेटा होता है जिसे संरक्षित किया जा सकता है। अवैध टैग को संग्रहीत नहीं किया जा सकता। |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | टैग आईडी प्राप्त करता है। |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | टैग प्रकार प्राप्त करता है। |
| value | object | r/w | इस डेटा प्रकार द्वारा रखे गए मान को प्राप्त या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | वर्तमान उदाहरण की तुलना समान प्रकार के दूसरे ऑब्जेक्ट से करता है और एक पूर्णांक लौटाता है जो दर्शाता है कि वर्तमान उदाहरण क्रम में पहले आता है, बाद में या समान स्थिति में है। |
| [deep_clone()](#deep_clone__2) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | टैग डेटा पढ़ता है। |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | अतिरिक्त टैग डेटा लिखता है। |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | टैग डेटा लिखता है। |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

वर्तमान उदाहरण की तुलना समान प्रकार के दूसरे ऑब्जेक्ट से करता है और एक पूर्णांक लौटाता है जो दर्शाता है कि वर्तमान उदाहरण क्रम में पहले आता है, बाद में या समान स्थिति में है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| obj | object | इस इंस्टेंस के साथ तुलना करने के लिए एक ऑब्जेक्ट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | एक 32-बिट साइन्ड इंटीजर जो तुलना किए जा रहे वस्तुओं के सापेक्ष क्रम को दर्शाता है। रिटर्न वैल्यू के ये अर्थ हैं:<br/>            मान<br/>            अर्थ<br/>            शून्य से कम<br/>            यह इंस्टेंस <paramref name="obj" /> से कम है।<br/>            शून्य<br/>            यह इंस्टेंस <paramref name="obj" /> के बराबर है।<br/>            शून्य से अधिक<br/>            यह इंस्टेंस <paramref name="obj" /> से अधिक है। |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

इस उदाहरण की गहरी प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | वर्तमान इंस्टेंस की एक डीप क्लोन। |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

टैग डेटा पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | डेटा स्ट्रीम। |
| position | long | टैग की स्थिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | पढ़ा गया टैग। |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

अतिरिक्त टैग डेटा लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | डेटा स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long | वास्तविक लिखे गए बाइट्स। |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

टैग डेटा लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | डेटा स्ट्रीम। |
| additional_data_offset | long | अतिरिक्त डेटा लिखने के लिए ऑफसेट। |

