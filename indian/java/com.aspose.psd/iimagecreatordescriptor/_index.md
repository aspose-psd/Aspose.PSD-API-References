---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "निर्माता गुणों को निर्दिष्ट करने वाला इमेज निर्माता विवरणकर्ता."
type: docs
weight: 119
url: /hi/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

छवि निर्माता विवरणकर्ता, जो निर्माता गुणों को निर्दिष्ट करता है। निर्माता विवरणकर्ता का उपयोग प्रत्येक छवि निर्माता इंस्टेंस को मेमोरी में रखने की आवश्यकता और मल्टीथ्रेडिंग समस्याओं को दूर करने के लिए किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | निर्धारित करता है कि क्या छवि निर्माता निर्दिष्ट  imageOptions  का उपयोग करके नई छवि बना सकता है। |
| [createInstance()](#createInstance--) | एक नया निर्माता इंस्टेंस बनाता है। |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


निर्धारित करता है कि क्या छवि निर्माता निर्दिष्ट  imageOptions  का उपयोग करके नई छवि बना सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | छवि विकल्प। |

**Returns:**
boolean -  true  यदि इस विवरणकर्ता द्वारा निर्मित छवि निर्माता निर्दिष्ट  imageOptions  का उपयोग करके छवि डेटा बना सकता है; अन्यथा,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


एक नया निर्माता इंस्टेंस बनाता है।

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
