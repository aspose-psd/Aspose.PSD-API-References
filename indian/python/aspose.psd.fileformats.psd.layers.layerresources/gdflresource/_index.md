---
title: "GdFlResource क्लास"
type: docs
weight: 330
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | GdFlResource क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| align_with_layer | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [align with layer]। |
| कोण | डबल | r/w | कोण प्राप्त करता है या सेट करता है। |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | RGB का रंग प्राप्त करता है। |
| color_model | string | r/w | रंग मॉडल - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | रंग बिंदुओं को प्राप्त करता है। |
| dither | bool | r/w | यह निर्धारित करने के लिए मान प्राप्त करता है या सेट करता है कि यह [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) डिथर है या नहीं। |
| gradient_interval | डबल | r/w | ग्रेडिएंट अंतराल को प्राप्त करता है या सेट करता है। |
| gradient_mode | string | r/w | इस ग्रेडिएंट का मोड।<br/>            निर्धारित करता है 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\"। |
| gradient_name | string | r/w | ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है। |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| horizontal_offset | डबल | r/w | क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat का अधिकतम रंग। |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat का न्यूनतम रंग। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| reverse | bool | r/w | यह निर्धारित करने के लिए मान प्राप्त करता है या सेट करता है कि यह [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) रिवर्स है या नहीं। |
| rnd_number_seed | int | r/w | Noise ग्रेडिएंट के लिए रंग उत्पन्न करने हेतु उपयोग किया जाने वाला रैंडम नंबर सीड। |
| roughness | int | r/w | रफ़नेस कारक। |
| scale | int | r/w | scale को प्राप्त करता है या सेट करता है। |
| show_transparency | bool | r/w | पारदर्शिता दिखाने के लिए फ़्लैग। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | पारदर्शिता बिंदुओं को प्राप्त करता है। |
| use_vector_color | bool | r/w | वेक्टर रंग उपयोग करने के लिए फ़्लैग। |
| vertical_offset | डबल | r/w | ऊर्ध्वाधर ऑफ़सेट प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

GdFlResource क्लास का नया उदाहरण प्रारंभ करता है

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |

