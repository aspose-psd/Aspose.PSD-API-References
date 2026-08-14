---
title: "JpegOptions क्लास"
type: docs
weight: 60
url: /hi/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | नया उदाहरण प्रारंभ करता है [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) क्लास का। |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | नया उदाहरण प्रारंभ करता है [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | लॉसलैस jpeg छवि के लिए प्रति चैनल बिट्स प्राप्त करता है या सेट करता है। अब हम 2 से 8 बिट्स प्रति चैनल का समर्थन करते हैं। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg छवियों के लिए गंतव्य CMYK रंग प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे RGBColorProfile के साथ जोड़ी में होना चाहिए। |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | jpeg छवि के लिए रंग प्रकार प्राप्त करता है या सेट करता है। |
| टिप्पणी | string | r/w | jpeg फ़ाइल टिप्पणी प्राप्त करता है या सेट करता है। |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | संपीड़न प्रकार प्राप्त करता है या सेट करता है। |
| default_memory_allocation_limit | int | r/w | डिफ़ॉल्ट मेमोरी आवंटन सीमा प्राप्त करता है या सेट करता है। |
| default_replacement_font | string | r/w | डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में एक्सपोर्ट करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)।<br/>            डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | exif डेटा कंटेनर प्राप्त करें या सेट करें |
| full_frame | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [full frame] है या नहीं। |
| horizontal_sampling | byte | r/w | प्रत्येक घटक के लिए क्षैतिज सबसैंपलिंग प्राप्त करता है या सेट करता है। |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | jfif प्राप्त करता है या सेट करता है। |
| jpeg_ls_allowed_lossy_error | int | r/w | निकट-निष्प्रभावी कोडिंग के लिए JPEG-LS अंतर सीमा (JPEG-LS विनिर्देश से NEAR पैरामीटर) प्राप्त करता है या सेट करता है। |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | JPEG-LS इंटरलीव मोड प्राप्त करता है या सेट करता है। |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | JPEG-LS प्रीसेट पैरामीटर प्राप्त करता है या सेट करता है। |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | मल्टीपेज विकल्प |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | कलर पैलेट प्राप्त करता है या सेट करता है। |
| preblend_alpha_if_present | bool | r/w | यदि अल्फा चैनल मौजूद है तो लाल, हरा और नीला घटक पृष्ठभूमि रंग के साथ मिश्रित किए जाने चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| गुणवत्ता | int | r/w | छवि गुणवत्ता प्राप्त करता है या सेट करता है। |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | RD ऑप्टिमाइज़र सेटिंग्स प्राप्त करता है या सेट करता है। |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है। |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg छवियों के लिए गंतव्य RGB रंग प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे CMYKColorProfile के साथ जोड़ी में होना चाहिए। |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड प्राप्त करता है या सेट करता है। <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | स्केल्ड गुणवत्ता। |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | छवि बनाने के लिए स्रोत को प्राप्त करता है या सेट करता है। |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| vertical_sampling | byte | r/w | प्रत्येक घटक के लिए ऊर्ध्वाधर सबसैंपलिंग को प्राप्त करता है या सेट करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस इंस्टेंस की प्रतिलिपि बनाता है। |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

नया उदाहरण प्रारंभ करता है [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) क्लास का।

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

नया उदाहरण प्रारंभ करता है [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | JPEG विकल्प। |

### Method: clone() {#clone__1}


```
 clone() 
```

इस इंस्टेंस की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | इस इंस्टेंस की उथली प्रतिलिपि लौटाता है। |


