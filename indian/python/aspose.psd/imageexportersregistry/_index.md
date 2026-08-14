---
title: "ImageExportersRegistry क्लास"
type: docs
weight: 2230
url: /hi/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | पंजीकृत एक्सपोर्टर डिस्क्रिप्टर प्राप्त करता है। |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | पंजीकृत एक्सपोर्ट फॉर्मेट प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला एक्सपोर्टर बनाता है। |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | निर्दिष्ट इमेज एक्सपोर्टर डिस्क्रिप्टर को पंजीकृत करता है। |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | एक्सपोर्टर को पंजीकृत करता है। |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | एक्सपोर्टर को पंजीकरण रद्द करता है। |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला एक्सपोर्टर बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | निर्यात करने के लिए छवि। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | निर्यात के लिए उपयोग करने वाले सहेजने विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | निर्दिष्ट छवि और सहेजने विकल्पों को समर्थन करने वाला एक्सपोर्टर, या यदि ऐसा कोई एक्सपोर्टर नहीं मिलता तो null। |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | निर्यात करने के लिए छवि। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | निर्दिष्ट छवि और सहेजने विकल्पों को समर्थन करने वाला एक्सपोर्टर डिस्क्रिप्टर, या यदि ऐसा कोई डिस्क्रिप्टर नहीं मिलता तो null। |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

निर्दिष्ट इमेज एक्सपोर्टर डिस्क्रिप्टर को पंजीकृत करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | छवि एक्सपोर्टर डिस्क्रिप्टर। |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

एक्सपोर्टर को पंजीकृत करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | पंजीकृत करने के लिए एक्सपोर्टर डिस्क्रिप्टर। |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

एक्सपोर्टर को पंजीकरण रद्द करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | पंजीकरण रद्द करने के लिए एक्सपोर्टर डिस्क्रिप्टर। |

