---
title: "LayerResourcesRegistry क्लास"
type: docs
weight: 1010
url: /hi/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | पंजीकृत डिस्क्रिप्टर्स प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | पहला समर्थित ओपनर डिस्क्रिप्टर प्राप्त करता है। |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | उसके टाइप नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | निर्दिष्ट <paramref name="stream" /> के लिए उपयुक्त पहला मिला ओपनर उपयोग करके [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) लोड करता है। |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | ओपनर को रजिस्टर करता है। |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | ओपनर को अनरजिस्टर करता है। |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

पहला समर्थित ओपनर डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | स्ट्रीम। |
| psd_version | int | PSD संस्करण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | लेयर रिसोर्स लोडर डिस्क्रिप्टर या null यदि ऐसे स्ट्रीम के लिए कोई लोडर डिस्क्रिप्टर समर्थित नहीं है। |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | पहला मिला हुआ ओपनर डिस्क्रिप्टर या null यदि ऐसा कोई डिस्क्रिप्टर नहीं मिला। |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

निर्दिष्ट <paramref name="stream" /> के लिए उपयुक्त पहला मिला ओपनर उपयोग करके [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | स्ट्रीम। |
| psd_version | int | PSD संस्करण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | लोड किया गया [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) या null यदि कोई ओपनर नहीं मिला। |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

ओपनर को रजिस्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | रजिस्टर करने के लिए ओपनर डिस्क्रिप्टर। |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

ओपनर को अनरजिस्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | अनरजिस्टर करने के लिए ओपनर डिस्क्रिप्टर। |

