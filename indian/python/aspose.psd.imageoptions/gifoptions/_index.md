---
title: "GifOptions क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | नया उदाहरण प्रारंभ करता है [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) क्लास का। |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | नया उदाहरण प्रारंभ करता है [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | GIF पृष्ठभूमि रंग सूचकांक प्राप्त करता है या सेट करता है। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| color_resolution | byte | r/w | GIF रंग रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| default_replacement_font | string | r/w | डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में एक्सपोर्ट करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)।<br/>            डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| do_palette_correction | bool | r/w | पैलेट सुधार लागू है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| full_frame | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [full frame] है या नहीं। |
| has_trailer | bool | r/w | GIF में ट्रेलर है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| interlaced | bool | r/w | True यदि छवि को इंटरलेस्ड होना चाहिए। |
| is_palette_sorted | bool | r/w | पैलेट प्रविष्टियों का क्रमबद्ध है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| max_diff | int | r/w | अधिकतम अनुमत पिक्सेल अंतर प्राप्त करता है या सेट करता है। यदि शून्य से अधिक है, तो लॉसी संपीड़न उपयोग किया जाएगा।<br/>            इष्टतम लॉसी संपीड़न के लिए अनुशंसित मान 80 है। 30 बहुत हल्का संपीड़न है, 200 भारी है।<br/>            यह तब सबसे अच्छा काम करता है जब केवल थोड़ा नुकसान प्रस्तुत किया जाता है, और संपीड़न एल्गोरिदम की सीमा के कारण बहुत उच्च नुकसान स्तर अधिक लाभ नहीं देते।<br/>            अनुमत मानों की सीमा [0, 1000] है। |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | मल्टीपेज विकल्प |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | कलर पैलेट प्राप्त करता है या सेट करता है। |
| pixel_aspect_ratio | byte | r/w | GIF पिक्सेल पहलू अनुपात प्राप्त करता है या सेट करता है। |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | छवि बनाने के लिए स्रोत को प्राप्त करता है या सेट करता है। |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस इंस्टेंस की प्रतिलिपि बनाता है। |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

नया उदाहरण प्रारंभ करता है [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) क्लास का।

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

नया उदाहरण प्रारंभ करता है [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | यह GIF विकल्प। |

### Method: clone() {#clone__1}


```
 clone() 
```

इस इंस्टेंस की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | इस इंस्टेंस की उथली प्रतिलिपि लौटाता है। |


