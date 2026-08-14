---
title: "IImageLoaderDescriptor क्लास"
type: docs
weight: 1820
url: /hi/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | समर्थित फ़ॉर्मेट को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | निर्धारित करता है कि इमेज लोडर निर्दिष्ट स्ट्रीम से नई छवि पढ़ सकता है या नहीं, और वैकल्पिक रूप से <paramref name="loadOptions" /> का उपयोग करके। |
| [create_instance()](#create_instance__2) | एक नया लोडर इंस्टेंस बनाता है। |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

निर्धारित करता है कि इमेज लोडर निर्दिष्ट स्ट्रीम से नई छवि पढ़ सकता है या नहीं, और वैकल्पिक रूप से <paramref name="loadOptions" /> का उपयोग करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | <paramref name="loadOptions" /> द्वारा निर्दिष्ट फ़ाइल फ़ॉर्मेट विवरण। <paramref name="loadOptions" /> null भी हो सकता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि इस डिस्क्रिप्टर द्वारा बनाया गया इमेज लोडर स्ट्रीम से छवि पढ़ सकता है तो <c>true</c>; अन्यथा <c>false</c>। |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

एक नया लोडर इंस्टेंस बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | एक नया लोडर इंस्टेंस। |


