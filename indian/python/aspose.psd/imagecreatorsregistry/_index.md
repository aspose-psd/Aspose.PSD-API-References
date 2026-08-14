---
title: "ImageCreatorsRegistry क्लास"
type: docs
weight: 2210
url: /hi/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | पंजीकृत डिस्क्रिप्टर्स प्राप्त करता है। |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | पंजीकृत इमेज निर्माण फ़ॉर्मेट प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | निर्दिष्ट के लिए उपयुक्त पहला मिला हुआ निर्माता बनाता है। |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | निर्दिष्ट के लिए उपयुक्त पहला पाया गया समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | निर्दिष्ट इमेज क्रिएटर डिस्क्रिप्टर को रजिस्टर करता है। |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | क्रिएटर को रजिस्टर करता है। |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | क्रिएटर को अनरजिस्टर करता है। |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

निर्दिष्ट के लिए उपयुक्त पहला मिला हुआ निर्माता बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | छवि विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | निर्दिष्ट को सपोर्ट करने वाला क्रिएटर, या यदि ऐसा कोई क्रिएटर नहीं मिला तो null। |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

निर्दिष्ट के लिए उपयुक्त पहला पाया गया समर्थित डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | छवि विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | निर्दिष्ट को सपोर्ट करने वाला क्रिएटर डिस्क्रिप्टर, या यदि ऐसा कोई डिस्क्रिप्टर नहीं मिला तो null। |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

निर्दिष्ट इमेज क्रिएटर डिस्क्रिप्टर को रजिस्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | इमेज क्रिएटर डिस्क्रिप्टर। |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

क्रिएटर को रजिस्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | रजिस्टर करने के लिए क्रिएटर डिस्क्रिप्टर। |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

क्रिएटर को अनरजिस्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | क्रिएटर डिस्क्रिप्टर। |

