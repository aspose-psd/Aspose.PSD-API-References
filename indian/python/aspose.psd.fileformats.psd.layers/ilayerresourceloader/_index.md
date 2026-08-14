---
title: "ILayerResourceLoader क्लास"
type: docs
weight: 720
url: /hi/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | निर्धारित करता है कि लेयर रिसोर्स को निर्दिष्ट [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) से लोड किया जा सकता है या नहीं। |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) को लोड करता है। |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

निर्धारित करता है कि लेयर रिसोर्स को निर्दिष्ट [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) से लोड किया जा सकता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि लेयर रिसोर्स को निर्दिष्ट [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) से लोड किया जा सकता है; अन्यथा, <c>false</c>। |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) को लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | लोड करने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | लोड किया गया रिसोर्स। |


