---
title: "LayerMaskDataFull क्लास"
type: docs
weight: 980
url: /hi/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | LayerMaskDataFull क्लास का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| background_color | byte | r/w | पृष्ठभूमि रंग प्राप्त करता है या सेट करता है। |
| नीचे | int | r/w | नीचे की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| data_size | int | r | लेयर मास्क डेटा का आकार प्राप्त करता है। |
| default_color | byte | r/w | डिफ़ॉल्ट रंग को प्राप्त करता है या सेट करता है। |
| enclosing_bottom | int | r/w | PSD इमेज लेयर में एनक्लोज़िंग नीचे रास्टर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| enclosing_left | int | r/w | PSD फ़ाइल लेयर में एनक्लोज़िंग बाएँ रास्टर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| enclosing_right | int | r/w | PSD फ़ाइल लेयर में एनक्लोज़िंग दाएँ रास्टर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| enclosing_top | int | r/w | PSD इमेज लेयर में रास्टर मास्क की एनक्लोज़िंग ऊपर स्थिति को प्राप्त करता है या सेट करता है। |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | लेयर मास्क फ्लैग्स को प्राप्त करता है या सेट करता है। |
| image_data | byte | r/w | PSD फ़ाइल में लेयर मास्क डेटा (या संयुक्त/अंतिम मास्क यदि वेक्टर मास्क है) को प्राप्त करता है या सेट करता है। |
| left | int | r/w | बाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | लेयर मास्क के मास्क [Rectangle](/psd/python-net/aspose.psd/rectangle/) को PSD फ़ाइल में प्राप्त करता है या सेट करता है।<br/>            यह बाएँ, दाएँ, ऊपर और नीचे की प्रॉपर्टीज़ लेता है और [Rectangle](/psd/python-net/aspose.psd/rectangle/) बनाता है। |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है जो उपयोगकर्ता / रास्टर मास्क के लिए उपयोग होते हैं। वेक्टर मास्क के लिए Flags प्रॉपर्टी का उपयोग किया जाता है। |
| right | int | r/w | दाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| ऊपर | int | r/w | ऊपर की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| user_mask_data | byte | r/w | PSD फ़ाइल में लेयर के उपयोगकर्ता (रास्टर) मास्क डेटा को प्राप्त करता है या सेट करता है। (MaskData प्रॉपर्टी में एक रास्टराइज़्ड वेक्टर मास्क मौजूद है)। |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD इमेज लेयर में उपयोगकर्ता मास्क (घेरने वाला) आयत को प्राप्त करता है या सेट करता है। |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

LayerMaskDataFull क्लास का नया उदाहरण प्रारंभ करता है।

