---
title: "IImageExporter"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इमेज निर्यातकर्ता."
type: docs
weight: 121
url: /hi/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

यह इमेज एक्सपोर्टर है। आंतरिक Aspose.Imaging फ़ॉर्मेट से डेटा को निर्दिष्ट डेटा फ़ॉर्मेट में निर्यात कर सकता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | निर्दिष्ट इमेज डेटा को निर्दिष्ट डेटा फ़ॉर्मेट में निर्यात करता है। |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | निर्दिष्ट इमेज डेटा को निर्दिष्ट डेटा फ़ॉर्मेट में निर्यात करता है। |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


निर्दिष्ट इमेज डेटा को निर्दिष्ट डेटा फ़ॉर्मेट में निर्यात करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | निर्यात करने के लिए इमेज डेटा। |
| stream | java.io.OutputStream | डेटा निर्यात करने के लिए स्ट्रीम। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | इमेज निर्यात के विकल्प |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


निर्दिष्ट इमेज डेटा को निर्दिष्ट डेटा फ़ॉर्मेट में निर्यात करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | निर्यात करने के लिए इमेज डेटा। |
| stream | java.io.OutputStream | डेटा निर्यात करने के लिए स्ट्रीम। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | इमेज निर्यात के विकल्प |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | सीमाओं का आयत। |

