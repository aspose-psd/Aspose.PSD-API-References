---
title: "GrdmResource क्लास"
type: docs
weight: 340
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | नई इंस्टेंस को प्रारंभ करता है [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) क्लास की। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| color_model | short | r/w | कलर मॉडल।<br/>            जब 'Gradient type' = 'Noise' हो, तो हम 'Color Model' को RGB/SHB/LAB (3/4/6) पर सेट कर सकते हैं। |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | रंग बिंदुओं को प्राप्त करता है या सेट करता है। |
| डिथर | bool | r/w | क्या ग्रेडिएंट डिथर किया गया है। |
| expansion_count | short | r/w | विस्तार गणना ( = 2 Photoshop 6.0 के लिए)। |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | इस ग्रेडिएंट का मोड<br/>            निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)। |
| gradient_name | string | r/w | ग्रेडिएंट का नाम: यूनिकोड स्ट्रिंग, पैडेड। |
| इंटरपोलेशन | short | r/w | इंटरपोलेशन। निर्धारित करता है स्मूदनेस, जब 'Gradient Type' = 'Solid' (GradientMode = 0)। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का अधिकतम रंग।<br/>            रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है। |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का न्यूनतम रंग।<br/>            रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| उल्टा | bool | r/w | क्या ग्रेडिएंट उल्टा है। |
| rnd_number_seed | int | r/w | Noise ग्रेडिएंट के लिए रंग उत्पन्न करने हेतु उपयोग किया जाने वाला रैंडम नंबर सीड। |
| roughness | int | r/w | रफ़नेस फ़ैक्टर<br/>            जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) सेट कर सकते हैं। |
| show_transparency | short | r/w | पारदर्शिता दिखाने का फ़्लैग<br/>            जब 'Gradient type' = 'Noise' हो, तो हम 'Add transparency' को true सेट कर सकते हैं। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है। |
| use_vector_color | short | r/w | वेक्टर रंग उपयोग करने के लिए फ़्लैग। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स डेटा को सहेजता है। |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

नई इंस्टेंस को प्रारंभ करता है [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) क्लास की।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| psd_version | int | रिसोर्स का psd संस्करण। |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स डेटा को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |

