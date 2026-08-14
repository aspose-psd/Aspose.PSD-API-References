---
title: "AiLayerSection क्लास"
type: docs
weight: 50
url: /hi/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| नीला | int | r/w | नीले रंग घटक को प्राप्त करता है या सेट करता है। |
| color_index | int | r/w | रंग का सूचकांक प्राप्त करता है या सेट करता है।<br/>            यह तर्क –1 और 26 के बीच मान ले सकता है। प्रत्येक पूर्णांक<br/>            एक रंग का प्रतिनिधित्व करता है जिसे उपयोगकर्ता द्वारा लेयर को पहचानने के लिए असाइन किया जा सकता है। |
| color_number | int | r/w | रंग संख्या प्राप्त करता है या सेट करता है। -1 लाल, हरा, नीला गुणों से कस्टम रंग मान है।<br/>            लेयर की रंग सेटिंग निर्दिष्ट करता है। |
| dim_value | int | r/w | डिम मान को प्रतिशत के रूप में प्राप्त करता है या सेट करता है।<br/>            लेयर में शामिल लिंक्ड इमेज और बिटमैप इमेज की तीव्रता को निर्दिष्ट प्रतिशत तक कम करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| हरा | int | r/w | ग्रीन रंग घटक को प्राप्त करता है या सेट करता है। |
| has_multi_layer_masks | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह इंस्टेंस मल्टीलेयर मास्क रखता है या नहीं। |
| is_images_dimmed | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह लेयर मंद है या नहीं।<br/>            लेयर में शामिल लिंक्ड इमेजेज़ और बिटमैप इमेजेज़ की तीव्रता को कम करता है। |
| is_locked | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह लेयर लॉक है या नहीं।<br/>            आइटम में परिवर्तन को रोकता है। |
| is_preview | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह लेयर प्रीव्यू है या नहीं।<br/>            लेयर में मौजूद कलाकृति को रूपरेखा के बजाय रंग में प्रदर्शित करता है। |
| is_printed | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह लेयर प्रिंटेड है या नहीं।<br/>            यदि सत्य हो तो लेयर में मौजूद कलाकृति को प्रिंट करने योग्य बनाता है। |
| is_shown | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह लेयर दिखाया गया है या नहीं।<br/>            यदि सत्य हो तो लेयर में मौजूद सभी कलाकृति को आर्टबोर्ड पर प्रदर्शित करता है। |
| is_template | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह लेयर एक टेम्पलेट लेयर है या नहीं। |
| name | string | r/w | लेयर का नाम प्राप्त करता है या सेट करता है।<br/>            लेयर पैनल में दिखाई देने वाले आइटम का नाम निर्दिष्ट करता है। |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | रास्टर इमेजेज़ को प्राप्त करता है। |
| लाल | int | r/w | रेड रंग घटक को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | रास्टर इमेज जोड़ता है। |
| [get_data()](#get_data__2) | स्ट्रिंग डेटा प्राप्त करता है। |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

रास्टर इमेज जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | रास्टर इमेज। |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

स्ट्रिंग डेटा प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | सेक्शन का स्ट्रिंग डेटा |


