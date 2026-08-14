---
title: "ImageLoadersRegistry क्लास"
type: docs
weight: 2260
url: /hi/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | पंजीकृत डिस्क्रिप्टर्स प्राप्त करता है। |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | पंजीकृत इमेज लोडिंग फ़ॉर्मेट प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | निर्दिष्ट <paramref name="stream" /> के लिए उपयुक्त पहला मिला लोडर बनाता है और वैकल्पिक रूप से <paramref name="loadOptions" />। |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | निर्दिष्ट <paramref name="stream" /> के लिए उपयुक्त पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है और वैकल्पिक रूप से <paramref name="loadOptions" />। |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | उसके प्रकार नाम द्वारा पहला समर्थित फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | उसके टाइप नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | निर्दिष्ट इमेज लोडर डिस्क्रिप्टर को पंजीकृत करता है। |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | लोडर को पंजीकृत करता है। |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | लोडर को अनपंजीकृत करता है। |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

निर्दिष्ट <paramref name="stream" /> के लिए उपयुक्त पहला मिला लोडर बनाता है और वैकल्पिक रूप से <paramref name="loadOptions" />।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | स्ट्रीम। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | लोड विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | निर्दिष्ट <paramref name="stream" /> और <paramref name="loadOptions" /> को समर्थन देने वाला लोडर, या यदि ऐसा कोई लोडर न मिले तो null। |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

निर्दिष्ट <paramref name="stream" /> के लिए उपयुक्त पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है और वैकल्पिक रूप से <paramref name="loadOptions" />।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | स्ट्रीम। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | लोड विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | निर्दिष्ट <paramref name="stream" /> और <paramref name="loadOptions" /> को समर्थन देने वाला लोडर डिस्क्रिप्टर, या यदि ऐसा कोई डिस्क्रिप्टर न मिले तो null। |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

उसके प्रकार नाम द्वारा पहला समर्थित फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | समर्थित डिस्क्रिप्टर फ़ाइल फ़ॉर्मेट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | पहला मिला लोडर डिस्क्रिप्टर या यदि ऐसा डिस्क्रिप्टर न मिले तो null। |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

उसके टाइप नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| descriptor_type_name | string | डिस्क्रिप्टर प्रकार का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | पहला मिला लोडर डिस्क्रिप्टर या यदि ऐसा डिस्क्रिप्टर न मिले तो null। |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

निर्दिष्ट इमेज लोडर डिस्क्रिप्टर को पंजीकृत करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | इमेज लोडर डिस्क्रिप्टर। |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

लोडर को पंजीकृत करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | पंजीकृत करने के लिए लोडर डिस्क्रिप्टर। |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

लोडर को अनपंजीकृत करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | अनपंजीकृत करने के लिए लोडर डिस्क्रिप्टर। |

