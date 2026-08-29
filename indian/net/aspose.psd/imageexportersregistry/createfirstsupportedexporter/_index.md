---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ImageExportersRegistry मेथड। निर्दिष्ट सहेजने के विकल्प और छवि के लिए उपयुक्त पहला पाया गया निर्यातकर्ता बनाता है।"
type: docs
weight: 30
url: /hi/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

निर्दिष्ट सहेजने के विकल्प और इमेज के लिए उपयुक्त पहला पाया गया एक्सपोर्टर बनाता है।

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | निर्यात करने के लिए छवि। |
| विकल्प | ImageOptionsBase | निर्यात के लिए उपयोग करने वाले सहेजने के विकल्प। |

### रिटर्न वैल्यू

निर्दिष्ट छवि और सहेजने के विकल्पों को समर्थन करने वाला निर्यातकर्ता, या यदि ऐसा कोई निर्यातकर्ता नहीं मिला तो null।

## टिप्पणियाँ

पहला निर्यातकर्ता वास्तव में अंतिम पंजीकृत होगा।

### देखें भी

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


