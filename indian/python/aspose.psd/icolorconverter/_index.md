---
title: "IColorConverter क्लास"
type: docs
weight: 1690
url: /hi/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | प्रदान किए गए डेटा को आउटपुट फ़ॉर्मेट में परिवर्तित करता है। |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

प्रदान किए गए डेटा को आउटपुट फ़ॉर्मेट में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | स्रोत प्रारूप। |
| data | byte | स्रोत डेटा। |
| offset | int | डेटा कॉपी शुरू होने वाले बाइट्स में ऑफ़सेट। |
| bit_start | int | बिट प्रारंभ। ध्यान दें कि यह मान बाइट संरेखित नहीं है, बल्कि वह वास्तविक बिट है जहाँ कॉपी शुरू होनी चाहिए। |
| samples_count | int | सैंपल्स की गणना। |
| lines_count | int | पंक्तियों की गणना। |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | गंतव्य प्रारूप। |
| output_data | byte | आउटपुट डेटा। |
| output_offset | int | आउटपुट ऑफ़सेट जहाँ डेटा कॉपी शुरू होनी चाहिए। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | परिवर्तित बाइट्स की गिनती। |


