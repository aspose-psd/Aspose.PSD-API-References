---
title: "BritResource वर्ग"
type: docs
weight: 120
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [BritResource()](#BritResource__1) | एक नया उदाहरण प्रारंभ करता है [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) वर्ग का। |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | एक नया उदाहरण प्रारंभ करता है [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) वर्ग का। |
| [BritResource(bytes)](#BritResource_bytes_3) | एक नया उदाहरण प्रारंभ करता है [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) वर्ग।<br/>            PSD फ़ॉर्मेट विनिर्देशन में निम्न विवरण शामिल है:<br/>            2 ब्राइटनेस<br/>            2 कॉन्ट्रास्ट<br/>            2 ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान<br/>            1 केवल लैब रंग<br/>            यह आधुनिक PSD (CS5 और उससे ऊपर) में उपयोग नहीं होता जहाँ CgEd है। CgEd जानकारी गुण संग्रहीत करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| चमक | short | r/w | ब्राइटनेस को प्राप्त करता है या सेट करता है। |
| कॉन्ट्रास्ट | short | r/w | कॉन्ट्रास्ट को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| lab_color | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [lab color] है या नहीं। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| mean_value_for_brightness_and_contrast | short | r/w | ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

एक नया उदाहरण प्रारंभ करता है [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) वर्ग का।

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

एक नया उदाहरण प्रारंभ करता है [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) वर्ग का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| चमक | short | ब्राइटनेस। |
| कॉन्ट्रास्ट | short | कॉन्ट्रास्ट। |
| mean_value_for_brightness_and_contrast | short | ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान। |
| lab_color | bool | यदि <c>true</c> सेट किया गया है [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

एक नया उदाहरण प्रारंभ करता है [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) वर्ग।<br/>            PSD फ़ॉर्मेट विनिर्देशन में निम्न विवरण शामिल है:<br/>            2 ब्राइटनेस<br/>            2 कॉन्ट्रास्ट<br/>            2 ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान<br/>            1 केवल लैब रंग<br/>            यह आधुनिक PSD (CS5 और उससे ऊपर) में उपयोग नहीं होता जहाँ CgEd है। CgEd जानकारी गुण संग्रहीत करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बाइट्स | byte | बाइट्स। |

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

