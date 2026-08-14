---
title: "PngOptions क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | नया उदाहरण प्रारंभ करता है [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) क्लास का। |
| [PngOptions(png_options)](#PngOptions_png_options_2) | नया उदाहरण प्रारंभ करता है [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | डिफ़ॉल्ट संपीड़न स्तर। |
| bit_depth | byte | r/w | बिट गहराई। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | रंग के प्रकार को प्राप्त करता है या सेट करता है। |
| compression_level | int | r/w | 0-9 सीमा में PNG छवि संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न है और 0 स्टोर मोड है। |
| default_replacement_font | string | r/w | डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में एक्सपोर्ट करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)।<br/>            डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | PNG फ़ाइल सहेजने प्रक्रिया के दौरान उपयोग किए जाने वाले फ़िल्टर प्रकार को प्राप्त करता है या सेट करता है। |
| full_frame | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [full frame] है या नहीं। |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | मल्टीपेज विकल्प |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | कलर पैलेट प्राप्त करता है या सेट करता है। |
| progressive | bool | r/w | इस [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) के प्रोग्रेसिव होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | छवि बनाने के लिए स्रोत को प्राप्त करता है या सेट करता है। |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस इंस्टेंस की प्रतिलिपि बनाता है। |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

नया उदाहरण प्रारंभ करता है [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) क्लास का।

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

नया उदाहरण प्रारंभ करता है [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | PNG विकल्प। |

### Method: clone() {#clone__1}


```
 clone() 
```

इस इंस्टेंस की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | इस इंस्टेंस की उथली प्रतिलिपि लौटाता है। |


