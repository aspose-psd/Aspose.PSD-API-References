---
title: "FileStreamContainer क्लास"
type: docs
weight: 1270
url: /hi/python-net/aspose.psd/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FileStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | क्रमिक रूप से पढ़ते समय पढ़ने और लिखने के बाइट्स की गिनती निर्दिष्ट करता है। |
| can_read | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम पढ़ने का समर्थन करती है या नहीं। |
| can_seek | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम सीकिंग का समर्थन करती है या नहीं। |
| can_write | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम लिखने का समर्थन करती है या नहीं। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| file_path | string | r | फ़ाइल पथ प्राप्त करता है। |
| is_created | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम स्पष्ट रूप से बनाई गई थी या नहीं। |
| is_stream_disposed_on_close | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह स्ट्रीम बंद करने पर नष्ट हो जाती है या नहीं। |
| is_temporal | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि स्ट्रीम अस्थायी है या नहीं। |
| लंबाई | long | r/w | स्ट्रीम की लंबाई बाइट्स में प्राप्त या सेट करता है। यह मान प्रारंभिक स्ट्रीम स्थिति द्वारा पास किए गए StreamContainer कंस्ट्रक्टर में कम है। |
| position | long | r/w | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है। |
| स्ट्रीम | _io.BufferedRandom | r | डेटा स्ट्रीम प्राप्त करता है। |
| sync_root | object | r | एक ऑब्जेक्ट प्राप्त करता है जिसका उपयोग सिंक्रनाइज़्ड संसाधन तक पहुँच को समकालिक करने के लिए किया जा सकता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | एक नई फ़ाइल स्ट्रीम बनाता है। |
| flush() | इस स्ट्रीम के सभी बफ़र साफ़ करता है और किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखता है। |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | मौजूदा फ़ाइल स्ट्रीम को खोलता है। यदि फ़ाइल स्ट्रीम मौजूद नहीं है तो उपयुक्त अपवाद फेंका जाता है। |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है। |
| [read(bytes)](#read_bytes_4) | निर्दिष्ट बाइट बफ़र को भरने के लिए बाइट्स पढ़ता है। |
| [read_byte()](#read_byte__5) | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है। |
| [save(destination_stream)](#save_destination_stream_6) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) और स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है। |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | सभी स्ट्रीम डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है। |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [save(file_path)](#save_file_path_9) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) और स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है। |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | निर्दिष्ट स्ट्रीम में स्ट्रीम का डेटा सहेजता (कॉपी करता) है। स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है। |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [seek(offset, origin)](#seek_offset_origin_12) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है। |
| seek_begin() | स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट को दर्शाता है। |
| [to_bytes()](#to_bytes__13) | स्ट्रीम डेटा को int ऐरे में बदलता है। |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_14) | स्ट्रीम डेटा को int ऐरे में बदलता है। |
| [write(buffer, offset, count)](#write_buffer_offset_count_15) | वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है और इस स्ट्रीम में वर्तमान स्थिति को लिखे गए बाइट्स की संख्या से आगे बढ़ाता है। |
| [write(bytes)](#write_bytes_16) | निर्दिष्ट सभी बाइट्स को स्ट्रीम में लिखता है। |
| [write_byte(value)](#write_byte_value_17) | स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है। |
| [write_to(stream_container)](#write_to_stream_container_18) | समाहित डेटा को दूसरे [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) में कॉपी करता है। |
| [write_to(stream_container, length)](#write_to_stream_container_length_19) | समाहित डेटा को दूसरे [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) में कॉपी करता है। |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

एक नई फ़ाइल स्ट्रीम बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_location | string | फ़ाइल स्थान। |
| is_temporal | bool | यदि <c>true</c> पर सेट किया जाता है तो फ़ाइल स्ट्रीम कंटेनर अस्थायी होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | फ़ाइल स्ट्रीम कंटेनर। |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

मौजूदा फ़ाइल स्ट्रीम को खोलता है। यदि फ़ाइल स्ट्रीम मौजूद नहीं है तो उपयुक्त अपवाद फेंका जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_location | string | फ़ाइल स्थान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | फ़ाइल स्ट्रीम कंटेनर। |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बफ़र | byte | बाइट्स का एक ऐरे। जब यह मेथड लौटता है, तो बफ़र में निर्दिष्ट बाइट ऐरे होता है जिसमें <paramref name="offset" /> और (<paramref name="offset" /> + <paramref name="count" /> - 1) के बीच के मानों को वर्तमान स्रोत से पढ़े गए बाइट्स द्वारा प्रतिस्थापित किया गया है। |
| offset | int | <paramref name="buffer" /> में शून्य-आधारित बाइट ऑफ़सेट जहाँ से वर्तमान स्ट्रीम से पढ़ा गया डेटा संग्रहीत करना शुरू किया जाता है। |
| count | int | वर्तमान स्ट्रीम से पढ़े जाने वाले बाइट्स की अधिकतम संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | बफ़र में पढ़े गए बाइट्स की कुल संख्या। यदि अनुरोधित बाइट्स उपलब्ध नहीं हैं तो यह अनुरोधित संख्या से कम हो सकता है, या यदि स्ट्रीम का अंत पहुँच गया हो तो शून्य (0) हो सकता है। |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

निर्दिष्ट बाइट बफ़र को भरने के लिए बाइट्स पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बाइट्स | byte | भरण के लिए बाइट्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | पढ़े गए बाइट्स की संख्या। यदि स्ट्रीम में पर्याप्त बाइट्स नहीं हैं तो यह मान बफ़र में बाइट्स की संख्या से कम हो सकता है। |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | असाइनड बाइट को Int32 में कास्ट किया गया मान, या यदि स्ट्रीम के अंत पर हो तो -1। |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) और स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | डेटा को सहेजने के लिए स्ट्रीम। |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

सभी स्ट्रीम डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | डेटा को सहेजने के लिए स्ट्रीम। |
| buffer_size | int | बफ़र। |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | डेटा को सहेजने के लिए स्ट्रीम। |
| buffer_size | int | बफ़र आकार। डिफ़ॉल्ट रूप से [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) मान उपयोग किया जाता है। |
| length | long | कॉपी करने के लिए स्ट्रीम डेटा की लंबाई। डिफ़ॉल्ट रूप से लंबाई को [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान पर सेट किया गया है। |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) और स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | स्ट्रीम डेटा को सहेजने के लिए फ़ाइल पथ। |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

निर्दिष्ट स्ट्रीम में स्ट्रीम का डेटा सहेजता (कॉपी करता) है। स्ट्रीम [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | स्ट्रीम डेटा को सहेजने के लिए फ़ाइल पथ। |
| buffer_size | int | बफ़र आकार। डिफ़ॉल्ट रूप से [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) मान उपयोग किया जाता है। |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | स्ट्रीम डेटा को सहेजने के लिए फ़ाइल पथ। |
| buffer_size | int | बफ़र आकार। डिफ़ॉल्ट रूप से [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) मान उपयोग किया जाता है। |
| length | long | कॉपी करने के लिए स्ट्रीम डेटा की लंबाई। डिफ़ॉल्ट रूप से लंबाई को [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) मान पर सेट किया गया है। |

### Method: seek(offset, origin) {#seek_offset_origin_12}


```
 seek(offset, origin) 
```

वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| offset | long | एक बाइट ऑफ़सेट जो <paramref name="origin" /> पैरामीटर के सापेक्ष है। यह मान StreamContainer कंस्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट को दर्शाता है। |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | SeekOrigin प्रकार का एक मान जो नई स्थिति प्राप्त करने के लिए उपयोग किए जाने वाले संदर्भ बिंदु को दर्शाता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long | वर्तमान स्ट्रीम के भीतर नई स्थिति। |


### Method: to_bytes() {#to_bytes__13}


```
 to_bytes() 
```

स्ट्रीम डेटा को int ऐरे में बदलता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | स्ट्रीम डेटा को int एरे में परिवर्तित किया गया। |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_14}


```
 to_bytes(position, bytes_count) 
```

स्ट्रीम डेटा को int ऐरे में बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| position | long | बाइट्स पढ़ना शुरू करने की स्थिति। |
| bytes_count | long | पढ़ने के लिए बाइट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | स्ट्रीम डेटा को int एरे में परिवर्तित किया गया। |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_15}


```
 write(buffer, offset, count) 
```

वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है और इस स्ट्रीम में वर्तमान स्थिति को लिखे गए बाइट्स की संख्या से आगे बढ़ाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बफ़र | byte | बाइट्स की एक एरे। यह मेथड <paramref name="count" /> बाइट्स को <paramref name="buffer" /> से वर्तमान स्ट्रीम में कॉपी करता है। |
| offset | int | <paramref name="buffer" /> में शून्य-आधारित बाइट ऑफ़सेट जहाँ से बाइट्स को वर्तमान स्ट्रीम में कॉपी करना शुरू किया जाता है। |
| count | int | वर्तमान स्ट्रीम में लिखे जाने वाले बाइट्स की संख्या। |

### Method: write(bytes) {#write_bytes_16}


```
 write(bytes) 
```

निर्दिष्ट सभी बाइट्स को स्ट्रीम में लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बाइट्स | byte | लिखने के लिए बाइट्स। |

### Method: write_byte(value) {#write_byte_value_17}


```
 write_byte(value) 
```

स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | byte | स्ट्रीम में लिखने के लिए बाइट। |

### Method: write_to(stream_container) {#write_to_stream_container_18}


```
 write_to(stream_container) 
```

समाहित डेटा को दूसरे [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) में कॉपी करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | कॉपी करने के लिए स्ट्रीम कंटेनर। |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_19}


```
 write_to(stream_container, length) 
```

समाहित डेटा को दूसरे [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) में कॉपी करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | कॉपी करने के लिए स्ट्रीम कंटेनर। |
| लंबाई | long | लिखने के लिए बाइट्स की संख्या। |

