---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लोडर गुणों को निर्दिष्ट करने वाला इमेज लोडर विवरणकर्ता."
type: docs
weight: 124
url: /hi/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

छवि लोडर डिस्क्रिप्टर जो लोडर गुणों को निर्दिष्ट करता है। लोडर डिस्क्रिप्टर का उपयोग प्रत्येक छवि लोडर इंस्टेंस को मेमोरी में रखने की आवश्यकता और मल्टीथ्रेडिंग समस्याओं को दूर करने के लिए किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | निर्धारित करता है कि क्या छवि लोडर निर्दिष्ट स्ट्रीम से नई छवि पढ़ सकता है और वैकल्पिक रूप से loadOptions का उपयोग कर सकता है। |
| [createInstance()](#createInstance--) | एक नया लोडर इंस्टेंस बनाता है। |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


निर्धारित करता है कि क्या छवि लोडर निर्दिष्ट स्ट्रीम से नई छवि पढ़ सकता है और वैकल्पिक रूप से loadOptions का उपयोग कर सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | loadOptions द्वारा निर्दिष्ट फ़ाइल फ़ॉर्मेट विवरण। loadOptions null भी हो सकता है। |

**Returns:**
boolean - true यदि इस डिस्क्रिप्टर द्वारा बनाया गया छवि लोडर स्ट्रीम से छवि पढ़ सकता है; अन्यथा false।
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


एक नया लोडर इंस्टेंस बनाता है।

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
