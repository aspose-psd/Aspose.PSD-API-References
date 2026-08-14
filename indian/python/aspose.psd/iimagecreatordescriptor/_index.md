---
title: "IImageCreatorDescriptor क्लास"
type: docs
weight: 1770
url: /hi/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | समर्थित फ़ॉर्मेट को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | निर्धारित करता है कि इमेज क्रिएटर <paramref name="imageOptions" /> का उपयोग करके नई छवि बना सकता है या नहीं। |
| [create_instance()](#create_instance__2) | एक नया क्रिएटर इंस्टेंस बनाता है। |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

निर्धारित करता है कि इमेज क्रिएटर <paramref name="imageOptions" /> का उपयोग करके नई छवि बना सकता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | छवि विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>True</c> यदि इस डिस्क्रिप्टर द्वारा निर्मित इमेज क्रिएटर निर्दिष्ट <paramref name="imageOptions" /> का उपयोग करके इमेज डेटा बना सकता है; अन्यथा, <c>false</c>। |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

एक नया क्रिएटर इंस्टेंस बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | एक नया क्रिएटर इंस्टेंस। |


