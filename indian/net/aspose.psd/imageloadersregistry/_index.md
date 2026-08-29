---
title: "क्लास ImageLoadersRegistry"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageLoadersRegistry क्लास। इमेज लोडर्स रजिस्ट्री का प्रतिनिधित्व करता है"
type: docs
weight: 5270
url: /hi/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

इमेज लोडर्स रजिस्ट्री का प्रतिनिधित्व करता है।

```csharp
public static class ImageLoadersRegistry
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | पंजीकृत डिस्क्रिप्टर प्राप्त करता है। |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | पंजीकृत इमेज लोडिंग फ़ॉर्मेट्स प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | निर्दिष्ट *stream* के लिए उपयुक्त पहला मिला लोडर बनाता है और वैकल्पिक रूप से *loadOptions* को भी। |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है जो निर्दिष्ट *stream* के लिए उपयुक्त है और वैकल्पिक रूप से *loadOptions* को भी। |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | उसके टाइप नाम द्वारा पहला समर्थित फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | उसके प्रकार नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | निर्दिष्ट इमेज लोडर डिस्क्रिप्टर को रजिस्टर करता है। |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | लोडर को रजिस्टर करता है। |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | लोडर को अनरजिस्टर करता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


