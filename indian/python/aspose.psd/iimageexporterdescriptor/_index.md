---
title: "IImageExporterDescriptor क्लास"
type: docs
weight: 1800
url: /hi/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | समर्थित फ़ॉर्मेट को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | निर्धारित करता है कि इमेज एक्सपोर्टर निर्दिष्ट इमेज को सहेजने विकल्पों द्वारा निर्दिष्ट इमेज फ़ॉर्मेट में निर्यात कर सकता है या नहीं। |
| [create_instance()](#create_instance__2) | एक नया एक्सपोर्टर इंस्टेंस बनाता है। |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

निर्धारित करता है कि इमेज एक्सपोर्टर निर्दिष्ट इमेज को सहेजने विकल्पों द्वारा निर्दिष्ट इमेज फ़ॉर्मेट में निर्यात कर सकता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | निर्यात करने के लिए छवि। |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्पों का आधार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>True</c> यदि इस डिस्क्रिप्टर द्वारा बनाया गया एक्सपोर्टर निर्दिष्ट इमेज को निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्यात कर सकता है; अन्यथा, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

एक नया एक्सपोर्टर इंस्टेंस बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | एक नया निर्यातक उदाहरण। |


