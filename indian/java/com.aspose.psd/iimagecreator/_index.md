---
title: "IImageCreator"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इमेज निर्माता."
type: docs
weight: 118
url: /hi/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

इमेज निर्माता.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | एक नया इमेज इंस्टेंस imageOptions के साथ बनाता है। |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


एक नया इमेज इंस्टेंस imageOptions के साथ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | इमेज डेटा बनाने के लिए स्ट्रीम कंटेनर। |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | छवि विकल्प। |
| width | int | नए इमेज की चौड़ाई |
| height | int | नए इमेज की ऊँचाई |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
