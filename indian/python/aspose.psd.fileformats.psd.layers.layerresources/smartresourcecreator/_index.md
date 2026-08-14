---
title: "SmartResourceCreator क्लास"
type: docs
weight: 910
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | नया उदाहरण प्रारंभ करता है [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) क्लास का। |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | नया उदाहरण प्रारंभ करता है [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) क्लास का। |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | नया उदाहरण प्रारंभ करता है [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) क्लास को<br/>            दिए गए टेम्पलेट के साथ। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | स्थापित संसाधन उत्पन्न करता है। |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | एम्बेडेड स्मार्ट ऑब्जेक्ट संसाधन उत्पन्न करता है। |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | बाहरी स्मार्ट ऑब्जेक्ट संसाधन उत्पन्न करता है। |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

नया उदाहरण प्रारंभ करता है [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) क्लास का।

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

नया उदाहरण प्रारंभ करता है [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| is_custom | bool | यदि सेट किया गया है <c>true</c> [is custom]। |
| has_comp_info | bool | यदि सेट किया गया है <c>true</c> [has comp information]। |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

नया उदाहरण प्रारंभ करता है [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) क्लास को<br/>            दिए गए टेम्पलेट के साथ।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | स्मार्ट ऑब्जेक्ट संसाधन टेम्पलेट। |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

स्थापित संसाधन उत्पन्न करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | जनरेट किया गया [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) उदाहरण। |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

एम्बेडेड स्मार्ट ऑब्जेक्ट संसाधन उत्पन्न करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | जनरेट किया गया [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) उदाहरण। |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

बाहरी स्मार्ट ऑब्जेक्ट संसाधन उत्पन्न करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | जनरेट किया गया [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) उदाहरण। |


