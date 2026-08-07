---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इमेज निर्यातकर्ता विवरणकर्ता को दर्शाता है."
type: docs
weight: 122
url: /hi/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

छवि निर्यातकर्ता विवरणकर्ता का प्रतिनिधित्व करता है। निर्यातकर्ता विवरणकर्ता का उपयोग प्रत्येक निर्यातकर्ता इंस्टेंस को मेमोरी में रखने की आवश्यकता और मल्टीथ्रेडिंग समस्याओं को दूर करने के लिए किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | निर्धारित करता है कि क्या छवि निर्यातकर्ता निर्दिष्ट छवि को सहेजने विकल्पों द्वारा निर्दिष्ट छवि प्रारूप में निर्यात कर सकता है। |
| [createInstance()](#createInstance--) | एक नया निर्यातकर्ता इंस्टेंस बनाता है। |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


निर्धारित करता है कि क्या छवि निर्यातकर्ता निर्दिष्ट छवि को सहेजने विकल्पों द्वारा निर्दिष्ट छवि प्रारूप में निर्यात कर सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | निर्यात करने के लिए छवि। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | विकल्पों का आधार। |

**Returns:**
boolean - true यदि इस विवरणकर्ता द्वारा बनाया गया निर्यातकर्ता निर्दिष्ट छवि को निर्दिष्ट फ़ाइल प्रारूप में निर्यात कर सकता है; अन्यथा, false।
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


एक नया निर्यातकर्ता इंस्टेंस बनाता है।

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
