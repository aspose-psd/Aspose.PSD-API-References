---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ImageLoadersRegistry मेथड। निर्दिष्ट *stream* के लिए उपयुक्त पहला मिला हुआ समर्थित डिस्क्रिप्टर प्राप्त करता है और वैकल्पिक रूप से *loadOptions*।"
type: docs
weight: 40
url: /hi/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है जो निर्दिष्ट *stream* के लिए उपयुक्त है और वैकल्पिक रूप से *loadOptions* को भी।

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | स्ट्रीम। |
| loadOptions | LoadOptions | लोड विकल्प। |

### रिटर्न वैल्यू

निर्दिष्ट *stream* और *loadOptions* को समर्थन करने वाला लोडर डिस्क्रिप्टर या null यदि ऐसा कोई डिस्क्रिप्टर नहीं मिला।

## टिप्पणियाँ

पहला लोडर डिस्क्रिप्टर वास्तव में अंतिम पंजीकृत होगा।

### देखें भी

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


