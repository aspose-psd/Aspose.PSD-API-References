---
title: "टाइमलाइन क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Timeline()](#Timeline__1) | टाइमलाइन क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| active_frame_index | int | r | सक्रिय फ्रेम सूचकांक प्राप्त करता है। |
| af_st | int | r/w | AFSt मान को प्राप्त करता है या सेट करता है। |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | फ़्रेमों की सूची प्राप्त करता है। |
| fs_id | int | r/w | FsID मान को प्राप्त करता है या सेट करता है। |
| loopes_count | ushort | r/w | लूपों की गिनती को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर PsdImage और टाइमलाइन डेटा को सहेजता है। |
| [save(output_stream, options)](#save_output_stream_options_2) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट स्ट्रीम पर PsdImage और टाइमलाइन डेटा को सहेजता है। |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | सक्रिय फ्रेम को लक्षित फ्रेम में बदलता है। |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

टाइमलाइन क्लास का नया उदाहरण प्रारंभ करता है

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर PsdImage और टाइमलाइन डेटा को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट स्ट्रीम पर PsdImage और टाइमलाइन डेटा को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | आउटपुट स्ट्रीम। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

सक्रिय फ्रेम को लक्षित फ्रेम में बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_active_frame_index | int | लक्षित फ्रेम इंडेक्स। |

