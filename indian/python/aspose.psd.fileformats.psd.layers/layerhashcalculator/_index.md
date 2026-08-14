---
title: "LayerHashCalculator क्लास"
type: docs
weight: 960
url: /hi/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | नया उदाहरण प्रारंभ करता है [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) क्लास का। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | ब्लेंडिंग हैश प्राप्त करता है। |
| [get_channels_hash()](#get_channels_hash__2) | चैनल्स हैश प्राप्त करता है। |
| [get_content_hash()](#get_content_hash__3) | कंटेंट हैश प्राप्त करता है। |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

नया उदाहरण प्रारंभ करता है [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | लेयर। |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

ब्लेंडिंग हैश प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | लेयर ब्लेंडिंग विकल्पों के लिए अद्वितीय हैश |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

चैनल्स हैश प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | सभी लेयर चैनलों का हैश |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

कंटेंट हैश प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | लेयर्स के महत्वपूर्ण पैरामीटरों का हैश। यह हैश सभी प्रकार के लेयर्स के लिए अलग होता है। |


