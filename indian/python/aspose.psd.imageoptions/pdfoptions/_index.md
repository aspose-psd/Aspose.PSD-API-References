---
title: "PdfOptions क्लास"
type: docs
weight: 80
url: /hi/python-net/aspose.psd.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PdfOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | PdfOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| default_replacement_font | string | r/w | डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में एक्सपोर्ट करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)।<br/>            डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| full_frame | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [full frame] है या नहीं। |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | मल्टीपेज विकल्प |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | पेज का आकार प्राप्त करता है या सेट करता है। |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | कलर पैलेट प्राप्त करता है या सेट करता है। |
| pdf_core_options | [PdfCoreOptions](/psd/python-net/aspose.psd.fileformats.pdf/pdfcoreoptions/) | r/w | PDF कोर विकल्प |
| pdf_document_info | [PdfDocumentInfo](/psd/python-net/aspose.psd.fileformats.pdf/pdfdocumentinfo/) | r/w | दस्तावेज़ के लिए मेटाडेटा प्राप्त करता है या सेट करता है। |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | छवि बनाने के लिए स्रोत को प्राप्त करता है या सेट करता है। |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस इंस्टेंस की प्रतिलिपि बनाता है। |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

PdfOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### Method: clone() {#clone__1}


```
 clone() 
```

इस इंस्टेंस की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | इस इंस्टेंस की उथली प्रतिलिपि लौटाता है। |


