---
title: "BlwhResource क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | BlwhResource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| black_and_white_preset_file_name | string | r/w | काली और सफेद प्रीसेट फ़ाइल नाम को प्राप्त करता है या सेट करता है। |
| नीले | int | r/w | नीले मान को प्राप्त करता है या सेट करता है। |
| bw_preset_kind | int | r/w | काली और सफेद प्रीसेट प्रकार मान को प्राप्त करता है या सेट करता है। |
| सियान | int | r/w | सियान मान को प्राप्त करता है या सेट करता है। |
| हरे | int | r/w | हरे मान को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| मैजेंटा | int | r/w | मैजेंटा मान को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| लाल | int | r/w | reds मान को प्राप्त करता है या सेट करता है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| tint_color | int | r/w | Tint Color ARGB मान को प्राप्त करता है या सेट करता है। |
| use_tint | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] उपयोग किया गया है या नहीं। |
| yellows | int | r/w | yellows मान को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

BlwhResource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

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

