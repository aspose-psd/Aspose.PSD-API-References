---
title: "IRasterImageRawDataLoader क्लास"
type: docs
weight: 2020
url: /hi/python-net/aspose.psd/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग समर्थित है या नहीं। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | कच्चा डेटा लोड करता है। |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

कच्चा डेटा लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | कच्चा डेटा लोड करने के लिए आयत। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | लोड किए गए डेटा के लिए उपयोग करने की कच्चा डेटा सेटिंग्स। नोट: यदि डेटा निर्दिष्ट प्रारूप में नहीं है तो डेटा रूपांतरण किया जाएगा। |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | कच्चा डेटा लोडर। |

