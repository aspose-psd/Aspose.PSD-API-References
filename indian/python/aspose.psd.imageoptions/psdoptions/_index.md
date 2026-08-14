---
title: "PsdOptions क्लास"
type: docs
weight: 100
url: /hi/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | नए [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PsdOptions(image)](#PsdOptions_image_2) | नए [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PsdOptions(options)](#PsdOptions_options_3) | नए [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है।<br/>            इसे पारदर्शी वस्तुओं के नीचे देखा जा सकता है। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| channel_bits_count | short | r/w | प्रति रंग चैनल बिट्स की गिनती प्राप्त करता है या सेट करता है। |
| चैनल्स_गणना | short | r/w | रंग चैनलों की गिनती प्राप्त करता है या सेट करता है। |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | psd रंग मोड प्राप्त करता है या सेट करता है। |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | psd संपीड़न विधि प्राप्त करता है या सेट करता है। |
| default_replacement_font | string | r/w | डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में एक्सपोर्ट करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)।<br/>            डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| full_frame | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [full frame] है या नहीं। |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | मल्टीपेज विकल्प |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | कलर पैलेट प्राप्त करता है या सेट करता है। |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है या सेट करता है। यह PSD या PSB हो सकता है। |
| refresh_image_preview_data | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [refresh image preview data] - विकल्प का उपयोग अन्य PSD इमेज व्यूअर्स के साथ संगतता को अधिकतम करने के लिए किया जाता है।<br/>            कृपया ध्यान दें, कॉम्पैक्ट फ्रेमवर्क प्लेटफ़ॉर्म के लिए अंतिम लेआउट में टेक्स्ट लेयर्स का ड्रॉइंग समर्थित नहीं है। |
| remove_global_text_engine_resource | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या - ग्लोबल टेक्स्ट इंजन रिसोर्स हटाएँ - कुछ टेक्स्ट-लेयर वाले psd फ़ाइलों के लिए उपयोग किया जाता है, केवल उस स्थिति में जब प्रोसेसिंग के बाद उन्हें Adobe Photoshop में नहीं खोला जा सकता (मुख्यतः अनुपलब्ध फ़ॉन्ट्स वाले टेक्स्ट लेयर्स के कारण)।<br/>            इस विकल्प का उपयोग करने के बाद, उपयोगकर्ता को Photoshop में खुले फ़ाइल में निम्न करना होगा: मेन्यू \"Text\" -> \"Process absent fonts\"। इसके बाद सभी टेक्स्ट फिर से दिखाई देंगे।<br/>            कृपया ध्यान दें, यह ऑपरेशन कुछ अंतिम लेआउट परिवर्तन कर सकता है। |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | psd संसाधनों को प्राप्त करता है या सेट करता है। |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | छवि बनाने के लिए स्रोत को प्राप्त करता है या सेट करता है। |
| update_metadata | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [update metadata]।<br/>            यदि मान true है, तो इमेज सहेजते समय मेटाडेटा अपडेट हो जाएगा। |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| version | int | r/w | psd फ़ाइल संस्करण प्राप्त करता है या सेट करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP डेटा कंटेनर को प्राप्त या सेट करें |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस इंस्टेंस की प्रतिलिपि बनाता है। |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

नए [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है।

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

नए [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | छवि। |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

नए [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | विकल्प। |

### Method: clone() {#clone__1}


```
 clone() 
```

इस इंस्टेंस की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | इस इंस्टेंस की उथली प्रतिलिपि लौटाता है। |


