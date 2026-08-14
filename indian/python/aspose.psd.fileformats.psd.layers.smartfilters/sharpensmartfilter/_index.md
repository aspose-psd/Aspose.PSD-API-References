---
title: "SharpenSmartFilter क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---

**Summary:** The Sharpen smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SharpenSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [SharpenSmartFilter()](#SharpenSmartFilter__1) | [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) क्लास का नया उदाहरण प्रारंभ करता है। |
| [SharpenSmartFilter(source_descriptor)](#SharpenSmartFilter_source_descriptor_2) | [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) क्लास का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | वर्तमान स्मार्ट फ़िल्टर का पहचानकर्ता। |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | ब्लेंडिंग मोड को प्राप्त करता है या सेट करता है। |
| filter_id | int | r | स्मार्ट फ़िल्टर प्रकार पहचानकर्ता को प्राप्त करता है। |
| is_enabled | bool | r/w | स्मार्ट फ़िल्टर की सक्षम स्थिति को प्राप्त करता है या सेट करता है। |
| name | string | r | स्मार्ट फ़िल्टर का नाम प्राप्त करता है। |
| opacity | डबल | r/w | स्मार्ट फ़िल्टर की अपारदर्शिता मान को प्राप्त करता है या सेट करता है। |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | स्मार्ट फ़िल्टर डेटा के साथ स्रोत वर्णनकर्ता संरचना। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | वर्तमान फ़िल्टर को इनपुट [RasterImage](/psd/python-net/aspose.psd/rasterimage/) छवि पर लागू करता है। |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | वर्तमान फ़िल्टर को इनपुट [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) मास्क डेटा पर लागू करता है। |
| [clone()](#clone__3) | प्रकार की वर्तमान इंस्टेंस की सदस्य-वार क्लोन बनाता है। |


### Constructor: SharpenSmartFilter() {#SharpenSmartFilter__1}


```
 SharpenSmartFilter() 
```

[SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) क्लास का नया उदाहरण प्रारंभ करता है।

### Constructor: SharpenSmartFilter(source_descriptor) {#SharpenSmartFilter_source_descriptor_2}


```
 SharpenSmartFilter(source_descriptor) 
```

[SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | स्मार्ट फ़िल्टर जानकारी के साथ वर्णनकर्ता संरचना। |

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

वर्तमान फ़िल्टर को इनपुट [RasterImage](/psd/python-net/aspose.psd/rasterimage/) छवि पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | रास्टर इमेज। |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

वर्तमान फ़िल्टर को इनपुट [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) मास्क डेटा पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | मास्क डेटा के साथ लेयर। |

### Method: clone() {#clone__3}


```
 clone() 
```

प्रकार की वर्तमान इंस्टेंस की सदस्य-वार क्लोन बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | प्रकार की वर्तमान इंस्टेंस की सदस्य-वार क्लोन लौटाता है। |


