---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ImageLoadersRegistry विधि। निर्दिष्ट stream के लिए उपयुक्त पहला मिला लोडर बनाता है और वैकल्पिक रूप से loadOptions।"
type: docs
weight: 30
url: /hi/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

निर्दिष्ट *stream* के लिए उपयुक्त पहला मिला लोडर बनाता है और वैकल्पिक रूप से *loadOptions* को भी।

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | स्ट्रीम। |
| loadOptions | LoadOptions | लोड विकल्प। |

### रिटर्न वैल्यू

निर्दिष्ट *stream* और *loadOptions* को समर्थन करने वाला लोडर, या यदि ऐसा कोई लोडर नहीं मिला तो null।

## टिप्पणियाँ

पहला लोडर वास्तव में अंतिम पंजीकृत होगा।

### देखें भी

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


