---
title: "TiffOptions क्लास"
type: docs
weight: 130
url: /hi/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट रूप से लिटिल एंडियन कन्वेंशन उपयोग किया जाता है। |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions(options)](#TiffOptions_options_3) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions(tags)](#TiffOptions_tags_4) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | अल्फा स्टोरेज विकल्प प्राप्त करता है या सेट करता है। विकल्प जो [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            3 से अधिक [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) परिभाषित होने पर उपयोग किए जाते हैं। |
| कलाकार | string | r/w | कलाकार प्राप्त करता है या सेट करता है। |
| बिट्स_प्रति_पिक्सेल | int | r | पिक्सेल प्रति बिट प्राप्त करता है। |
| bits_per_sample | ushort | r/w | बिट्स प्रति सैंपल प्राप्त करता है या सेट करता है। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | tiff बाइट ऑर्डर दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| color_map | ushort | r/w | रंग मानचित्र को प्राप्त करता है या सेट करता है। |
| compressed_quality | int | r/w | संपीड़ित छवि गुणवत्ता को प्राप्त करता है या सेट करता है।<br/>            Jpeg संपीड़न के साथ उपयोग किया जाता है। |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | संपीड़न को प्राप्त करता है या सेट करता है। |
| copyright | string | r/w | कॉपीराइट को प्राप्त करता है या सेट करता है। |
| date_time | string | r/w | तारीख और समय को प्राप्त करता है या सेट करता है। |
| default_memory_allocation_limit | int | r/w | डिफ़ॉल्ट मेमोरी आवंटन सीमा प्राप्त करता है या सेट करता है। |
| default_replacement_font | string | r/w | डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में एक्सपोर्ट करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)।<br/>            डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| document_name | string | r/w | दस्तावेज़ का नाम प्राप्त करता है या सेट करता है। |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | EXIF IFD के पॉइंटर को प्राप्त या सेट करता है। |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | फ़ैक्स t4 विकल्पों को प्राप्त करता है या सेट करता है। |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | TIFF फ़ाइल मानक को प्राप्त करता है या सेट करता है। |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | बाइट बिट्स भरने का क्रम प्राप्त करता है या सेट करता है। |
| full_frame | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [full frame] है या नहीं। |
| half_tone_hints | ushort | r/w | हैल्फ़टोन संकेतों को प्राप्त करता है या सेट करता है। |
| image_description | string | r/w | छवि विवरण को प्राप्त करता है या सेट करता है। |
| image_length | uint | r/w | छवि की लंबाई को प्राप्त करता है या सेट करता है। |
| image_width | uint | r/w | छवि की चौड़ाई को प्राप्त करता है या सेट करता है। |
| ink_names | string | r/w | स्याही के नाम को प्राप्त करता है या सेट करता है। |
| is_extra_samples_present | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि अतिरिक्त नमूने मौजूद हैं या नहीं। |
| is_tiled | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि छवि टाइल्ड है या नहीं। |
| is_valid | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) सही ढंग से कॉन्फ़िगर किए गए हैं या नहीं। विफलता का कारण पता करने के लिए Validate मेथड का उपयोग करें। |
| max_sample_value | ushort | r/w | अधिकतम सैंपल मान को प्राप्त करता है या सेट करता है। |
| min_sample_value | ushort | r/w | न्यूनतम सैंपल मान को प्राप्त करता है या सेट करता है। |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | मल्टीपेज विकल्प |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | ओरिएंटेशन को प्राप्त करता है या सेट करता है। |
| page_name | string | r/w | पेज नाम को प्राप्त करता है या सेट करता है। |
| page_number | ushort | r/w | पेज नंबर टैग को प्राप्त करता है या सेट करता है। |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | कलर पैलेट प्राप्त करता है या सेट करता है। |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | फोटोमेट्रिक को प्राप्त करता है या सेट करता है। |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | प्लैनर कॉन्फ़िगरेशन को प्राप्त करता है या सेट करता है। |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | LZW कम्प्रेशन के लिए प्रेडिक्टर को प्राप्त करता है या सेट करता है। |
| premultiply_components | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए या नहीं। |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है। |
| rows_per_strip | uint | r/w | प्रति स्ट्रिप पंक्तियों को प्राप्त करता है या सेट करता है। |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | सैंपल फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| samples_per_pixel | ushort | r | प्रति पिक्सेल सैंपल प्राप्त करता है। इस प्रॉपर्टी मान को बदलने के लिए [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) प्रॉपर्टी सेट्टर का उपयोग करें। |
| scanner_manufacturer | string | r/w | स्कैनर निर्माता को प्राप्त करता है या सेट करता है। |
| scanner_model | string | r/w | स्कैनर मॉडल को प्राप्त करता है या सेट करता है। |
| smax_sample_value | uint | r/w | अधिकतम सैंपल मान को प्राप्त करता है या सेट करता है। इस मान का फ़ील्ड प्रकार सबसे उपयुक्त सैंपल डेटा (Byte, Short या Long प्रकार) से मेल खाता है। |
| smin_sample_value | uint | r/w | न्यूनतम सैंपल मान को प्राप्त करता है या सेट करता है। यह मान एक फ़ील्ड प्रकार रखता है जो सैंपल डेटा (Byte, Short या Long प्रकार) के साथ सबसे अधिक मेल खाता है। |
| software_type | string | r/w | सॉफ़्टवेयर प्रकार को प्राप्त करता है या सेट करता है। |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | छवि बनाने के लिए स्रोत को प्राप्त करता है या सेट करता है। |
| strip_byte_counts | uint | r/w | स्ट्रिप बाइट काउंट को प्राप्त करता है या सेट करता है। |
| strip_offsets | uint | r/w | स्ट्रिप ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | इस सबफ़ाइल में शामिल डेटा के प्रकार की सामान्य संकेतक को प्राप्त करता है या सेट करता है। |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | टैग को प्राप्त करता है या सेट करता है। |
| target_printer | string | r/w | लक्षित प्रिंटर को प्राप्त करता है या सेट करता है। |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | थ्रेशहोल्डिंग को प्राप्त करता है या सेट करता है। |
| tile_byte_counts | uint | r/w | टाइल बाइट काउंट को प्राप्त करता है या सेट करता है। |
| tile_length | uint | r/w | टाइल लंबाई को प्राप्त करता है या सेट करता है। |
| tile_offsets | uint | r/w | टाइल ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| tile_width | uint | r/w | टाइल चौड़ाई को प्राप्त करता है या सेट करता है। |
| total_pages | ushort | r | कुल पृष्ठों को प्राप्त करता है। |
| valid_tag_count | int | r | वैध टैग गिनती को प्राप्त करता है। यह कुल टैग गिनती नहीं है बल्कि उन टैगों की संख्या है जिन्हें संरक्षित किया जा सकता है। |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| xp_author | string | r/w | इमेज लेखक को प्राप्त करता है या सेट करता है, जो Windows Explorer द्वारा उपयोग किया जाता है। |
| xp_comment | string | r/w | इमेज पर टिप्पणी को प्राप्त करता है या सेट करता है, जो Windows Explorer द्वारा उपयोग किया जाता है। |
| xp_keywords | string | r/w | विषय इमेज को प्राप्त करता है या सेट करता है, जो Windows Explorer द्वारा उपयोग किया जाता है। |
| xp_subject | string | r/w | इमेज के बारे में जानकारी को प्राप्त करता है या सेट करता है, जो Windows Explorer द्वारा उपयोग किया जाता है। |
| xp_title | string | r/w | इमेज के बारे में जानकारी को प्राप्त करता है या सेट करता है, जो Windows Explorer द्वारा उपयोग किया जाता है। |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x स्थिति को प्राप्त करता है या सेट करता है। |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | YCbCrCoefficients को प्राप्त करता है या सेट करता है। |
| y_cb_cr_subsampling | ushort | r/w | YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग फैक्टर्स को प्राप्त करता है या सेट करता है। |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y स्थिति को प्राप्त करता है या सेट करता है। |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | एक नया टैग जोड़ता है। |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | टैग्स जोड़ता है। |
| [clone()](#clone__3) | इस इंस्टेंस की प्रतिलिपि बनाता है। |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | टाइप द्वारा टैग का इंस्टेंस प्राप्त करता है। |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | वैध टैग्स की गिनती प्राप्त करता है। |
| [is_tag_present(tag)](#is_tag_present_tag_6) | निर्धारित करता है कि टैग विकल्पों में मौजूद है या नहीं। |
| [remove_tag(tag)](#remove_tag_tag_7) | टैग को हटाता है। |
| validate() | यदि विकल्पों में टैग्स का वैध संयोजन है तो सत्यापित करता है। |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट रूप से लिटिल एंडियन कन्वेंशन उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | अपेक्षित tiff फ़ाइल फ़ॉर्मेट। |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | अपेक्षित tiff फ़ाइल फ़ॉर्मेट। |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | उपयोग करने के लिए TIFF फ़ाइल फ़ॉर्मेट बाइट क्रम। |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | कॉपी करने के लिए विकल्प। |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | विकल्पों को प्रारंभ करने के लिए टैग। |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

एक नया टैग जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | जोड़ने के लिए टैग। |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

टैग्स जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | जोड़ने के लिए टैग्स। |

### Method: clone() {#clone__3}


```
 clone() 
```

इस इंस्टेंस की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | इस इंस्टेंस की उथली प्रतिलिपि लौटाता है। |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

टाइप द्वारा टैग का इंस्टेंस प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | टैग कुंजी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | यदि मौजूद हो तो टैग का उदाहरण, अन्यथा null। |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

वैध टैग्स की गिनती प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | मान्य करने के लिए टैग्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | वैध टैग्स की गिनती। |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

निर्धारित करता है कि टैग विकल्पों में मौजूद है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | जाँचने के लिए टैग आईडी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि टैग मौजूद है; अन्यथा, <c>false</c>। |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

टैग को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | हटाने के लिए टैग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सफलतापूर्वक हटाने पर true |


