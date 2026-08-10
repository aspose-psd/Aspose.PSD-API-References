---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ImageExportersRegistry मेथड। निर्दिष्ट सहेजने के विकल्प और छवि के लिए उपयुक्त पहला पाया गया समर्थित डिस्क्रिप्टर प्राप्त करता है।"
type: docs
weight: 40
url: /hi/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

निर्दिष्ट सहेजने के विकल्प और इमेज के लिए उपयुक्त पहला पाया गया समर्थित विवरण प्राप्त करता है।

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | निर्यात करने के लिए छवि। |
| विकल्प | ImageOptionsBase | विकल्प। |

### रिटर्न वैल्यू

निर्दिष्ट छवि और सहेजने के विकल्पों को समर्थन करने वाला निर्यातकर्ता डिस्क्रिप्टर, या यदि ऐसा कोई डिस्क्रिप्टर नहीं मिला तो null।

## टिप्पणियाँ

पहला निर्यातकर्ता डिस्क्रिप्टर वास्तव में अंतिम पंजीकृत होगा।

### देखें भी

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


