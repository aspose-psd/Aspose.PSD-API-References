---
title: "ILayerResourceLoader فئة"
type: docs
weight: 720
url: /ar/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | يحدد ما إذا كان يمكن تحميل مورد الطبقة من [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) المحدد. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | يقوم بتحميل [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

يحدد ما إذا كان يمكن تحميل مورد الطبقة من [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| psd_version | int | إصدار PSD. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل مورد الطبقة من [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) المحدد؛ وإلا، <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

يقوم بتحميل [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق للتحميل منها. |
| psd_version | int | إصدار PSD. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | المورد المحمَّل. |


